#### Test 1133518510faaea9_thali04_samsung-SM-G930F Logs


```
--------- beginning of system
,07-14 13:28:04.918  3707  3922 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-14 13:28:04.919  3707  3922 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-14 13:28:04.920  3707  3922 D BatteryService: online:4, current avg:153, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:153
07-14 13:28:04.920  3707  3707 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-14 13:28:04.933  3707  3707 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-14 13:28:04.933  3707  3707 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
07-14 13:28:04.937  3707  3707 D GameManagerService: new battery level: 100
--------- beginning of main
07-14 13:28:04.942  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-14 13:28:04.942  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
07-14 13:28:04.950  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
07-14 13:28:04.966  4056  4056 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-14 13:28:04.967  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
07-14 13:28:04.967  4056  4485 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-14 13:28:04.968  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
07-14 13:28:04.984  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
07-14 13:28:05.263  4497  4497 D io_stats: !@   8,0 r 24533 2204212 w 4349 194376 d 536 72544 f 1749 1749 iot 10570 10107 th 506412 0 0 pt 0 inp 0 0 166.377
07-14 13:28:05.441  9503  9503 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 9503 | app_process
07-14 13:28:05.441  9503  9503 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
07-14 13:28:05.447  9503  9503 E appproc : Enhanced Zygote ASLR: ro.knox.enhance.zygote.aslr != 1. Enhanced Zygote ASLR is DISABLED!
07-14 13:28:05.447  9503  9503 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-14 13:28:05.449  9503  9503 D AndroidRuntime: CheckJNI is OFF
07-14 13:28:05.449  9503  9503 D AndroidRuntime: addProductProperty: start
07-14 13:28:05.488  9503  9503 I [saiv 1.1]: saiv_OnLoadJNI.cpp(38): _init: Version 1.1 Build # 3532
07-14 13:28:05.488  9503  9503 I [saiv 1.1]: saiv_OnLoadJNI.cpp(43): _init: _init() was called
07-14 13:28:05.504  9503  9503 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-14 13:28:05.504  9503  9503 I MLDAP   :            libMLDAP/MLDAP.c:  53:  MLDAP_LIB v1.1.15
07-14 13:28:05.504  9503  9503 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-14 13:28:05.547  9503  9503 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl
07-14 13:28:05.565  9503  9503 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-14 13:28:05.588  9503  9503 I Enhanced Zygote ASLR: DISABLED!
07-14 13:28:05.588  9503  9503 I Radio-JNI: register_android_hardware_Radio DONE
07-14 13:28:05.591  9503  9503 D ReflectionHelper: loadKlass() : caller=android.app.Activity.<clinit>:7525 <bottom of call stack> 
07-14 13:28:05.591  9503  9503 D ReflectionHelper: Reflecting method.....  class <onScreenChanged>
07-14 13:28:05.592  9503  9503 E SemAffinityControl: SemAffinityControl: registerfunction enter
07-14 13:28:05.600  9503  9503 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-14 13:28:05.618  3707  4737 I ActivityManager: START u0 {act=null typ=null flg=0x10000000 cmp=ComponentInfo{com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}} from uid 2000 on display 0
07-14 13:28:05.656  3707  4737 D ActivityManager: ActivityRecord() Constructor : multiScreenAttrs=MultiScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
07-14 13:28:05.657  3707  4737 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3707  pkgName : AMS_RESUME@CPU_MIN@7
07-14 13:28:05.658  3707  4737 D ActivityManager: mActivityResumeBooster.acquire()
07-14 13:28:05.660  3707  4737 I MultiWindowManagerService: setTaskDimensions: Task=TaskRecord{4bf3decd0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} minWidth=-1 minHeight=-1 maxWidth=-1 maxHeight=-1
07-14 13:28:05.660  3707  4737 D ActivityManager: moveToFront() : reason=startedActivity setFocusedActivity isAttached=true TaskRecord{4bf3decd0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1}
07-14 13:28:05.660  3707  4737 D InputDispatcher: Focused application set to: xxxx
07-14 13:28:05.660  3707  4737 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=TaskRecord{4bf3decd0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} next=ActivityRecord{785c0d0 u0 com.thaliproject.thalitest/.MainActivity t5} mFocusedStack=ActivityStack{c202c12d0 stackId=1, 2 tasks}
07-14 13:28:05.661  3707  4737 D MountService: getExternalStorageMountMode : 1
07-14 13:28:05.661  3707  4737 D MountService: getExternalStorageMountMode : 3
07-14 13:28:05.661  3707  4737 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10033, packageName : com.thaliproject.thalitest
07-14 13:28:05.664  3707  3803 D WindowManager: addWindow: android.view.ViewRootImpl$W@9715e84 displayId=0
07-14 13:28:05.665  3707  3803 D InputTransport: Input channel constructed: fd=453
07-14 13:28:05.665  3707  3803 D InputTransport: Input channel constructed: fd=454
07-14 13:28:05.665  3707  3803 D ViewRootImpl@d591c97[thalitest]: setView = DecorView@dbf42a2[thalitest] touchMode=true
07-14 13:28:05.669  3707  3803 V WindowManager: Relayout Window{e29a66dd0 u0 Starting com.thaliproject.thalitest}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
07-14 13:28:05.670  3113  3113 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, uhalitest
07-14 13:28:05.673  3707  4737 I ActivityManager: Start proc 9513:com.thaliproject.thalitest/u0a33 for activity com.thaliproject.thalitest/.MainActivity
07-14 13:28:05.675  9513  9513 E Zygote  : v2
07-14 13:28:05.675  9513  9513 I libpersona: KNOX_SDCARD checking this for 10033
07-14 13:28:05.675  9513  9513 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:05.676  9513  9513 E Zygote  : accessInfo : 0
07-14 13:28:05.676  9513  9513 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
07-14 13:28:05.678  9513  9513 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
07-14 13:28:05.683  3707  3803 D WindowManager: finishDrawingWindow: Window{e29a66dd0 u0 Starting com.thaliproject.thalitest} mDrawState=DRAW_PENDING
07-14 13:28:05.684  9503  9503 D AndroidRuntime: Shutting down VM
07-14 13:28:05.702  9513  9513 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:05.702  3707  3803 V WindowManager: Now policy hidden: Window{e29a66dd0 u0 Starting com.thaliproject.thalitest}
07-14 13:28:05.702  9513  9513 D ActivityThread: Added TimaKeyStore provider
07-14 13:28:05.705  3707  4313 I ActivityManager: DSS on for com.thaliproject.thalitest and scale is 1.0
07-14 13:28:05.707  3707  4313 I WindowManager: Failed to capture screenshot of Token{ef4fde0 ActivityRecord{f0c6fe3d0 u0 com.samsung.android.MtpApplication/.USBConnection t4}} appWin=Window{3b39f10d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
07-14 13:28:05.711  9503  9503 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter
07-14 13:28:05.711  9503  9503 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter2
07-14 13:28:05.711  9503  9503 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - mSource2
07-14 13:28:05.711  9503  9503 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Exit
07-14 13:28:05.716  3707  4313 D GameManagerService: sem_perfomance_mode: 0
07-14 13:28:05.716  3707  3707 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-14 13:28:05.716  3707  3707 D GameManagerService: unexpected mPrevNotiType: -1
07-14 13:28:05.723  3707  3908 V WindowManager: Relayout Window{3b39f10d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=4 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
07-14 13:28:05.723  3707  4313 D ActivityTrigger: ActivityTrigger activityPauseTrigger 
07-14 13:28:05.724  3707  4313 D GameManagerService: sem_perfomance_mode: 0
07-14 13:28:05.728  3707  5610 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
07-14 13:28:05.728  3707  5610 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
07-14 13:28:05.729  4615  4626 D ForegroundUtils: could not check pending caller
07-14 13:28:05.730  4615  4626 D ForegroundUtils: could not check pending caller
07-14 13:28:05.730  4615  4626 D ForegroundUtils: could not check pending caller
07-14 13:28:05.731  3707  3803 D ViewRootImpl@d591c97[thalitest]: MSG_RESIZED: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-14 13:28:05.731  3707  3965 V WindowManager: Relayout Window{103c697d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=4 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
07-14 13:28:05.732  3707  3965 I WindowManager: Destroying surface Surface(name=com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowManagerService.tryStartExitingAnimation:3504 com.android.server.wm.WindowManagerService.relayoutWindow:3360 com.android.server.wm.Session.relayoutEx:244 android.view.IWindowSession$Stub.onTransact:407 com.android.server.wm.Session.onTransact:151 
07-14 13:28:05.732  3113  3283 I SurfaceFlinger: id=12 Removed MauncherAct (1/5)
07-14 13:28:05.733  3113  4411 I SurfaceFlinger: id=12 Removed MauncherAct (-2/5)
07-14 13:28:05.738  4818  4818 D Launcher: onTrimMemory. Level: 20
,07-14 13:28:05.740  3707  4716 V WindowManager: Relayout Window{9cb5ca4d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1015x1572 WM.LayoutParams{(0,0)(wrapxwrap) gr=#11 sim=#120 ty=2 fl=#1820002 fmt=-3 wanim=0x103038b surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
,07-14 13:28:05.744  3707  3803 V WindowManager: Relayout Window{e29a66dd0 u0 Starting com.thaliproject.thalitest}: viewVisibility=0 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,07-14 13:28:05.745  3707  5610 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-14 13:28:05.746  3707  4737 V WindowManager: Relayout Window{3b39f10d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
,07-14 13:28:05.748  3707  5610 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-14 13:28:05.753  3707  3803 D WindowManager: finishDrawingWindow: Window{e29a66dd0 u0 Starting com.thaliproject.thalitest} mDrawState=HAS_DRAWN
,07-14 13:28:05.755  3707  4717 V WindowManager: Relayout Window{103c697d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=8 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
,07-14 13:28:05.774  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:05.774  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-14 13:28:05.787  9513  9513 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:05.812  9513  9513 I CordovaLog: Changing log level to DEBUG(3)
07-14 13:28:05.812  9513  9513 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
07-14 13:28:05.812  9513  9513 D CordovaActivity: CordovaActivity.onCreate()
,07-14 13:28:05.824  9513  9513 W System  : ClassLoader referenced unknown path: /system/app/Chrome/lib/arm
,07-14 13:28:05.829  9513  9513 I WebViewFactory: Loading com.android.chrome version 56.0.2924.87 (code 292408752)
,07-14 13:28:05.856  3707  3990 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,07-14 13:28:05.885  9513  9513 I cr_LibraryLoader: Time to load native libraries: 15 ms (timestamps 6985-7000)
07-14 13:28:05.885  9513  9513 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-14 13:28:05.906  9513  9513 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-14 13:28:05.913  9513  9513 I chromium: [INFO:library_loader_hooks.cc(163)] Chromium logging enabled: level = 0, default verbosity = 0
,07-14 13:28:05.934  9513  9513 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-14 13:28:06.074  3707  3987 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10033
07-14 13:28:06.075  3707  3987 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:921 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:26544 com.android.server.am.ActivityManagerService.registerReceiver:21403 android.app.ActivityManagerNative.onTransact:466 com.android.server.am.ActivityManagerService.onTransact:3573 
,07-14 13:28:06.076  3707  3707 D KnoxVpnEngineService: Vpn Receiver : com.samsung.android.knox.intent.action.VPN_PROXY_BROADCAST_INTERNAL
,07-14 13:28:06.077  3707  3915 I KnoxVpnEngineService: vpn handle : Message received
,07-14 13:28:06.111  9513  9513 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 9513
,07-14 13:28:06.112  3707  4312 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/9513 for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-14 13:28:06.113  3707  3958 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-14 13:28:06.113  3707  3958 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-14 13:28:06.113  3707  3958 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-14 13:28:06.113  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-14 13:28:06.113  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.114  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.114  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [] ]
07-14 13:28:06.114  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.114  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.114  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.114  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.114  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.114  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:06.114  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:06.114  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-14 13:28:06.155  9513  9513 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-14 13:28:06.161  9513  9513 D PluginManager: init()
,07-14 13:28:06.165  9513  9513 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,07-14 13:28:06.184  9513  9513 I cr_Ime  : ImeThread is enabled.
,07-14 13:28:06.195  9513  9513 D CordovaActivity: Started the activity.
,07-14 13:28:06.197  9513  9513 D CordovaActivity: Resumed the activity.
,07-14 13:28:06.210  3707  4312 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@e60744e displayId=0
,07-14 13:28:06.210  3707  4312 D InputTransport: Input channel constructed: fd=455
07-14 13:28:06.210  3707  4312 D InputTransport: Input channel constructed: fd=457
07-14 13:28:06.211  3707  4312 D InputTransport: Input channel destroyed: fd=457
,07-14 13:28:06.212  9513  9513 D InputTransport: Input channel constructed: fd=98
07-14 13:28:06.212  9513  9513 D ViewRootImpl@b299a7e[MainActivity]: setView = DecorView@93d5bdf[MainActivity] touchMode=true
,07-14 13:28:06.212  3707  3922 D ActivityManager: post active user change for 0 fullscreen true isHomeActivity() false
07-14 13:28:06.213  3707  3922 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-14 13:28:06.213  3707  3707 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-14 13:28:06.213  9513  9513 D CordovaActivity: Paused the activity.
,07-14 13:28:06.214  3707  3707 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-14 13:28:06.217  3707  3783 D ActivityTrigger: ActivityTrigger activityStopTrigger 
,07-14 13:28:06.222  9513  9513 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 9513
,07-14 13:28:06.223  3707  4737 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/9513 for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-14 13:28:06.224  3707  3958 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-14 13:28:06.224  3707  3958 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-14 13:28:06.224  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.224  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.224  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-14 13:28:06.224  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.225  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.225  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:06.225  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:06.225  3707  3958 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-14 13:28:06.225  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-14 13:28:06.225  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.225  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:06.225  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [] ]
07-14 13:28:06.225  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:06.225  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-14 13:28:06.236  3707  4717 V WindowManager: Relayout Window{4beb67cd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#110 ty=1 fl=#81810900 pfl=0x20000 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,07-14 13:28:06.236  3113  3113 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,07-14 13:28:06.242  9513  9561 I OpenGLRenderer: Initialized EGL, version 1.4
07-14 13:28:06.242  9513  9561 D OpenGLRenderer: Swap behavior 1
,07-14 13:28:06.244  9513  9561 D libGLESv1: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,07-14 13:28:06.246  9513  9561 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1080x1920]-format:1
,07-14 13:28:06.247  9513  9513 D CordovaActivity: Stopped the activity.
,07-14 13:28:06.256  3707  3803 V WindowManager: Now policy hidden: Window{4beb67cd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}
,07-14 13:28:06.282  9513  9567 E libEGL  : validate_display:99 error 3008 (EGL_BAD_DISPLAY)
,07-14 13:28:06.299  3707  3922 D WindowManager: finishDrawingWindow: Window{4beb67cd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=DRAW_PENDING
,07-14 13:28:06.299  9513  9513 D ViewRootImpl@b299a7e[MainActivity]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,07-14 13:28:06.301  9513  9567 W AudioCapabilities: Unsupported mime audio/mpeg-L1
07-14 13:28:06.302  9513  9567 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-14 13:28:06.304  9513  9567 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-14 13:28:06.304  9513  9567 W AudioCapabilities: Unsupported mime audio/x-ima
,07-14 13:28:06.305  3707  3803 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
,07-14 13:28:06.305  3707  3707 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
,07-14 13:28:06.305  9513  9567 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-14 13:28:06.305  9513  9567 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-14 13:28:06.305  9513  9567 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-14 13:28:06.306  3707  3803 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +582ms (total +646ms)
07-14 13:28:06.306  3707  3707 I KnoxTimeoutHandler: SD activityfalse
07-14 13:28:06.306  3707  3707 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
07-14 13:28:06.307  3707  3783 D ActivityManager: mActivityResumeBoosterTail.acquire()
07-14 13:28:06.307  3707  4718 D WindowManager: finishDrawingWindow: Window{4beb67cd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=HAS_DRAWN
07-14 13:28:06.307  3707  3803 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3707  tag : AMS_RESUME@CPU_MIN@7
07-14 13:28:06.307  3707  3803 D ActivityManager: mActivityResumeBooster.release()
07-14 13:28:06.308  9513  9513 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
07-14 13:28:06.310  3707  3803 D ViewRootImpl@d591c97[thalitest]: dispatchDetachedFromWindow
07-14 13:28:06.310  3707  3783 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3707  pkgName : AMS_RESUME_TAIL@CPU_MIN@13
07-14 13:28:06.310  3707  3803 I WindowManager: Destroying surface Surface(name=Starting com.thaliproject.thalitest) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.removeLocked:1776 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:2876 com.android.server.wm.WindowManagerService.removeWindowLocked:2826 com.android.server.wm.WindowManagerService.removeWindowLocked:2641 com.android.server.wm.WindowManagerService.removeWindow:2636 com.android.server.wm.Session.remove:208 
07-14 13:28:06.311  3113  3283 I SurfaceFlinger: id=15 Removed uhalitest (3/5)
07-14 13:28:06.311  3113  3122 I SurfaceFlinger: id=15 Removed uhalitest (-2/5)
07-14 13:28:06.313  3707  3803 D InputTransport: Input channel destroyed: fd=453
07-14 13:28:06.313  3707  3803 D InputTransport: Input channel destroyed: fd=454
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.314  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.316  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-14 13:28:06.323  9513  9567 W VideoCapabilities: Unsupported mime video/wvc1
07-14 13:28:06.324  9513  9567 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-14 13:28:06.328  9513  9567 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-14 13:28:06.328  9513  9567 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-14 13:28:06.328  9513  9567 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-14 13:28:06.329  9513  9567 W VideoCapabilities: Unsupported mime video/wvc1
07-14 13:28:06.330  9513  9567 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-14 13:28:06.331  9513  9567 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
07-14 13:28:06.333  9513  9567 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
07-14 13:28:06.334  9513  9567 W VideoCapabilities: Unsupported mime video/mp43
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.337  9513  9567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-14 13:28:06.340  9513  9567 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-14 13:28:06.340  9513  9567 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-14 13:28:06.340  9513  9567 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-14 13:28:06.355  9513  9567 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-14 13:28:06.368  9513  9567 W VideoCapabilities: Unsupported mime video/sorenson
07-14 13:28:06.384  9513  9567 D libGLESv2: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,07-14 13:28:06.406  9513  9513 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9513
,07-14 13:28:06.547  9513  9513 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,07-14 13:28:06.560  9513  9513 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,07-14 13:28:06.599  9513  9574 D jxcore_app_log: JniHelper::setJavaVM(0xe65b4000), pthread_self() = -1077413600
,07-14 13:28:06.602  9513  9574 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-14 13:28:06.602  9513  9574 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-14 13:28:06.602  9513  9574 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-14 13:28:06.602  9513  9574 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-14 13:28:06.602  9513  9574 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-14 13:28:06.602  9513  9574 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eada9 added. We now have 1 listener(s)
,07-14 13:28:06.602  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89eada9 added. We now have 1 listener(s)
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-14 13:28:06.603  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-14 13:28:06.604  9513  9574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
07-14 13:28:06.605  9513  9574 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
07-14 13:28:06.605  9513  9574 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-14 13:28:06.605  9513  9574 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,07-14 13:28:06.607  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-14 13:28:06.607  9513  9574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2420c5c added. We now have 2 listener(s)
,07-14 13:28:06.607  9513  9574 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-14 13:28:06.610  9513  9574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-14 13:28:06.610  9513  9574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 64496
,07-14 13:28:06.611  3707  3707 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3707  tag : AMS_RESUME_TAIL@CPU_MIN@13
07-14 13:28:06.611  9513  9574 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 120
07-14 13:28:06.611  9513  9574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
07-14 13:28:06.611  9513  9574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
07-14 13:28:06.611  9513  9574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
07-14 13:28:06.611  9513  9574 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 120
,07-14 13:28:06.616  9513  9574 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-14 13:28:06.616  9513  9574 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,07-14 13:28:06.628  9513  9574 D BluetoothAdapter: STATE_ON
,07-14 13:28:06.631  9513  9574 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
07-14 13:28:06.631  9513  9574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-14 13:28:06.631  9513  9574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:06.631  9513  9574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:06.631  9513  9574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-14 13:28:06.631  9513  9574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-14 13:28:06.631  9513  9574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-14 13:28:06.631  9513  9574 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-14 13:28:06.631  9513  9574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-14 13:28:06.631  9513  9574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-14 13:28:06.631  9513  9574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-14 13:28:06.631  9513  9574 D io.jxcore.node.ConnectivityMonitor: start: OK
07-14 13:28:06.631  9513  9574 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-14 13:28:06.637  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:06.642  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:06.646  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:06.649  9513  9513 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
07-14 13:28:06.649  9513  9513 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,07-14 13:28:07.270  9513  9577 W jxcore-log: Initializing JXcore engine
07-14 13:28:07.270  9513  9577 W jxcore-log: JXcore engine is ready
,07-14 13:28:07.289  3239  3239 E audit   : type=1400 audit(1500031687.278:227): avc:  denied  { ioctl } for  pid=9577 comm="Thread-9" path="socket:[61823]" dev="sockfs" ino=61823 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0 SEPF_SECMOBILE_7.0_0005
07-14 13:28:07.290  3707  3799 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / /system/bin/sh /system/bin/install-recovery.sh
07-14 13:28:07.290  3239  3239 E audit   : type=1300 audit(1500031687.278:227): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3 a1=5451 a2=c5eb21e a3=22 items=0 ppid=3271 pid=9577 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-14 13:28:07.290  3707  3799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-14 13:28:07.292  3239  3239 E audit   : type=1327 audit(1500031687.278:227): proctitle="com.thaliproject.thalitest"
07-14 13:28:07.292  3239  3239 E audit   : type=1320 audit(1500031687.278:227): 
07-14 13:28:07.292  3239  3239 E audit   : type=1400 audit(1500031687.278:228): avc:  denied  { ioctl } for  pid=9577 comm="Thread-9" path="/dev/pmsg0" dev="tmpfs" ino=3718 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0 SEPF_SECMOBILE_7.0_0005
07-14 13:28:07.292  3239  3239 E audit   : type=1300 audit(1500031687.278:228): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=4 a1=5451 a2=c5eb21e a3=22 items=0 ppid=3271 pid=9577 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
,07-14 13:28:07.296  9513  9577 W jxcore-log: Starting JXcore engine
,07-14 13:28:07.297  3239  3239 E audit   : type=1327 audit(1500031687.278:228): proctitle="com.thaliproject.thalitest"
07-14 13:28:07.297  3239  3239 E audit   : type=1320 audit(1500031687.278:228): 
,07-14 13:28:07.297  9396  9396 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
07-14 13:28:07.298  3239  3239 E audit   : type=1400 audit(1500031687.278:229): avc:  denied  { ioctl } for  pid=9577 comm="Thread-9" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4245 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs_trace_marker:s0 tclass=file permissive=0 SEPF_SECMOBILE_7.0_0005
07-14 13:28:07.298  3239  3239 E audit   : type=1300 audit(1500031687.278:229): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=5 a1=5451 a2=c5eb21e a3=22 items=0 ppid=3271 pid=9577 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-14 13:28:07.300  3239  3239 E audit   : type=1327 audit(1500031687.278:229): proctitle="com.thaliproject.thalitest"
07-14 13:28:07.300  3239  3239 E audit   : type=1320 audit(1500031687.278:229): 
07-14 13:28:07.300  3707  3799 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
07-14 13:28:07.300  3239  3239 E audit   : type=1400 audit(1500031687.278:230): avc:  denied  { ioctl } for  pid=9577 comm="Thread-9" path="socket:[60904]" dev="sockfs" ino=60904 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0 SEPF_SECMOBILE_7.0_0005
07-14 13:28:07.300  3707  3799 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / "com.thaliproject.thalitest"
07-14 13:28:07.300  3239  3239 E audit   : type=1300 audit(1500031687.278:230): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=54 a1=5451 a2=c5eb21e a3=22 items=0 ppid=3271 pid=9577 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-14 13:28:07.301  3707  3799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-14 13:28:07.302  3239  3239 E audit   : type=1327 audit(1500031687.278:230): proctitle="com.thaliproject.thalitest"
07-14 13:28:07.302  3239  3239 E audit   : type=1320 audit(1500031687.278:230): 
,07-14 13:28:07.310  9396  9396 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-14 13:28:07.311  3707  3799 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-14 13:28:07.334  9513  9577 W jxcore-log: Platform android
07-14 13:28:07.334  9513  9577 W jxcore-log: 
07-14 13:28:07.334  9513  9577 W jxcore-log: Process ARCH arm
07-14 13:28:07.334  9513  9577 W jxcore-log: 
,07-14 13:28:07.467  9513  9577 I jxcore-log: JXcore Cordova bridge is ready!
07-14 13:28:07.467  9513  9577 I jxcore-log: 
07-14 13:28:07.467  9513  9577 W jxcore-log: JXcore engine is started
,07-14 13:28:07.472  9513  9574 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-14 13:28:07.476  9513  9513 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
07-14 13:28:07.477  9513  9513 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-14 13:28:08.792  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:08.793  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-14 13:28:10.267  4497  4497 D io_stats: !@   8,0 r 25021 2254564 w 4381 195192 d 544 72576 f 1795 1795 iot 10720 10307 th 468124 0 0 pt 0 inp 0 0 171.382
,07-14 13:28:10.311  3707  5610 D SSRM:f  : SIOP:: AP = 320, PST = 274 (W:6), CP = 228, CUR = 18, LCD = 57
,07-14 13:28:11.731  3707  5610 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-14 13:28:11.820  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:11.820  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-14 13:28:14.493  9513  9577 I jxcore-log: 2017-07-14 11:28:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
07-14 13:28:14.493  9513  9577 I jxcore-log: 
,07-14 13:28:14.495  9513  9577 I jxcore-log: 2017-07-14 11:28:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
07-14 13:28:14.495  9513  9577 I jxcore-log: 
07-14 13:28:14.495  9513  9577 I jxcore-log: 2017-07-14 11:28:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
07-14 13:28:14.495  9513  9577 I jxcore-log: 
,07-14 13:28:14.505  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:14.509  9513  9577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-14 13:28:14.509  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:14.509  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:14.509  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-14 13:28:14.509  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-14 13:28:14.509  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-14 13:28:14.509  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-14 13:28:14.509  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-14 13:28:14.509  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-14 13:28:14.513  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:14.517  9513  9577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-14 13:28:14.518  9513  9577 I jxcore-log: 2017-07-14 11:28:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
07-14 13:28:14.518  9513  9577 I jxcore-log: 
07-14 13:28:14.519  9513  9577 I jxcore-log: 2017-07-14 11:28:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
07-14 13:28:14.519  9513  9577 I jxcore-log: 
,07-14 13:28:14.519  9513  9577 I jxcore-log: 2017-07-14 11:28:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
07-14 13:28:14.519  9513  9577 I jxcore-log: 
,07-14 13:28:14.784  9513  9577 D ExecuteNativeTests: Running unit tests
07-14 13:28:14.784  9513  9577 D BluetoothAdapter: enable()
,07-14 13:28:14.791  4056  4483 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-14 13:28:14.792  4056  4483 D AdapterProvider: query
,07-14 13:28:14.808  4056  4483 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@7fd14b5
,07-14 13:28:14.810  4056  4483 D BluetoothAdapterService: updateEvent - already set, update
,07-14 13:28:14.811  4056  4483 W BluetoothAdapterService: updateEvent - alreadySet is true
07-14 13:28:14.812  4056  4483 D AdapterProvider: update
,07-14 13:28:14.822  4056  4483 E BluetoothAdapterService: updateEvent - update success 1
,07-14 13:28:14.829  9513  9577 D BluetoothAdapter: enable(): BT is already enabled..!
,07-14 13:28:14.837  3707  3908 D WifiService: setWifiEnabled: true pid=9513, uid=10033
07-14 13:28:14.838  3707  3908 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-14 13:28:14.839  3707  3908 D WifiControlHistoryProvider: query
,07-14 13:28:14.841  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:14.841  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-14 13:28:14.866  3707  3908 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-14 13:28:14.871  3707  3908 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:14.872  3707  3908 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-14 13:28:14.877  3707  3908 I WifiService: Wi-Fi Sharing settings has not been accessed
07-14 13:28:14.877  3707  3908 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-14 13:28:14.975  3707  4718 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-14 13:28:14.977  3707  4718 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4300, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-14 13:28:14.977  3707  4718 D BatteryService: online:4, current avg:-78, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:228
07-14 13:28:14.977  3707  3707 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-14 13:28:14.988  3707  3707 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-14 13:28:14.988  3707  3707 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-14 13:28:14.991  3707  3707 D GameManagerService: new battery level: 100
,07-14 13:28:14.997  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-14 13:28:14.998  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-14 13:28:15.009  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-14 13:28:15.013  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,07-14 13:28:15.013  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,07-14 13:28:15.017  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
07-14 13:28:15.018  4056  4056 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-14 13:28:15.018  4056  4485 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-14 13:28:15.273  4497  4497 D io_stats: !@   8,0 r 25028 2254628 w 4433 195580 d 544 72576 f 1799 1799 iot 10730 10317 th 471892 0 0 pt 0 inp 0 0 176.387
,07-14 13:28:15.715  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-14 13:28:15.740  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-14 13:28:15.740  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-14 13:28:16.085  3295  3770 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-14 13:28:17.877  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:17.877  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-14 13:28:20.278  4497  4497 D io_stats: !@   8,0 r 25028 2254628 w 4436 195708 d 544 72576 f 1800 1800 iot 10730 10320 th 471828 0 0 pt 0 inp 0 0 181.392
,07-14 13:28:20.332  3707  5610 D SSRM:f  : SIOP:: AP = 310, PST = 278 (W:6), CP = 239, CUR = 27, LCD = 57
,07-14 13:28:20.906  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:20.906  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-14 13:28:21.091  3295  3770 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-14 13:28:21.779  3707  4017 D WifiWatchdogStateMachine:  [|210]
,07-14 13:28:23.938  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:23.939  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-14 13:28:24.883  9513  9577 I com.test.thalitest.ThaliTestRunner: Running UT
,07-14 13:28:25.006  9513  9577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-14 13:28:25.006  9513  9577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@150b940 added. We now have 2 listener(s)
07-14 13:28:25.006  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@150b940 added. We now have 3 listener(s)
07-14 13:28:25.006  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-14 13:28:25.007  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
,07-14 13:28:25.007  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-14 13:28:25.007  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
07-14 13:28:25.007  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-14 13:28:25.008  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f509079 added. We now have 4 listener(s)
07-14 13:28:25.008  9513  9577 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-14 13:28:25.009  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-14 13:28:25.017  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.020  3707  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-14 13:28:25.021  3707  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
,07-14 13:28:25.021  3707  4737 D BatteryService: online:4, current avg:78, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:184
07-14 13:28:25.021  3707  3707 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-14 13:28:25.024  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,07-14 13:28:25.025  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-14 13:28:25.025  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-14 13:28:25.025  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-14 13:28:25.025  9513  9577 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
07-14 13:28:25.026  9513  9577 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-14 13:28:25.026  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-14 13:28:25.026  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-14 13:28:25.026  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-14 13:28:25.027  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,07-14 13:28:25.028  9513  9577 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-14 13:28:25.030  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,07-14 13:28:25.031  3707  3707 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-14 13:28:25.031  3707  3707 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
07-14 13:28:25.032  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
07-14 13:28:25.032  9513  9577 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-14 13:28:25.033  3707  3707 D GameManagerService: new battery level: 100
07-14 13:28:25.037  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-14 13:28:25.037  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-14 13:28:25.043  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-14 13:28:25.047  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
07-14 13:28:25.048  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,07-14 13:28:25.053  4056  4056 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-14 13:28:25.053  4056  4485 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-14 13:28:25.061  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-14 13:28:25.069  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-14 13:28:25.071  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.076  9513  9577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-14 13:28:25.076  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:25.076  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:25.076  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-14 13:28:25.076  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-14 13:28:25.076  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-14 13:28:25.076  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-14 13:28:25.076  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-14 13:28:25.076  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-14 13:28:25.076  9513  9577 D io.jxcore.node.ConnectivityMonitor: start: OK
07-14 13:28:25.077  9513  9577 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
07-14 13:28:25.077  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
07-14 13:28:25.077  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-14 13:28:25.082  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
,07-14 13:28:25.083  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:25.083  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:25.083  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.083  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-14 13:28:25.087  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:25.087  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
,07-14 13:28:25.088  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.088  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-14 13:28:25.088  9513  9577 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,07-14 13:28:25.088  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-14 13:28:25.088  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:25.089  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-14 13:28:25.091  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-14 13:28:25.092  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-14 13:28:25.092  9513  9584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-14 13:28:25.092  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-14 13:28:25.093  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-14 13:28:25.093  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-14 13:28:25.093  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-14 13:28:25.093  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-14 13:28:25.093  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-14 13:28:25.094  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:25.094  9513  9513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-14 13:28:25.100  9513  9584 D BluetoothSocket: bindListen(): myUserId = 0
07-14 13:28:25.100  9513  9584 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-14 13:28:25.104  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-14 13:28:25.104  9513  9577 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-14 13:28:25.104  9513  9584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-14 13:28:25.105  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-14 13:28:25.108  9513  9584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@340bb35, port: 6, type: 1, local socket address: null, socket type: 0
,07-14 13:28:25.109  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.110  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.111  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.113  9513  9577 D BluetoothAdapter: isSecureModeEnabled
,07-14 13:28:25.114  4056  4654 D BtConfig.SecureMode: isSecureModeOn:false
,07-14 13:28:25.115  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.115  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-14 13:28:25.118  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.119  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.120  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-14 13:28:25.120  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-14 13:28:25.120  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,07-14 13:28:25.123  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.126  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.127  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.127  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-14 13:28:25.127  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-14 13:28:25.127  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "9efc9363-3d2b-4b01-abd9-143186647519", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-14 13:28:25.128  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 4A 3E
,07-14 13:28:25.129  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-14 13:28:25.130  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-14 13:28:25.130  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.131  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.131  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-14 13:28:25.131  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-14 13:28:25.132  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.132  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.133  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.134  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:25.136  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:25.136  9513  9577 D BluetoothAdapter: isSecureModeEnabled
07-14 13:28:25.136  4056  4067 D BtConfig.SecureMode: isSecureModeOn:false
07-14 13:28:25.137  9513  9577 D BluetoothLeAdvertiser: start advertising
07-14 13:28:25.138  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.146  4056  4483 D BtGatt.GattService: registerClient() - UUID=f29490f7-1fa5-4873-96c2-a8d7f2f2f704
,07-14 13:28:25.250  4056  4178 D BtGatt.GattService: onClientRegistered() - UUID=f29490f7-1fa5-4873-96c2-a8d7f2f2f704, clientIf=5, status=0
,07-14 13:28:25.252  9513  9524 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-14 13:28:25.257  4056  4067 E BtGatt.ContextMap: Context not found for ID 5
,07-14 13:28:25.258  4056  4401 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-14 13:28:25.259  4056  4377 D BtGatt.AdvertiseManager: message : 0
,07-14 13:28:25.265  4056  4377 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-14 13:28:25.265  4056  4377 D BtGatt.AdvertiseManager: size of list is =0
,07-14 13:28:25.274  4056  4377 D BtGatt.AdvertiseManager: starting advertising
,07-14 13:28:25.279  4056  4377 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-14 13:28:25.283  4497  4497 D io_stats: !@   8,0 r 25033 2254964 w 4462 196048 d 548 72660 f 1807 1807 iot 10730 10335 th 473496 0 0 pt 0 inp 0 0 186.397
,07-14 13:28:25.283  4056  4469 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-14 13:28:25.303  4056  4178 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-14 13:28:25.307  4056  4377 D BtGatt.AdvertiseManager: starting multi advertising
,07-14 13:28:25.319  4056  4178 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-14 13:28:25.320  4056  4377 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-14 13:28:25.320  4056  4377 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-14 13:28:25.321  4056  4377 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
,07-14 13:28:25.322  4056  4377 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-14 13:28:25.323  9513  9525 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-14 13:28:25.326  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.328  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.328  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-14 13:28:25.330  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.332  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.333  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.334  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.336  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.336  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-14 13:28:25.341  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-14 13:28:25.342  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.348  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.349  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.350  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.351  9513  9577 I io.jxcore.node.ConnectionHelper: start: OK
,07-14 13:28:25.351  9513  9513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-14 13:28:25.353  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-14 13:28:25.354  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-14 13:28:25.354  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-14 13:28:25.355  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,07-14 13:28:25.356  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-14 13:28:25.357  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-14 13:28:25.358  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,07-14 13:28:25.359  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-14 13:28:25.359  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,07-14 13:28:25.360  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-14 13:28:25.360  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-14 13:28:25.362  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-14 13:28:25.363  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-14 13:28:25.364  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-14 13:28:25.369  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-14 13:28:25.369  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-14 13:28:25.370  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,07-14 13:28:25.371  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-14 13:28:25.371  9513  9513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-14 13:28:25.855  9513  9586 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-14 13:28:25.857  9513  9577 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-14 13:28:25.858  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,07-14 13:28:25.858  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
07-14 13:28:25.858  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
07-14 13:28:25.859  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
07-14 13:28:25.859  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
07-14 13:28:25.859  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
,07-14 13:28:25.860  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
07-14 13:28:25.860  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
,07-14 13:28:25.860  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
07-14 13:28:25.860  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
,07-14 13:28:25.860  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
,07-14 13:28:25.861  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
,07-14 13:28:25.861  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
,07-14 13:28:25.861  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
07-14 13:28:25.864  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
,07-14 13:28:25.864  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
07-14 13:28:25.864  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
07-14 13:28:25.865  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
07-14 13:28:25.865  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
,07-14 13:28:25.865  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
07-14 13:28:25.865  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
07-14 13:28:25.867  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
07-14 13:28:25.867  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
07-14 13:28:25.867  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
07-14 13:28:25.867  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
07-14 13:28:25.867  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
07-14 13:28:25.867  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
07-14 13:28:25.868  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
07-14 13:28:25.868  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
07-14 13:28:25.868  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
07-14 13:28:25.868  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
07-14 13:28:25.869  9513  9577 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-14 13:28:25.869  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
07-14 13:28:25.870  9513  9577 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-14 13:28:25.870  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-14 13:28:25.870  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-14 13:28:25.870  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-14 13:28:25.871  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-14 13:28:25.871  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-14 13:28:25.871  9513  9584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-14 13:28:25.872  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-14 13:28:25.872  9513  9584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-14 13:28:25.872  9513  9584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-14 13:28:25.872  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-14 13:28:25.872  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-14 13:28:25.873  9513  9513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-14 13:28:25.873  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.874  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-14 13:28:25.874  9513  9577 D org.thaliproject.,p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-14 13:28:25.876  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.877  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.878  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.881  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.884  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:25.886  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.887  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-14 13:28:25.889  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.891  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.891  9513  9577 D BluetoothLeScanner: could not find callback wrapper
07-14 13:28:25.891  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-14 13:28:25.892  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.893  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.894  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.895  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-14 13:28:25.895  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.898  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.900  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:25.900  9513  9577 D BluetoothLeAdvertiser: stop advertising
,07-14 13:28:25.902  4056  4483 E BtGatt.ContextMap: Context not found for ID 5
07-14 13:28:25.902  4056  4401 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-14 13:28:25.902  4056  4377 D BtGatt.AdvertiseManager: message : 1
,07-14 13:28:25.903  4056  4377 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-14 13:28:25.904  4056  4377 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-14 13:28:25.906  4056  4377 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-14 13:28:25.912  4056  4178 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-14 13:28:25.912  4056  4178 D BtGatt.GattService: Client app is not null!
,07-14 13:28:25.913  9513  9524 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
07-14 13:28:25.914  4056  4067 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-14 13:28:25.915  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-14 13:28:25.916  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.916  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-14 13:28:25.917  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.917  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.917  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.918  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-14 13:28:25.918  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-14 13:28:25.919  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-14 13:28:25.919  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.922  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.922  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-14 13:28:25.923  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.923  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.924  9513  9513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-14 13:28:25.924  9513  9513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
07-14 13:28:25.925  9513  9513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-14 13:28:25.925  9513  9513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-14 13:28:25.926  9513  9513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-14 13:28:25.926  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-14 13:28:25.926  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-14 13:28:25.926  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,07-14 13:28:25.930  9513  9587 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,07-14 13:28:25.930  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:28:25.930  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-14 13:28:25.930  9513  9577 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-14 13:28:25.930  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-14 13:28:25.930  9513  9577 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-14 13:28:25.930  9513  9577 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
07-14 13:28:25.930  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
07-14 13:28:25.931  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-14 13:28:25.931  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-14 13:28:25.931  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-14 13:28:25.932  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-14 13:28:25.932  9513  9513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-14 13:28:25.935  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:25.936  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
,07-14 13:28:25.936  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.936  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-14 13:28:25.939  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:25.939  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:25.940  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.940  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-14 13:28:25.940  9513  9577 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,07-14 13:28:25.941  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,07-14 13:28:25.941  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-14 13:28:25.943  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-14 13:28:25.944  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-14 13:28:25.944  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-14 13:28:25.945  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-14 13:28:25.945  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-14 13:28:25.945  9513  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-14 13:28:25.945  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-14 13:28:25.945  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-14 13:28:25.945  9513  9513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-14 13:28:25.945  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-14 13:28:25.948  9513  9588 D BluetoothSocket: bindListen(): myUserId = 0
,07-14 13:28:25.948  9513  9588 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-14 13:28:25.953  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-14 13:28:25.953  9513  9577 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-14 13:28:25.954  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-14 13:28:25.954  9513  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,07-14 13:28:25.955  9513  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@c131a96, port: 6, type: 1, local socket address: null, socket type: 0
,07-14 13:28:25.958  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.959  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.960  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.963  9513  9577 D BluetoothAdapter: isSecureModeEnabled
,07-14 13:28:25.963  4056  4067 D BtConfig.SecureMode: isSecureModeOn:false
,07-14 13:28:25.964  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.964  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-14 13:28:25.966  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.967  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.967  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-14 13:28:25.968  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-14 13:28:25.968  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
,07-14 13:28:25.970  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.973  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.974  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.974  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-14 13:28:25.974  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-14 13:28:25.974  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "9efc9363-3d2b-4b01-abd9-143186647519", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-14 13:28:25.975  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 4A 3E
07-14 13:28:25.975  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-14 13:28:25.976  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-14 13:28:25.976  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.977  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:25.977  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-14 13:28:25.978  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-14 13:28:25.978  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.979  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.980  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:25.981  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.982  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:25.983  9513  9577 D BluetoothAdapter: isSecureModeEnabled
,07-14 13:28:25.983  4056  4482 D BtConfig.SecureMode: isSecureModeOn:false
,07-14 13:28:25.983  9513  9577 D BluetoothLeAdvertiser: start advertising
,07-14 13:28:25.985  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:25.991  4056  4483 D BtGatt.GattService: registerClient() - UUID=959536e8-99c1-44ef-b7e8-ad0f03988348
,07-14 13:28:26.093  4056  4178 D BtGatt.GattService: onClientRegistered() - UUID=959536e8-99c1-44ef-b7e8-ad0f03988348, clientIf=5, status=0
,07-14 13:28:26.094  9513  9525 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-14 13:28:26.096  4056  4482 E BtGatt.ContextMap: Context not found for ID 5
,07-14 13:28:26.097  4056  4401 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-14 13:28:26.097  4056  4377 D BtGatt.AdvertiseManager: message : 0
07-14 13:28:26.098  4056  4377 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-14 13:28:26.098  4056  4377 D BtGatt.AdvertiseManager: size of list is =0
,07-14 13:28:26.103  4056  4377 D BtGatt.AdvertiseManager: starting advertising
,07-14 13:28:26.105  4056  4377 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-14 13:28:26.108  4056  4469 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-14 13:28:26.119  4056  4178 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-14 13:28:26.121  4056  4377 D BtGatt.AdvertiseManager: starting multi advertising
,07-14 13:28:26.128  4056  4178 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-14 13:28:26.128  4056  4377 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-14 13:28:26.128  4056  4377 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-14 13:28:26.128  4056  4377 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-14 13:28:26.128  4056  4377 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-14 13:28:26.129  9513  9524 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-14 13:28:26.130  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.131  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.131  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-14 13:28:26.131  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.132  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.133  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.133  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.134  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.134  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-14 13:28:26.137  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-14 13:28:26.137  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.137  9513  9577 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,07-14 13:28:26.140  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.141  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.141  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.141  9513  9577 I io.jxcore.node.ConnectionHelper: start: OK
07-14 13:28:26.143  9513  9513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-14 13:28:26.145  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-14 13:28:26.146  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-14 13:28:26.146  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-14 13:28:26.146  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,07-14 13:28:26.147  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-14 13:28:26.148  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-14 13:28:26.148  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:28:26.149  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-14 13:28:26.149  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,07-14 13:28:26.149  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-14 13:28:26.150  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-14 13:28:26.151  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-14 13:28:26.152  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-14 13:28:26.152  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-14 13:28:26.158  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,07-14 13:28:26.158  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
07-14 13:28:26.159  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-14 13:28:26.159  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,07-14 13:28:26.160  9513  9513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-14 13:28:26.644  9513  9590 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-14 13:28:26.649  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
07-14 13:28:26.650  9513  9577 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-14 13:28:26.650  9513  9577 V io.jxcore.node.ConnectivityMonitor: start: Already started
,07-14 13:28:26.650  9513  9577 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-14 13:28:26.651  9513  9577 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
07-14 13:28:26.651  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,07-14 13:28:26.652  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-14 13:28:26.659  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,07-14 13:28:26.660  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:26.660  9513  9513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-14 13:28:26.661  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.661  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-14 13:28:26.668  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:26.669  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:26.670  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.671  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
07-14 13:28:26.671  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 64496
07-14 13:28:26.671  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
07-14 13:28:26.671  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
07-14 13:28:26.671  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
07-14 13:28:26.671  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
07-14 13:28:26.671  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
07-14 13:28:26.671  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
07-14 13:28:26.671  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
07-14 13:28:26.671  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.671  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
,07-14 13:28:26.672  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.673  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.674  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.678  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:26.680  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:26.680  9513  9577 D BluetoothLeAdvertiser: stop advertising
,07-14 13:28:26.682  4056  4482 E BtGatt.ContextMap: Context not found for ID 5
,07-14 13:28:26.683  4056  4401 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-14 13:28:26.683  4056  4377 D BtGatt.AdvertiseManager: message : 1
07-14 13:28:26.684  4056  4377 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-14 13:28:26.684  4056  4377 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-14 13:28:26.686  4056  4377 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-14 13:28:26.692  4056  4178 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-14 13:28:26.692  4056  4178 D BtGatt.GattService: Client app is not null!
,07-14 13:28:26.693  9513  9525 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-14 13:28:26.695  4056  4067 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-14 13:28:26.696  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-14 13:28:26.697  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.697  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-14 13:28:26.698  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.699  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.700  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.700  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-14 13:28:26.700  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.701  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.702  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.702  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-14 13:28:26.702  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-14 13:28:26.702  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "9efc9363-3d2b-4b01-abd9-143186647519", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-14 13:28:26.703  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 4A 3E
07-14 13:28:26.703  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-14 13:28:26.704  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-14 13:28:26.705  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.705  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.706  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,07-14 13:28:26.706  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-14 13:28:26.707  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.707  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.708  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.711  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:26.713  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:26.713  9513  9577 D BluetoothAdapter: isSecureModeEnabled
,07-14 13:28:26.713  4056  4483 D BtConfig.SecureMode: isSecureModeOn:false
07-14 13:28:26.714  9513  9577 D BluetoothLeAdvertiser: start advertising
,07-14 13:28:26.716  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:26.722  4056  4068 D BtGatt.GattService: registerClient() - UUID=e4c86060-8b1b-479f-87f4-8405aeb9eac5
,07-14 13:28:26.825  4056  4178 D BtGatt.GattService: onClientRegistered() - UUID=e4c86060-8b1b-479f-87f4-8405aeb9eac5, clientIf=5, status=0
,07-14 13:28:26.826  9513  9524 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-14 13:28:26.831  4056  4483 E BtGatt.ContextMap: Context not found for ID 5
,07-14 13:28:26.832  4056  4401 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-14 13:28:26.833  4056  4377 D BtGatt.AdvertiseManager: message : 0
,07-14 13:28:26.835  4056  4377 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-14 13:28:26.835  4056  4377 D BtGatt.AdvertiseManager: size of list is =0
,07-14 13:28:26.845  4056  4377 D BtGatt.AdvertiseManager: starting advertising
,07-14 13:28:26.849  4056  4377 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-14 13:28:26.853  4056  4469 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-14 13:28:26.882  4056  4178 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-14 13:28:26.887  4056  4377 D BtGatt.AdvertiseManager: starting multi advertising
,07-14 13:28:26.898  4056  4178 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-14 13:28:26.898  4056  4377 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-14 13:28:26.899  4056  4377 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-14 13:28:26.899  4056  4377 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-14 13:28:26.899  4056  4377 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
07-14 13:28:26.900  9513  9525 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-14 13:28:26.901  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.903  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.903  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-14 13:28:26.904  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.905  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.907  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.908  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.909  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:26.910  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.910  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-14 13:28:26.912  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.912  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-14 13:28:26.913  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-14 13:28:26.913  9513  9577 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-14 13:28:26.913  9513  9577 I io.jxcore.node.ConnectionHelper: start: OK
,07-14 13:28:26.915  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-14 13:28:26.916  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-14 13:28:26.916  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-14 13:28:26.917  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-14 13:28:26.917  9513  9592 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
07-14 13:28:26.918  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-14 13:28:26.918  9513  9577 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-14 13:28:26.918  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
07-14 13:28:26.919  9513  9577 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-14 13:28:26.919  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-14 13:28:26.919  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-14 13:28:26.919  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-14 13:28:26.919  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-14 13:28:26.920  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:28:26.920  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-14 13:28:26.920  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-14 13:28:26.920  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-14 13:28:26.920  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-14 13:28:26.920  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-14 13:28:26.920  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-14 13:28:26.920  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-14 13:28:26.920  9513  9588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-14 13:28:26.920  9513  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-14 13:28:26.921  9513  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-14 13:28:26.921  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-14 13:28:26.921  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.921  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-14 13:28:26.921  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-14 13:28:26.921  9513  9513 D org.thaliproject.p2p.btconnectorlib.i,nternal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-14 13:28:26.922  9513  9513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-14 13:28:26.922  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.923  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.924  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.926  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.929  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:26.930  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:26.930  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
07-14 13:28:26.932  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:26.934  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:26.934  9513  9577 D BluetoothLeScanner: could not find callback wrapper
07-14 13:28:26.934  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-14 13:28:26.935  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.935  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.936  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.936  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-14 13:28:26.937  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.938  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:26.943  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:26.944  9513  9577 D BluetoothLeAdvertiser: stop advertising
07-14 13:28:26.945  4056  4067 E BtGatt.ContextMap: Context not found for ID 5
07-14 13:28:26.946  4056  4401 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-14 13:28:26.947  4056  4377 D BtGatt.AdvertiseManager: message : 1
07-14 13:28:26.948  4056  4377 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-14 13:28:26.948  4056  4377 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
07-14 13:28:26.951  4056  4377 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
07-14 13:28:26.960  4056  4178 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-14 13:28:26.960  4056  4178 D BtGatt.GattService: Client app is not null!
07-14 13:28:26.961  9513  9524 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-14 13:28:26.962  4056  4654 D BtGatt.GattService: unregisterClient() - clientIf=5
07-14 13:28:26.963  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:26.963  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
07-14 13:28:26.964  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-14 13:28:26.965  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.966  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-14 13:28:26.966  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.967  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.967  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.967  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-14 13:28:26.968  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-14 13:28:26.969  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-14 13:28:26.969  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.972  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.972  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-14 13:28:26.973  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.973  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:26.974  9513  9513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-14 13:28:26.974  9513  9513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
07-14 13:28:26.974  9513  9513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-14 13:28:26.974  9513  9513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-14 13:28:26.975  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-14 13:28:26.975  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-14 13:28:26.975  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-14 13:28:26.975  9513  9593 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
07-14 13:28:26.976  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:28:26.976  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-14 13:28:26.976  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-14 13:28:26.976  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-14 13:28:26.977  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-14 13:28:26.977  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-14 13:28:26.978  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
07-14 13:28:26.978  9513  9513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-14 13:28:26.978  9513  9577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-14 13:28:26.979  9513  9577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8081cb3 added. We now have 3 listener(s)
07-14 13:28:26.979  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8081cb3 added. We now have 5 listener(s)
07-14 13:28:26.979  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-14 13:28:26.982  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:26.982  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-14 13:28:26.982  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:26.983  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-14 13:28:26.983  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a4f270 added. We now have 6 listener(s)
07-14 13:28:26.983  9513  9577 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-14 13:28:26.984  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-14 13:28:26.989  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-14 13:28:26.997  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:27.000  9513  9577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-14 13:28:27.000  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:27.000  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:27.000  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-14 13:28:27.000  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-14 13:28:27.000  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-14 13:28:27.000  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-14 13:28:27.000  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-14 13:28:27.000  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-14 13:28:27.000  9513  9577 D io.jxcore.node.ConnectivityMonitor: start: OK
07-14 13:28:27.006  9513  9577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:27.012  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:27.016  9513  9577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-14 13:28:27.016  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:27.016  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:27.016  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-14 13:28:27.016  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-14 13:28:27.016  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-14 13:28:27.016  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-14 13:28:27.016  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-14 13:28:27.016  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-14 13:28:27.016  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-14 13:28:27.016  9513  9577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-14 13:28:27.016  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-14 13:28:27.016  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-14 13:28:27.016  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-14 13:28:27.017  9513  9577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8081cb3 removed from the list
07-14 13:28:27.017  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8081cb3 removed from the list
07-14 13:28:27.017  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-14 13:28:27.017  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a4f270 removed from the list
,07-14 13:28:27.021  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:27.021  9513  9577 D io.jxcore.node.ConnectivityMonitor: stop
07-14 13:28:27.021  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-14 13:28:27.024  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,07-14 13:28:27.024  9513  9577 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,07-14 13:28:27.028  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
07-14 13:28:27.029  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:27.029  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,07-14 13:28:27.032  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
07-14 13:28:27.032  9513  9577 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,07-14 13:28:27.034  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
,07-14 13:28:27.035  9513  9577 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,07-14 13:28:27.037  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
07-14 13:28:27.037  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-14 13:28:27.038  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-14 13:28:27.038  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-14 13:28:27.038  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-14 13:28:27.038  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-14 13:28:27.039  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-14 13:28:27.039  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-14 13:28:27.039  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-14 13:28:27.039  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-14 13:28:27.041  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
,07-14 13:28:27.042  9513  9577 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-14 13:28:27.042  9513  9577 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-14 13:28:27.043  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,07-14 13:28:27.047  9513  9577 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-14 13:28:27.048  9513  9577 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-14 13:28:27.048  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
,07-14 13:28:27.048  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
07-14 13:28:27.049  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
07-14 13:28:27.049  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
07-14 13:28:27.049  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
07-14 13:28:27.049  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
07-14 13:28:27.049  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
,07-14 13:28:27.049  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
07-14 13:28:27.049  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
07-14 13:28:27.049  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
07-14 13:28:27.049  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
07-14 13:28:27.049  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
07-14 13:28:27.049  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
07-14 13:28:27.049  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
07-14 13:28:27.050  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
07-14 13:28:27.051  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
07-14 13:28:27.051  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
07-14 13:28:27.051  9513  9577 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-14 13:28:27.051  9513  9577 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-14 13:28:27.051  9513  9577 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-14 13:28:27.051  9513  9577 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-14 13:28:27.052  9513  9577 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-14 13:28:27.052  9513  9577 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-14 13:28:27.052  9513  9577 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
0,7-14 13:28:27.052  9513  9577 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-14 13:28:27.052  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
,07-14 13:28:27.059  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,07-14 13:28:27.060  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
07-14 13:28:27.060  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,07-14 13:28:27.061  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,07-14 13:28:27.061  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-14 13:28:27.061  9513  9594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 195)
07-14 13:28:27.061  9513  9577 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-14 13:28:27.062  9513  9577 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-14 13:28:27.062  9513  9594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
07-14 13:28:27.062  9513  9577 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-14 13:28:27.062  9513  9594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
07-14 13:28:27.062  9513  9594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
,07-14 13:28:27.064  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
07-14 13:28:27.065  9513  9577 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,07-14 13:28:27.067  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
07-14 13:28:27.067  9513  9577 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,07-14 13:28:27.069  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,07-14 13:28:27.070  9513  9577 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-14 13:28:27.070  9513  9577 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-14 13:28:27.070  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-14 13:28:27.070  9513  9577 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-14 13:28:27.070  9513  9577 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,07-14 13:28:27.071  9513  9577 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-14 13:28:27.071  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-14 13:28:27.071  9513  9577 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-14 13:28:27.071  9513  9577 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-14 13:28:27.071  9513  9577 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-14 13:28:27.071  9513  9594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
07-14 13:28:27.071  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-14 13:28:27.071  9513  9594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
07-14 13:28:27.072  9513  9577 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,07-14 13:28:27.073  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
,07-14 13:28:27.073  9513  9577 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-14 13:28:27.074  9513  9577 V io.jxcore.node.ConnectivityMonitor: start: Already started
,07-14 13:28:27.074  9513  9577 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
07-14 13:28:27.074  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
07-14 13:28:27.074  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-14 13:28:27.078  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-14 13:28:27.079  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-14 13:28:27.079  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.079  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-14 13:28:27.082  9513  9594 D BluetoothSocket: connect(): myUserId = 0
07-14 13:28:27.082  9513  9594 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-14 13:28:27.083  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:27.083  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:27.083  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.084  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-14 13:28:27.084  9513  9577 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-14 13:28:27.084  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-14 13:28:27.084  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-14 13:28:27.086  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-14 13:28:27.087  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-14 13:28:27.087  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-14 13:28:27.087  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,07-14 13:28:27.087  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-14 13:28:27.087  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,07-14 13:28:27.087  9513  9595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-14 13:28:27.087  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-14 13:28:27.087  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-14 13:28:27.087  9513  9513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-14 13:28:27.090  9513  9595 D BluetoothSocket: bindListen(): myUserId = 0
,07-14 13:28:27.090  9513  9595 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-14 13:28:27.093  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-14 13:28:27.094  9513  9577 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-14 13:28:27.094  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-14 13:28:27.095  9513  9595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-14 13:28:27.095  9513  9595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@b5dd10f, port: 6, type: 1, local socket address: null, socket type: 0
,07-14 13:28:27.097  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:27.097  3707  3965 D SecContentProvider: insert(), uri = 2
,07-14 13:28:27.098  3707  3965 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:27.099  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:27.099  4056  4469 W bt_btif : bta_dm_bl_change_cback : reason=0
,07-14 13:28:27.101  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:27.102  4056  4178 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
,07-14 13:28:27.105  9513  9577 D BluetoothAdapter: isSecureModeEnabled
,07-14 13:28:27.105  4056  4483 D BtConfig.SecureMode: isSecureModeOn:false
,07-14 13:28:27.107  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.107  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-14 13:28:27.108  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:27.110  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:27.110  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-14 13:28:27.110  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-14 13:28:27.110  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,07-14 13:28:27.112  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:27.115  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.115  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.115  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-14 13:28:27.115  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-14 13:28:27.115  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "9efc9363-3d2b-4b01-abd9-143186647519", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-14 13:28:27.115  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 4A 3E
,07-14 13:28:27.116  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-14 13:28:27.116  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-14 13:28:27.116  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.116  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.116  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-14 13:28:27.117  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-14 13:28:27.117  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.117  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.117  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.119  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:27.120  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:27.120  9513  9577 D BluetoothAdapter: isSecureModeEnabled
,07-14 13:28:27.120  4056  4068 D BtConfig.SecureMode: isSecureModeOn:false
07-14 13:28:27.120  9513  9577 D BluetoothLeAdvertiser: start advertising
,07-14 13:28:27.121  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:27.126  4056  4654 D BtGatt.GattService: registerClient() - UUID=254dcefd-7c9a-4d5a-bd1c-4064e9081a1f
,07-14 13:28:27.230  4056  4178 D BtGatt.GattService: onClientRegistered() - UUID=254dcefd-7c9a-4d5a-bd1c-4064e9081a1f, clientIf=5, status=0
,07-14 13:28:27.231  9513  9524 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-14 13:28:27.235  4056  4068 E BtGatt.ContextMap: Context not found for ID 5
07-14 13:28:27.236  4056  4377 D BtGatt.AdvertiseManager: message : 0
07-14 13:28:27.236  4056  4401 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-14 13:28:27.238  4056  4377 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-14 13:28:27.238  4056  4377 D BtGatt.AdvertiseManager: size of list is =0
,07-14 13:28:27.247  4056  4377 D BtGatt.AdvertiseManager: starting advertising
,07-14 13:28:27.252  4056  4377 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-14 13:28:27.257  4056  4469 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-14 13:28:27.278  4056  4178 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-14 13:28:27.281  4056  4377 D BtGatt.AdvertiseManager: starting multi advertising
,07-14 13:28:27.292  4056  4178 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
07-14 13:28:27.293  4056  4377 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-14 13:28:27.293  4056  4377 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-14 13:28:27.293  4056  4377 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-14 13:28:27.293  4056  4377 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-14 13:28:27.294  9513  9525 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-14 13:28:27.296  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.298  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.298  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-14 13:28:27.299  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.300  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.301  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.303  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.304  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.304  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-14 13:28:27.309  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-14 13:28:27.310  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.310  9513  9577 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,07-14 13:28:27.315  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.316  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.317  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.317  9513  9577 I io.jxcore.node.ConnectionHelper: start: OK
,07-14 13:28:27.318  9513  9513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-14 13:28:27.319  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.319  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,07-14 13:28:27.319  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-14 13:28:27.320  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.320  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.321  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-14 13:28:27.321  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.321  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-14 13:28:27.321  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-14 13:28:27.322  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.322  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.322  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.323  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.324  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-14 13:28:27.330  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.330  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-14 13:28:27.331  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,07-14 13:28:27.332  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.332  9513  9513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-14 13:28:27.819  9513  9586 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
07-14 13:28:27.820  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-14 13:28:27.820  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-14 13:28:27.820  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,07-14 13:28:27.820  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-14 13:28:27.821  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-14 13:28:27.821  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-14 13:28:27.821  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-14 13:28:27.821  9513  9595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-14 13:28:27.821  9513  9595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-14 13:28:27.821  9513  9595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-14 13:28:27.822  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-14 13:28:27.822  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,07-14 13:28:27.825  9513  9513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-14 13:28:27.825  9513  9513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-14 13:28:27.825  9513  9577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@150b940 removed from the list
07-14 13:28:27.826  9513  9513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-14 13:28:27.826  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@150b940 removed from the list
07-14 13:28:27.826  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-14 13:28:27.826  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-14 13:28:27.826  9513  9597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 195
07-14 13:28:27.826  9513  9597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
07-14 13:28:27.827  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.827  9513  9597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 195)
07-14 13:28:27.827  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-14 13:28:27.827  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-14 13:28:27.828  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.829  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.830  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.830  9513  9597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 195)
07-14 13:28:27.830  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.831  4056  4555 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
,07-14 13:28:27.832  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:27.833  9513  9594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
07-14 13:28:27.833  9513  9594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
07-14 13:28:27.833  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:27.833  9513  9594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 195)
07-14 13:28:27.833  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-14 13:28:27.835  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:27.837  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:27.837  9513  9577 D BluetoothLeScanner: could not find callback wrapper
07-14 13:28:27.837  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-14 13:28:27.837  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.838  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.839  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.839  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-14 13:28:27.839  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.841  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:27.842  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:27.842  9513  9577 D BluetoothLeAdvertiser: stop advertising
,07-14 13:28:27.843  4056  4654 E BtGatt.ContextMap: Context not found for ID 5
07-14 13:28:27.844  4056  4377 D BtGatt.AdvertiseManager: message : 1
07-14 13:28:27.844  4056  4401 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,07-14 13:28:27.845  4056  4377 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-14 13:28:27.845  4056  4377 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-14 13:28:27.847  4056  4377 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-14 13:28:27.852  4056  4178 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-14 13:28:27.852  4056  4178 D BtGatt.GattService: Client app is not null!
,07-14 13:28:27.852  9513  9524 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-14 13:28:27.854  4056  4068 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-14 13:28:27.855  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-14 13:28:27.856  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.856  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-14 13:28:27.857  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.857  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.858  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.858  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-14 13:28:27.858  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-14 13:28:27.859  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-14 13:28:27.860  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.862  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.865  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-14 13:28:27.866  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:27.868  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:27.868  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-14 13:28:27.868  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-14 13:28:27.868  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f509079 removed from the list
07-14 13:28:27.868  9513  9513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-14 13:28:27.868  9513  9577 D io.jxcore.node.ConnectivityMonitor: stop
07-14 13:28:27.868  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-14 13:28:27.869  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-14 13:28:27.870  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.871  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-14 13:28:27.871  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-14 13:28:27.871  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.871  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.872  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-14 13:28:27.872  9513  9513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-14 13:28:28.374  9513  9513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-14 13:28:29.992  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:29.992  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-14 13:28:30.288  4497  4497 D io_stats: !@   8,0 r 25034 2254968 w 4496 196664 d 559 72704 f 1817 1817 iot 10780 10354 th 474532 0 0 pt 0 inp 0 0 191.402
,07-14 13:28:30.357  3707  5610 D SSRM:f  : SIOP:: AP = 280, PST = 281 (W:14), CP = 236, CUR = 114, LCD = 57
,07-14 13:28:32.429  3707  3707 D UsbMonitorService: readUsbState++
,07-14 13:28:32.431  3707  3707 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-14 13:28:32.432  3707  3707 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-14 13:28:32.433  3707  3707 D UsbMonitorService: Posting Message again
,07-14 13:28:32.875  9513  9587 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,07-14 13:28:32.880  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,07-14 13:28:32.882  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,07-14 13:28:32.883  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-14 13:28:32.889  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-14 13:28:32.892  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-14 13:28:32.892  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-14 13:28:32.892  9513  9598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-14 13:28:32.892  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-14 13:28:32.893  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-14 13:28:32.893  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-14 13:28:32.894  9513  9513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-14 13:28:32.899  9513  9598 D BluetoothSocket: bindListen(): myUserId = 0
,07-14 13:28:32.899  9513  9598 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-14 13:28:32.900  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,07-14 13:28:32.901  9513  9577 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
07-14 13:28:32.902  9513  9577 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-14 13:28:32.902  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-14 13:28:32.904  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-14 13:28:32.905  9513  9598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-14 13:28:32.905  9513  9598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@697dba5, port: 6, type: 1, local socket address: null, socket type: 0
,07-14 13:28:32.907  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,07-14 13:28:32.917  9513  9577 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,07-14 13:28:32.918  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-14 13:28:32.918  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-14 13:28:32.918  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-14 13:28:32.918  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,07-14 13:28:32.919  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-14 13:28:32.919  9513  9598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-14 13:28:32.919  9513  9598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-14 13:28:32.919  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-14 13:28:32.919  9513  9598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-14 13:28:32.920  9513  9513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,07-14 13:28:32.920  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-14 13:28:32.920  9513  9577 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@150b940 not in the list
07-14 13:28:32.920  9513  9513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-14 13:28:32.921  9513  9577 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@150b940 not in the list
07-14 13:28:32.921  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-14 13:28:32.921  9513  9513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-14 13:28:32.921  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-14 13:28:32.921  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:32.921  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-14 13:28:32.922  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-14 13:28:32.922  9513  9577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-14 13:28:32.922  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-14 13:28:32.923  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:32.926  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:32.927  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-14 13:28:32.927  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:32.928  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:32.928  9513  9577 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f509079 not in the list
,07-14 13:28:32.928  9513  9577 D io.jxcore.node.ConnectivityMonitor: stop
07-14 13:28:32.928  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-14 13:28:32.928  9513  9577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-14 13:28:32.928  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-14 13:28:32.928  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-14 13:28:32.929  9513  9513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-14 13:28:32.931  9513  9577 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,07-14 13:28:32.932  9513  9577 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-14 13:28:32.933  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-14 13:28:32.933  9513  9577 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-14 13:28:32.933  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-14 13:28:32.933  9513  9577 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-14 13:28:32.934  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-14 13:28:32.936  9513  9577 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,07-14 13:28:32.938  9513  9577 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,07-14 13:28:32.940  9513  9577 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,07-14 13:28:32.941  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
07-14 13:28:32.942  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,07-14 13:28:32.943  9513  9577 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,07-14 13:28:32.945  9513  9577 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-14 13:28:32.945  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-14 13:28:32.945  9513  9577 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-14 13:28:32.946  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,07-14 13:28:32.946  9513  9577 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-14 13:28:32.946  9513  9577 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-14 13:28:32.948  9513  9577 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,07-14 13:28:32.948  9513  9577 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-14 13:28:32.949  9513  9577 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-14 13:28:32.950  9513  9577 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,07-14 13:28:32.951  9513  9577 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-14 13:28:32.951  9513  9577 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-14 13:28:32.951  9513  9577 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,07-14 13:28:32.952  9513  9577 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,07-14 13:28:32.953  9513  9577 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,07-14 13:28:32.955  9513  9577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-14 13:28:32.955  9513  9577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a32fb7a added. We now have 2 listener(s)
,07-14 13:28:32.955  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a32fb7a added. We now have 3 listener(s)
07-14 13:28:32.955  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-14 13:28:32.958  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:32.958  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-14 13:28:32.958  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:32.959  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-14 13:28:32.959  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab06f2b added. We now have 4 listener(s)
07-14 13:28:32.959  9513  9577 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-14 13:28:32.960  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-14 13:28:32.965  9513  9577 D BluetoothAdapter: enable()
,07-14 13:28:32.970  4056  4068 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,07-14 13:28:32.970  4056  4068 D AdapterProvider: query
,07-14 13:28:32.983  4056  4068 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@489b7d8
,07-14 13:28:32.985  4056  4068 D BluetoothAdapterService: updateEvent - already set, update
,07-14 13:28:32.985  4056  4068 W BluetoothAdapterService: updateEvent - alreadySet is true
07-14 13:28:32.985  4056  4068 D AdapterProvider: update
,07-14 13:28:32.989  4056  4068 E BluetoothAdapterService: updateEvent - update success 1
,07-14 13:28:32.991  9513  9577 D BluetoothAdapter: enable(): BT is already enabled..!
,07-14 13:28:33.002  3707  3922 D WifiService: setWifiEnabled: true pid=9513, uid=10033
,07-14 13:28:33.002  3707  3922 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-14 13:28:33.004  3707  3922 D WifiControlHistoryProvider: query
,07-14 13:28:33.011  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:33.011  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
07-14 13:28:33.012  3707  3922 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-14 13:28:33.013  3707  3922 D SecContentProvider: called from android.uid.system:1000
,07-14 13:28:33.013  3707  3922 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-14 13:28:33.017  3707  3922 I WifiService: Wi-Fi Sharing settings has not been accessed
07-14 13:28:33.017  3707  3922 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-14 13:28:33.019  9513  9577 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,07-14 13:28:33.021  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:33.025  9513  9577 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,07-14 13:28:33.027  9513  9577 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,07-14 13:28:33.028  9513  9577 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,07-14 13:28:33.033  9513  9599 D BluetoothAdapter: disable()
,07-14 13:28:33.038  4056  4654 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : false
07-14 13:28:33.038  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:33.038  4056  4654 D AdapterProvider: query
07-14 13:28:33.041  9513  9577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-14 13:28:33.041  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:33.041  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:33.041  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-14 13:28:33.041  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-14 13:28:33.041  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-14 13:28:33.041  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-14 13:28:33.041  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-14 13:28:33.041  9513  9577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-14 13:28:33.044  4056  4654 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@3ddc397
,07-14 13:28:33.045  4056  4654 D BluetoothAdapterService: updateEvent - already set, update
07-14 13:28:33.045  4056  4654 W BluetoothAdapterService: updateEvent - alreadySet is true
07-14 13:28:33.046  4056  4654 D AdapterProvider: update
,07-14 13:28:33.050  4056  4654 E BluetoothAdapterService: updateEvent - update success 1
,07-14 13:28:33.056  3707  3802 D SecContentProvider: insert(), uri = 2
,07-14 13:28:33.057  3707  3802 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:33.058  4056  4170 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,07-14 13:28:33.060  4056  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-14 13:28:33.060  4056  4170 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-14 13:28:33.063  4056  4056 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,07-14 13:28:33.064  3707  3802 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
,07-14 13:28:33.066  4056  4170 D BluetoothAdapterService: Autoconnection is available 
07-14 13:28:33.066  4056  4170 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-14 13:28:33.066  4056  4170 D BluetoothAdapterService: terminating service from this receiver
,07-14 13:28:33.074  4056  4170 W bt_btif : btif_dm_cancel_discovery
,07-14 13:28:33.076  3707  4313 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,07-14 13:28:33.077  3707  4313 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:33.078  4069  4348 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:33.078  4069  4348 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,07-14 13:28:33.078  3707  4312 D SecContentProvider: insert(), uri = 2
07-14 13:28:33.079  3707  4312 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:33.080  4056  4170 I BluetoothAdapterState: Entering PendingCommandState
,07-14 13:28:33.084  3707  3707 D BluetoothPhoneService: Bluetooth Adapter state : 13
,07-14 13:28:33.095  3707  3707 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-14 13:28:33.095  3707  3707 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
,07-14 13:28:33.095  3707  3707 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-14 13:28:33.102  3707  3783 D MountService: getExternalStorageMountMode : 1
07-14 13:28:33.102  3707  3783 D MountService: getExternalStorageMountMode : 3
,07-14 13:28:33.102  3707  3783 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.android.settings
,07-14 13:28:33.104  9513  9513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-14 13:28:33.104  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-14 13:28:33.104  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:33.104  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:33.104  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-14 13:28:33.104  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-14 13:28:33.104  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-14 13:28:33.104  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-14 13:28:33.104  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-14 13:28:33.104  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-14 13:28:33.106  9513  9513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-14 13:28:33.106  9513  9513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-14 13:28:33.122  9601  9601 E Zygote  : v2
07-14 13:28:33.122  9601  9601 I libpersona: KNOX_SDCARD checking this for 1000
07-14 13:28:33.122  9601  9601 I libpersona: KNOX_SDCARD not a persona
,07-14 13:28:33.123  9601  9601 E Zygote  : accessInfo : 0
,07-14 13:28:33.124  9601  9601 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:33.126  9601  9601 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.android.settings 
,07-14 13:28:33.128  3707  3783 I ActivityManager: Start proc 9601:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,07-14 13:28:33.129  4069  4069 D BluetoothPbap: Proxy object disconnected
07-14 13:28:33.129  4069  4069 D PbapServerProfile: Bluetooth service disconnected
,07-14 13:28:33.130  4056  4056 D DOWNLOADABLE_DB: onReceive of BR
07-14 13:28:33.130  4056  4056 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-14 13:28:33.131  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.131  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:33.133  3707  4737 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{82c5b4f: PendingIntentRecord{ccf22dc com.google.android.gms broadcastIntent}}
07-14 13:28:33.135  4056  4178 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-14 13:28:33.136  4056  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,07-14 13:28:33.139  4056  4170 E BluetoothServiceJni: disableBrEdrNative:
07-14 13:28:33.139  4056  4170 E bt_btif : disable_bredr
07-14 13:28:33.139  4056  4178 W bt_btif : btif_dm_generic_evt: event=33035
07-14 13:28:33.139  4056  4556 W bt_osi_thread: run_thread: thread id 4556, thread name btif_sock exited
07-14 13:28:33.142  4056  4173 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-14 13:28:33.142  4056  4861 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-14 13:28:33.142  4056  5324 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-14 13:28:33.142  4056  4862 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-14 13:28:33.143  4056  4173 E bt_btif : BTA_DisableBluetoothOnly
07-14 13:28:33.143  4056  4861 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-14 13:28:33.144  4056  4862 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-14 13:28:33.145  4056  4469 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
07-14 13:28:33.146  4056  4178 W bt_btif : btif_dm_generic_evt: event=33035
,07-14 13:28:33.148  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:33.148  3707  3908 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{2f90fe5: PendingIntentRecord{701baba com.google.android.gms broadcastIntent}}
,07-14 13:28:33.150  3707  4312 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4056 / op:PendingIntent{87d5d6b: PendingIntentRecord{b9990c8 com.android.bluetooth broadcastIntent}}
,07-14 13:28:33.151  4056  4178 W bt_btif : btif_dm_generic_evt: event=33035
07-14 13:28:33.159  4056  4056 D DOWNLOADABLE_DB: onReceive of BR
07-14 13:28:33.159  4056  4056 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-14 13:28:33.159  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.159  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.159  4056  4056 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:33.160  4056  4056 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
,07-14 13:28:33.160  4056  4056 D BluetoothSdpJni: SDP Remove record success - handle: 1
07-14 13:28:33.160  4056  4546 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
07-14 13:28:33.160  4056  4546 D BluetoothSdpJni: SDP Remove record success - handle: 0
,07-14 13:28:33.160  4056  4546 D BluetoothMapMasInstance: RemoveSDPrecord returns true
07-14 13:28:33.160  4056  4546 D ObexServerSockets: shutdown(block = true)
07-14 13:28:33.160  4056  4546 D ObexServerSockets: shutdown called from another thread - interrupt().
07-14 13:28:33.160  4056  4546 D ObexServerSockets: shutdown called from another thread - interrupt().
07-14 13:28:33.160  4056  4056 I BtOppRfcommListener: stopping Accept Thread
07-14 13:28:33.162  4056  5324 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-14 13:28:33.163  4056  4178 W bt_btif : btif_dm_generic_evt: event=33035
07-14 13:28:33.164  4056  4469 W bt_btm  : btm_sec_connected
,07-14 13:28:33.164  4056  4469 W bt_btif : bta_dm_bl_change_cback : reason=2
07-14 13:28:33.164  4056  4469 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
07-14 13:28:33.164  4056  4469 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
07-14 13:28:33.164  4056  4469 W bt_btif : bta_dm_bl_change_cback : reason=2
07-14 13:28:33.166  4056  4178 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
07-14 13:28:33.166  4056  4178 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
07-14 13:28:33.168  4056  4056 V BluetoothOppManager: cleanUp...
07-14 13:28:33.170  9601  9601 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:33.170  9601  9601 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:33.173  3707  4312 I ActivityManager: DSS on for com.android.settings and scale is 1.0
,07-14 13:28:33.177  4056  4170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:33.179  4056  4178 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 1
,07-14 13:28:33.184  4056  4178 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-14 13:28:33.185  4056  4178 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 241
07-14 13:28:33.185  4069  4348 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,07-14 13:28:33.209  9601  9601 W System  : ClassLoader referenced unknown path: /system/priv-app/SecSettings2/lib/arm64
,07-14 13:28:33.233  9601  9601 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:33.246  3707  4226 E Watchdog: !@Sync 6 [14_lip_13_28_33.246]
,07-14 13:28:33.255  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-14 13:28:33.261  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-14 13:28:33.261  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-14 13:28:33.267  9601  9601 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : ACCESSIBILITYSETTINGS, X6qErjsfs2, com.samsung.android.settings.accessibility.sharedaccessibility.scloud.BNRTask
,07-14 13:28:33.268  9601  9601 I QBNRClientHelper: init SyncClientHelper : ACCESSIBILITYSETTINGS
07-14 13:28:33.268  9601  9601 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : CONNECTIONS, C0phMaUuZZ, com.samsung.android.settings.wifi.mobileap.WifiApBackupRestore
07-14 13:28:33.269  9601  9601 I QBNRClientHelper: init SyncClientHelper : CONNECTIONS
07-14 13:28:33.269  9601  9601 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : WiFi, C0phMaUuZZ, com.samsung.android.settings.wifi.WifiBackupRestore
,07-14 13:28:33.269  9601  9601 I QBNRClientHelper: init SyncClientHelper : WiFi
,07-14 13:28:33.283  9601  9601 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-14 13:28:33.290  9601  9601 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,07-14 13:28:33.295  9601  9601 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,07-14 13:28:33.296  9601  9601 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,07-14 13:28:33.300  9601  9601 D LocalBluetoothProfileManager: LocalBluetoothProfileManager :: uuid is null
07-14 13:28:33.300  9601  9601 D LocalBluetoothProfileManager: PANU : true
,07-14 13:28:33.306  9601  9601 D BluetoothSap: Create BluetoothSap proxy object
,07-14 13:28:33.310  9601  9601 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-14 13:28:33.310  9601  9601 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,07-14 13:28:33.315  9601  9601 D DockEventReceiver: finishStartingService: stopping service
,07-14 13:28:33.317  9601  9601 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:33.317  9601  9601 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
07-14 13:28:33.317  9601  9601 D BluetoothPan: BluetoothPAN Proxy object connected
,07-14 13:28:33.317  9601  9601 D PanProfile: Bluetooth service connected
,07-14 13:28:33.318  9601  9601 D BluetoothSap: Proxy object connected
07-14 13:28:33.319  9601  9601 D SapProfile: Bluetooth service connected
,07-14 13:28:33.328  3707  3908 I ActivityManager: KPU : put [com.samsung.android.app.mirrorlink] : 21176 K
07-14 13:28:33.328  3707  3908 I ActivityManager: Killing 8811:com.samsung.android.app.mirrorlink/1000 (adj 906): DHA:empty #33
,07-14 13:28:33.348  3707  4737 D ActivityManager: cleanUpApplicationRecord -- 8811
,07-14 13:28:33.349  4615  4626 D ForegroundUtils: could not check pending caller
,07-14 13:28:33.357  4056  4178 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_BT_EVT
07-14 13:28:33.357  4056  4178 E BluetoothAdapterState: stateChangeCallback : 16
07-14 13:28:33.357  4056  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
,07-14 13:28:33.361  4056  4170 D BtConfig.SecureMode: isSecureModeOn:false
07-14 13:28:33.362  4056  4170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-14 13:28:33.372  4056  4170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-14 13:28:33.373  4056  4056 D HeadsetService: Received stop request...Stopping profile...
,07-14 13:28:33.377  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.378  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
07-14 13:28:33.378  4056  4056 D HeadsetService: notifyProfileServiceStateChanged
07-14 13:28:33.379  4056  4170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-14 13:28:33.381  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:33.381  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
07-14 13:28:33.381  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-14 13:28:33.381  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-14 13:28:33.381  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:33.381  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:33.382  4056  4056 D A2dpService: Received stop request...Stopping profile...
07-14 13:28:33.384  4069  4069 D HeadsetProfile: Bluetooth service disconnected
07-14 13:28:33.385  3707  3707 W BluetoothHeadset: Proxy not attached to service
07-14 13:28:33.385  3707  3707 I Telecom : SecBluetoothManager : not single connected gear
07-14 13:28:33.385  3707  3707 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
07-14 13:28:33.385  3707  3707 D BluetoothHeadset: unRegisterMessageListener : 11
07-14 13:28:33.385  3707  3707 W BluetoothHeadset: Proxy not attached to service
07-14 13:28:33.385  3707  3707 I Telecom : SecBluetoothManager : unregister MessageListener
07-14 13:28:33.385  3707  4365 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACs_0
07-14 13:28:33.385  3707  4365 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACs_0
07-14 13:28:33.385  3707  4365 I Telecom : SecBluetoothManager : mBluetoothHeadset is null
07-14 13:28:33.386  3707  4365 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACs_0
07-14 13:28:33.390  4056  4541 D A2dpStateMachine: Exit Disconnected: -1
,07-14 13:28:33.429  9513  9513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-14 13:28:33.543  4056  4056 D Avrcp   : unregisterContentObserver
07-14 13:28:33.544  4056  4170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-14 13:28:33.545  4056  4056 D Avrcp   : removeOnActiveSessionsChangedListener
07-14 13:28:33.549  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.549  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
07-14 13:28:33.549  4056  4056 D A2dpService: notifyProfileServiceStateChanged
,07-14 13:28:33.554  4056  4170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-14 13:28:33.554  4069  4069 D A2dpProfile: Bluetooth service disconnected
,07-14 13:28:33.555  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:33.564  4056  4170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-14 13:28:33.565  4056  4056 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-14 13:28:33.565  4056  4056 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-14 13:28:33.567  4056  4056 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
07-14 13:28:33.568  4056  4170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-14 13:28:33.568  9513  9599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-14 13:28:33.568  9513  9599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-14 13:28:33.568  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:33.568  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:33.568  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-14 13:28:33.568  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-14 13:28:33.568  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-14 13:28:33.568  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-14 13:28:33.568  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-14 13:28:33.568  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-14 13:28:33.568  4056  4056 D HidService: Received stop request...Stopping profile...
07-14 13:28:33.568  4056  4056 D HidService: Stopping Bluetooth HidService
07-14 13:28:33.569  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.569  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
07-14 13:28:33.569  4056  4056 D HidService: notifyProfileServiceStateChanged
07-14 13:28:33.570  4069  4069 D BluetoothInputDevice: Proxy object disconnected
07-14 13:28:33.571  4069  4069 D HidProfile: Bluetooth service disconnected
07-14 13:28:33.572  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:33.572  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
07-14 13:28:33.572  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-14 13:28:33.572  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-14 13:28:33.572  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:33.572  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:33.574  4056  4170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-14 13:28:33.574  4056  4170 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-14 13:28:33.574  4056  4170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
07-14 13:28:33.574  4056  4170 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
07-14 13:28:33.574  4056  4170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-14 13:28:33.575  4056  4056 D HealthService: Received stop request...Stopping profile...
07-14 13:28:33.575  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.576  9513  9599 D BluetoothAdapter: enable()
07-14 13:28:33.576  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
07-14 13:28:33.576  4056  4056 D HealthService: notifyProfileServiceStateChanged
07-14 13:28:33.579  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:33.581  4056  4542 W bt_osi_thread: run_thread: thread id 4542, thread name media_worker exited
,07-14 13:28:33.582  9513  9577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:33.585  4056  4056 D PanService: Received stop request...Stopping profile...
07-14 13:28:33.586  4056  4068 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-14 13:28:33.586  4056  4068 D AdapterProvider: query
,07-14 13:28:33.594  4056  4056 D EnhancedTetheringManager: stop
07-14 13:28:33.597  4056  4068 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@3b10233
07-14 13:28:33.598  4056  4056 D EnhancedTetheringManager: tetherEnabled : false
07-14 13:28:33.598  4056  4068 D BluetoothAdapterService: updateEvent - already set, update
07-14 13:28:33.598  4056  4056 D ETMLeHelper: stopAdvertise
07-14 13:28:33.598  4056  4068 W BluetoothAdapterService: updateEvent - alreadySet is true
07-14 13:28:33.598  4056  4068 D AdapterProvider: update
,07-14 13:28:33.601  4056  4056 D BluetoothAdapter: STATE_TURNING_OFF
,07-14 13:28:33.602  4056  4056 D BluetoothAdapter: STATE_TURNING_OFF
07-14 13:28:33.602  4056  4056 D BluetoothLeAdvertiser: stop advertising
07-14 13:28:33.602  4056  4068 E BluetoothAdapterService: updateEvent - update success 1
07-14 13:28:33.602  4056  4056 D BluetoothLeAdvertiser: wrapper is null
07-14 13:28:33.602  4056  4056 D EnhancedTetheringManager: removeNapWakeAlarm
07-14 13:28:33.605  3707  4313 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4056 / op:PendingIntent{e179fa4: PendingIntentRecord{f8b210d com.android.bluetooth broadcastIntent}}
07-14 13:28:33.605  4056  4056 D EnhancedTetheringManager: cancelFindTetherServer
07-14 13:28:33.605  4056  4056 D ETMLeHelper: stopScan
07-14 13:28:33.606  4056  4056 D BluetoothAdapter: STATE_TURNING_OFF
07-14 13:28:33.607  4056  4056 D BluetoothAdapter: STATE_TURNING_OFF
07-14 13:28:33.607  4056  4056 D BluetoothLeScanner: could not find callback wrapper
07-14 13:28:33.607  4056  4056 D EnhancedTetheringManager: removePanuWakeAlarm
07-14 13:28:33.609  3707  4313 W ActivityManager: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-14 13:28:33.610  3707  3965 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4056 / op:PendingIntent{f5d38c2: PendingIntentRecord{a0876d3 com.android.bluetooth broadcastIntent}}
07-14 13:28:33.610  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.610  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
07-14 13:28:33.610  4056  4056 D PanService: notifyProfileServiceStateChanged
,07-14 13:28:33.612  9601  9601 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-14 13:28:33.612  4069  4069 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-14 13:28:33.612  4069  4069 D PanProfile: Bluetooth service disconnected
07-14 13:28:33.613  9601  9601 D PanProfile: Bluetooth service disconnected
07-14 13:28:33.613  3707  4313 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-14 13:28:33.613  3707  4313 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-14 13:28:33.613  3707  4313 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-14 13:28:33.613  3707  4313 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-14 13:28:33.613  3707  4313 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-14 13:28:33.613  3707  4313 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-14 13:28:33.613  3707  4313 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-14 13:28:33.613  3707  4313 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-14 13:28:33.613  3707  4313 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-14 13:28:33.613  3707  4313 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
07-14 13:28:33.614  4056  4056 D BluetoothMapService: Received stop request...Stopping profile...
,07-14 13:28:33.616  3707  4313 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-14 13:28:33.618  3707  4313 D SecContentProvider: called from com.thaliproject.thalitest
,07-14 13:28:33.622  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.622  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
,07-14 13:28:33.623  4056  4056 D BluetoothMapService: notifyProfileServiceStateChanged
,07-14 13:28:33.626  4069  4069 D BluetoothMap: Proxy object disconnected
07-14 13:28:33.626  4069  4069 D MapProfile: Bluetooth service disconnected
,07-14 13:28:33.628  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
,07-14 13:28:33.628  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
07-14 13:28:33.628  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-14 13:28:33.628  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-14 13:28:33.628  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:33.628  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:33.628  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.628  4056  4056 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-14 13:28:33.628  4056  4056 W bt_btif : cleanup: HH disabling or disabled already, status = 0
,07-14 13:28:33.628  4056  4056 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,07-14 13:28:33.630  4056  4056 D SapService: Received stop request...Stopping profile...
07-14 13:28:33.630  4056  4056 V SapService: stop()
07-14 13:28:33.631  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.631  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
07-14 13:28:33.631  4056  4056 D SapService: notifyProfileServiceStateChanged
,07-14 13:28:33.633  4069  4069 D BluetoothSap: Proxy object disconnected
,07-14 13:28:33.633  4069  4069 D SapProfile: Bluetooth service disconnected
07-14 13:28:33.633  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:33.633  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
07-14 13:28:33.633  9601  9601 D BluetoothSap: Proxy object disconnected
07-14 13:28:33.633  9601  9601 D SapProfile: Bluetooth service disconnected
,07-14 13:28:33.639  4056  4056 V BluetoothAdapterState: isTurningOff()=true
,07-14 13:28:33.639  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-14 13:28:33.639  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:33.639  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
,07-14 13:28:33.640  4056  4056 D HidDevService: Received stop request...Stopping profile...
,07-14 13:28:33.640  4056  4056 D HidDevService: stop()
07-14 13:28:33.640  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.640  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Message sending
07-14 13:28:33.640  4056  4056 D HidDevService: notifyProfileServiceStateChanged
,07-14 13:28:33.643  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:33.643  4056  4056 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-14 13:28:33.643  3707  4717 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{55c109: PendingIntentRecord{b4a1f0e com.google.android.gms broadcastIntent}}
07-14 13:28:33.643  4056  4056 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-14 13:28:33.643  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:33.643  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
07-14 13:28:33.644  4056  4056 V BluetoothAdapterState: isTurningOff()=true
,07-14 13:28:33.644  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-14 13:28:33.644  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:33.644  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:33.644  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.644  4056  4056 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-14 13:28:33.644  4056  4056 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-14 13:28:33.646  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:33.647  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
,07-14 13:28:33.647  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-14 13:28:33.647  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-14 13:28:33.647  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:33.647  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:33.647  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.647  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:33.647  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
07-14 13:28:33.647  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-14 13:28:33.647  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-14 13:28:33.647  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:33.647  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:33.647  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.648  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:33.648  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Before synchronized
07-14 13:28:33.648  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-14 13:28:33.648  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-14 13:28:33.648  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:33.648  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:33.648  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.648  4056  4056 D HidDevService: cleanup()
07-14 13:28:33.648  4056  4056 V BluetoothHidDevServiceJni: cleanupNative enter
07-14 13:28:33.648  4056  4056 I BluetoothHidDevServiceJni: Cleaning up interface
07-14 13:28:33.648  4056  4056 I BluetoothHidDevServiceJni: Cleaning up callback object
07-14 13:28:33.648  4056  4056 V BluetoothHidDevServiceJni: cleanupNative done
07-14 13:28:33.649  4056  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
07-14 13:28:33.651  4056  4170 D BtGatt.GattService: getGattService(): returning com.android.bluetooth.gatt.GattService@61e58ef
,07-14 13:28:33.651  4056  4170 D BtGatt.GattService: serverDisconnectIncomingConnClients()
07-14 13:28:33.651  4056  4469 W bt_btif : BTA got unregistered event id 32
07-14 13:28:33.651  4056  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-14 13:28:33.652  4056  4170 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-14 13:28:33.652  3707  3743 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{6d9ad2f: PendingIntentRecord{ecd3f3c com.google.android.gms broadcastIntent}}
07-14 13:28:33.656  4056  4170 D BluetoothAdapterService: Autoconnection is available 
07-14 13:28:33.656  4056  4170 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
07-14 13:28:33.656  4056  4170 I BluetoothAdapterState: Entering BleOnState
07-14 13:28:33.657  4056  4056 D DOWNLOADABLE_DB: onReceive of BR
07-14 13:28:33.657  4056  4056 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-14 13:28:33.658  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.658  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.664  4069  4082 D BluetoothMap: onBluetoothStateChange: up=false
07-14 13:28:33.665  4056  4056 D DOWNLOADABLE_DB: onReceive of BR
07-14 13:28:33.665  4056  4056 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-14 13:28:33.665  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:33.665  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:33.667  4069  4080 D BluetoothAdapter: onBluetoothStateChange: up=false
07-14 13:28:33.667  4069  4080 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-14 13:28:33.670  4576  6622 I BeaconBle: Client requested to stop, listener=hjz@7d8355d
07-14 13:28:33.674  4069  4080 D BluetoothAdapter: There are no active google scan apps, stop scan
07-14 13:28:33.674  9601  9612 D BluetoothAdapter: onBluetoothStateChange: up=false
07-14 13:28:33.675  9601  9612 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-14 13:28:33.678  4056  4170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.680  9601  9612 D BluetoothAdapter: There are no active google scan apps, stop scan
07-14 13:28:33.680  4069  4349 D BluetoothSap: onBluetoothStateChange: up=false
07-14 13:28:33.695  4056  4064 E System  : Uncaught exception thrown by finalizer
,07-14 13:28:33.700  9601  9613 D BluetoothSap: onBluetoothStateChange: up=false
,07-14 13:28:33.702  4576  6616 W NearbyMessages: NetworkPollManager:  No operations for client(com.google.android.gms#0p:discoverer). It should not be in the tracker.
07-14 13:28:33.702  4576  6616 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
07-14 13:28:33.702  4056  4064 E System  : java.io.IOException: socket not created
07-14 13:28:33.702  4056  4064 E System  : 	at android.net.LocalSocketImpl.shutdownInput(LocalSocketImpl.java:404)
07-14 13:28:33.702  4056  4064 E System  : 	at android.net.LocalSocket.shutdownInput(LocalSocket.java:207)
07-14 13:28:33.702  4056  4064 E System  : 	at android.bluetooth.BluetoothSocket.close(BluetoothSocket.java:800)
07-14 13:28:33.702  4056  4064 E System  : 	at android.bluetooth.BluetoothSocket.finalize(BluetoothSocket.java:309)
07-14 13:28:33.702  4056  4064 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:222)
07-14 13:28:33.702  4056  4064 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:209)
07-14 13:28:33.702  4056  4064 E System  : 	at java.lang.Thread.run(Thread.java:762)
07-14 13:28:33.703  4056  4064 E System  : Uncaught exception thrown by finalizer
,07-14 13:28:33.703  4056  4064 E System  : java.io.IOException: socket not created
07-14 13:28:33.703  4056  4064 E System  : 	at android.net.LocalSocketImpl.shutdownInput(LocalSocketImpl.java:404)
07-14 13:28:33.703  4056  4064 E System  : 	at android.net.LocalSocket.shutdownInput(LocalSocket.java:207)
07-14 13:28:33.703  4056  4064 E System  : 	at android.bluetooth.BluetoothSocket.close(BluetoothSocket.java:800)
07-14 13:28:33.703  4056  4064 E System  : 	at android.bluetooth.BluetoothSocket.finalize(BluetoothSocket.java:309)
07-14 13:28:33.703  4056  4064 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:222)
07-14 13:28:33.703  4056  4064 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:209)
07-14 13:28:33.703  4056  4064 E System  : 	at java.lang.Thread.run(Thread.java:762)
07-14 13:28:33.705  9601  9612 D BluetoothPan: onBluetoothStateChange on: false
,07-14 13:28:33.706  4576  6622 I BeaconBle: Scan canceled successfully.
,07-14 13:28:33.710  3707  4718 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{7cd1328: PendingIntentRecord{7178841 com.google.android.gms broadcastIntent}}
,07-14 13:28:33.711  4576  6506 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-14 13:28:33.711  4576  6506 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-14 13:28:33.712  4576  6506 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-14 13:28:33.712  4576  6506 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
07-14 13:28:33.712  4576  6506 D BluetoothLeScanner: Exiting stopAllScan
,07-14 13:28:33.715  4069  4082 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-14 13:28:33.716  3707  3802 D BluetoothAdapter: onBluetoothStateChange: up=false
07-14 13:28:33.716  3707  3802 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-14 13:28:33.716  3707  3802 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-14 13:28:33.718  4615  4626 D BluetoothAdapter: onBluetoothStateChange: up=false
07-14 13:28:33.718  4615  4626 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-14 13:28:33.719  4615  4626 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-14 13:28:33.720  7412  7424 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-14 13:28:33.720  7412  7424 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-14 13:28:33.721  7412  7424 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-14 13:28:33.721  4069  4349 D BluetoothPbap: onBluetoothStateChange: up=false
,07-14 13:28:33.723  4069  4883 D BluetoothPan: onBluetoothStateChange on: false
,07-14 13:28:33.725  9513  9524 D BluetoothAdapter: onBluetoothStateChange: up=false
07-14 13:28:33.725  9513  9524 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-14 13:28:33.725  9513  9524 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
07-14 13:28:33.725  9513  9524 D BluetoothLeAdvertiser: Exit stop advertising
,07-14 13:28:33.726  9513  9524 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-14 13:28:33.726  9513  9524 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
07-14 13:28:33.726  9513  9524 D BluetoothLeScanner: Exiting stopAllScan
07-14 13:28:33.727  4043  4055 D BluetoothAdapter: onBluetoothStateChange: up=false
07-14 13:28:33.727  4043  4055 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-14 13:28:33.727  4043  4055 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-14 13:28:33.728  4056  4067 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-14 13:28:33.729  4056  4170 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,07-14 13:28:33.733  3707  3707 D Telecom : SecBluetoothManager : unregister BluetoothHeadset after STATE_OFF : null
07-14 13:28:33.733  3707  3707 D Telecom : SecBluetoothManager : unRegisterBluetoothHeadsetMessageListener fail
,07-14 13:28:33.733  3707  3707 D BluetoothPhoneService: Bluetooth Adapter state : 10
07-14 13:28:33.733  4069  4348 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:33.733  4069  4348 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,07-14 13:28:33.735  3707  3707 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-14 13:28:33.735  3707  3707 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:33.735  3707  3707 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-14 13:28:33.742  9601  9601 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:33.742  9601  9601 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
07-14 13:28:33.744  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:33.748  4056  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-14 13:28:33.748  4056  4170 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-14 13:28:33.748  3707  3802 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
07-14 13:28:33.748  4056  4170 D BluetoothAdapterService: Autoconnection is available 
07-14 13:28:33.749  4056  4170 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
,07-14 13:28:33.750  3707  4718 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,07-14 13:28:33.751  4056  4056 D DOWNLOADABLE_DB: onReceive of BR
07-14 13:28:33.751  3707  4718 D SecContentProvider: called from android.uid.bluetooth:1002
07-14 13:28:33.751  4056  4056 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-14 13:28:33.751  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.751  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:33.754  3707  4313 D SecContentProvider: insert(), uri = 2
07-14 13:28:33.754  3707  4313 D SecContentProvider: called from android.uid.bluetooth:1002
07-14 13:28:33.755  4056  4173 E bt_btif : btif_vhci_sock_cleanup
07-14 13:28:33.756  4056  4170 I BluetoothAdapterState: Entering PendingCommandState
07-14 13:28:33.758  4056  4173 I bt_core_module: module_shut_down Shutting down module "btif_config_module"
07-14 13:28:33.760  4056  4056 D DOWNLOADABLE_DB: onReceive of BR
07-14 13:28:33.761  4056  4056 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-14 13:28:33.761  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.761  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:33.761  4056  4469 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-14 13:28:33.763  4056  4178 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-14 13:28:33.763  4056  4178 W bt_btif : btif_dm_generic_evt: event=33035
07-14 13:28:33.764  3707  4737 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{3cf01e6: PendingIntentRecord{f9c1327 com.google.android.gms broadcastIntent}}
,07-14 13:28:33.771  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:33.774  9601  9601 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-14 13:28:33.775  3707  4737 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{a7439d4: PendingIntentRecord{b13677d com.google.android.gms broadcastIntent}}
07-14 13:28:33.776  4056  4178 W bt_btif : btif_dm_generic_evt: event=33035
07-14 13:28:33.777  4056  4173 I bt_core_module: module_shut_down Shutdown of module "btif_config_module" completed
,07-14 13:28:33.788  9601  9601 D DockEventReceiver: finishStartingService: stopping service
,07-14 13:28:33.794  9601  9601 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:33.794  9601  9601 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,07-14 13:28:33.820  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-14 13:28:33.827  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-14 13:28:33.827  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-14 13:28:33.965  4056  4178 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_EVT
,07-14 13:28:33.965  4056  4178 I bt_core_module: module_shut_down Shutting down module "hci_module"
07-14 13:28:33.965  4056  4178 I bt_hci  : shut_down
,07-14 13:28:34.023  4056  4403 D bt_hwcfg: hw_epilog_process
07-14 13:28:34.025  4056  4403 I bt_vendor: low_power_mode_cb
,07-14 13:28:34.032  4056  4403 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-14 13:28:34.032  4056  4403 I bt_vendor: epilog_cb
07-14 13:28:34.032  4056  4403 I bt_hci  : epilog_finished_callback
07-14 13:28:34.033  5059  6572 I Authzen : [PermitStore] Getting all permits...
07-14 13:28:34.035  4056  4403 W bt_osi_thread: run_thread: thread id 4403, thread name hci_thread exited
07-14 13:28:34.037  4056  4178 I bt_hci_h4: hal_close
07-14 13:28:34.037  4056  4429 W bt_osi_thread: run_thread: thread id 4429, thread name hci_single_chann exited
07-14 13:28:34.038  4056  4178 I bt_userial_vendor: device fd = 96 close
07-14 13:28:34.039  4056  4178 I bt_upio : upio_set_bluetooth_power(on: 0)
07-14 13:28:34.047  4056  4178 I bt_core_module: module_shut_down Shutdown of module "hci_module" completed
,07-14 13:28:34.047  4056  4178 I bt_core_module: module_shut_down Shutting down module "btsnoop_module"
07-14 13:28:34.047  4056  4178 I bt_core_module: module_shut_down Shutdown of module "btsnoop_module" completed
07-14 13:28:34.048  4056  4178 I bt_core_module: module_clean_up Cleaning up module "bte_logmsg_module"
07-14 13:28:34.048  4056  4178 I bt_core_module: module_clean_up Cleanup of module "bte_logmsg_module" completed
07-14 13:28:34.049  4056  4469 W bt_osi_thread: run_thread: thread id 4469, thread name bt_workqueue exited
07-14 13:28:34.050  4056  4173 I bt_core_module: module_shut_down Shutting down module "controller_module"
07-14 13:28:34.050  4056  4173 I bt_core_module: module_shut_down Shutdown of module "controller_module" completed
07-14 13:28:34.051  4056  4178 E BluetoothAdapterState: stateChangeCallback : 0
07-14 13:28:34.051  4056  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
07-14 13:28:34.053  3707  3805 I PowerManagerService: [PWL] On : 0 (195168 ms ago)
07-14 13:28:34.053  3707  3805 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-14 13:28:34.068  4056  4056 D BtGatt.DebugUtils: handleDebugAction() action=null
07-14 13:28:34.069  4056  4170 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-14 13:28:34.069  4056  4056 D BtGatt.GattService: Received stop request...Stopping profile...
07-14 13:28:34.069  4056  4056 D BtGatt.GattService: stop()
07-14 13:28:34.069  4056  4056 D BtGatt.GattService: cleanup binder
,07-14 13:28:34.069  4056  4056 D BtGatt.AdvertiseManager: advertise clients cleared
07-14 13:28:34.069  4056  4056 D BtGatt.ScanManager: cleanup
07-14 13:28:34.070  3707  3908 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4056 / op:PendingIntent{c7cef6c: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
,07-14 13:28:34.072  4056  4056 D BtGatt.ScanManager: cleanup handler
,07-14 13:28:34.074  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:34.074  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
07-14 13:28:34.074  4056  4056 D BtGatt.GattService: notifyProfileServiceStateChanged
,07-14 13:28:34.075  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:34.075  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
07-14 13:28:34.075  4056  4056 V BluetoothAdapterState: isTurningOff()=false
07-14 13:28:34.075  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-14 13:28:34.075  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:34.075  4056  4056 V BluetoothAdapterState: isBleTurningOff()=true
07-14 13:28:34.076  4056  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
,07-14 13:28:34.079  4056  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,07-14 13:28:34.079  4056  4170 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-14 13:28:34.080  3707  3802 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
07-14 13:28:34.083  4056  4170 D BluetoothAdapterService: Autoconnection is available 
07-14 13:28:34.083  4056  4170 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
07-14 13:28:34.083  4056  4170 I BluetoothAdapterState: Entering OffState
,07-14 13:28:34.095  4056  4056 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-14 13:28:34.095  4056  4056 W BluetoothSdpJni: Cleaning up Bluetooth SDP object
,07-14 13:28:34.096  4056  4173 E BluetoothServiceJni: Callback env check fail: env: 0x0, callback: 0xda5c63d0
07-14 13:28:34.096  4056  4173 E BluetoothServiceJni: Callback: 'callback_thread_event' is not called on the correct thread
07-14 13:28:34.096  4056  4178 W bt_btif : btif_dm_generic_evt: event=33035
07-14 13:28:34.096  4056  4178 E bt_btif_dm: ### ASSERT : system/bt/btif/src/btif_dm.c line 2983 Callback is NULL (0) ###
07-14 13:28:34.096  4056  4178 W bt_osi_thread: run_thread: thread id 4178, thread name bt_jni_workqueue exited
07-14 13:28:34.097  3707  4312 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{57941ca: PendingIntentRecord{2e8bf3b com.google.android.gms broadcastIntent}}
07-14 13:28:34.098  4056  4173 I bt_core_module: module_clean_up Cleaning up module "stack_config_module"
07-14 13:28:34.098  4056  4173 I bt_core_module: module_clean_up Cleanup of module "stack_config_module" completed
07-14 13:28:34.098  4056  4173 I bt_core_module: module_clean_up Cleaning up module "interop_module"
07-14 13:28:34.098  4056  4173 I bt_core_module: module_clean_up Cleanup of module "interop_module" completed
07-14 13:28:34.098  4056  4173 I bt_core_module: module_clean_up Cleaning up module "btif_config_module"
,07-14 13:28:34.105  4056  4173 I bt_core_module: module_clean_up Cleanup of module "btif_config_module" completed
07-14 13:28:34.106  4056  4173 I bt_core_module: module_clean_up Cleaning up module "bt_utils_module"
07-14 13:28:34.106  4056  4173 I bt_core_module: module_clean_up Cleanup of module "bt_utils_module" completed
,07-14 13:28:34.106  4056  4173 I bt_core_module: module_clean_up Cleaning up module "osi_module"
07-14 13:28:34.106  4056  4177 D bt_osi_alarm: callback_dispatch Callback thread exited
07-14 13:28:34.106  4056  4177 W bt_osi_thread: run_thread: thread id 4177, thread name alarm_dispatcher exited
07-14 13:28:34.107  4056  4176 W bt_osi_thread: run_thread: thread id 4176, thread name alarm_default_ca exited
,07-14 13:28:34.108  4056  4173 I bt_core_module: module_clean_up Cleanup of module "osi_module" completed
07-14 13:28:34.108  4056  4056 I BluetoothServiceJni: cleanupNative: return from cleanup
07-14 13:28:34.108  4056  4056 D DOWNLOADABLE_DB: cleanup
,07-14 13:28:34.113  4056  4056 I art     : System.exit called, status: 0
07-14 13:28:34.113  4056  4056 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-14 13:28:34.120  9513  9599 D BluetoothAdapter: enable()
,07-14 13:28:34.128  4576  6616 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,07-14 13:28:34.128  3707  3937 W ActivityManager: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-14 13:28:34.129  3707  3937 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-14 13:28:34.129  3707  3937 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-14 13:28:34.129  3707  3937 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-14 13:28:34.129  3707  3937 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-14 13:28:34.129  3707  3937 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-14 13:28:34.129  3707  3937 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-14 13:28:34.129  3707  3937 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-14 13:28:34.129  3707  3937 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-14 13:28:34.129  3707  3937 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-14 13:28:34.129  3707  3937 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-14 13:28:34.135  3707  3937 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-14 13:28:34.136  3707  3937 D SecContentProvider: called from com.thaliproject.thalitest
07-14 13:28:34.140  3111  3111 E lowmemorykiller: Error writing /proc/4056/oom_score_adj; errno=22
07-14 13:28:34.140  3707  3802 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
07-14 13:28:34.143  3707  3802 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1656)
07-14 13:28:34.144  3707  3802 W ActivityManager: Application dead when creating service ServiceRecord{41a1417 u0 com.android.bluetooth/.btservice.AdapterService}
07-14 13:28:34.146  3707  3802 I ActivityManager: Process com.android.bluetooth (pid 4056) has died(68,1804)
07-14 13:28:34.146  3707  3802 D ActivityManager: cleanUpApplicationRecord -- 4056
07-14 13:28:34.147  3707  3802 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,07-14 13:28:34.150  3707  3802 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
,07-14 13:28:34.151  3707  3802 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
07-14 13:28:34.151  3707  3802 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:628)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:1674)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:2102)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:2005)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:1165)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:21011)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1516)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1483)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:2561)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:2526)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap12(BluetoothManagerService.java)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:2028)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at android.os.Looper.loop(Looper.java:154)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-14 13:28:34.151  3707  3802 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,07-14 13:28:34.152  3707  4675 W ActivityManager: Spurious death for ProcessRecord{dc08544 0:com.android.bluetooth/1002}, curProc for 4056: null
,07-14 13:28:34.153  4615  4626 D ForegroundUtils: could not check pending caller
,07-14 13:28:34.638  9513  9599 D BluetoothAdapter: enable()
,07-14 13:28:34.655  3707  4679 W ActivityManager: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-14 13:28:34.657  3707  4679 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-14 13:28:34.657  3707  4679 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-14 13:28:34.657  3707  4679 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-14 13:28:34.657  3707  4679 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-14 13:28:34.657  3707  4679 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-14 13:28:34.657  3707  4679 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-14 13:28:34.657  3707  4679 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-14 13:28:34.657  3707  4679 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-14 13:28:34.657  3707  4679 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-14 13:28:34.657  3707  4679 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-14 13:28:34.661  3707  4679 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-14 13:28:34.663  3707  4679 D SecContentProvider: called from com.thaliproject.thalitest
,07-14 13:28:35.088  3707  4313 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-14 13:28:35.167  9513  9599 D BluetoothAdapter: enable()
,07-14 13:28:35.183  3707  4836 W ActivityManager: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-14 13:28:35.186  3707  4836 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-14 13:28:35.186  3707  4836 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-14 13:28:35.186  3707  4836 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-14 13:28:35.186  3707  4836 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-14 13:28:35.186  3707  4836 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-14 13:28:35.186  3707  4836 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-14 13:28:35.186  3707  4836 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-14 13:28:35.186  3707  4836 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-14 13:28:35.186  3707  4836 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-14 13:28:35.186  3707  4836 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-14 13:28:35.189  3707  4836 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-14 13:28:35.191  3707  4836 D SecContentProvider: called from com.thaliproject.thalitest
,07-14 13:28:35.293  4497  4497 D io_stats: !@   8,0 r 25044 2256272 w 4557 197820 d 579 72828 f 1843 1843 iot 10860 10404 th 475940 0 0 pt 0 inp 0 0 196.407
,07-14 13:28:35.695  9513  9599 D BluetoothAdapter: enable()
,07-14 13:28:35.711  3707  3744 W ActivityManager: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-14 13:28:35.713  3707  3744 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-14 13:28:35.713  3707  3744 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-14 13:28:35.713  3707  3744 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-14 13:28:35.713  3707  3744 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-14 13:28:35.713  3707  3744 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-14 13:28:35.713  3707  3744 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-14 13:28:35.713  3707  3744 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-14 13:28:35.713  3707  3744 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-14 13:28:35.713  3707  3744 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-14 13:28:35.713  3707  3744 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-14 13:28:35.717  3707  3744 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-14 13:28:35.719  3707  3744 D SecContentProvider: called from com.thaliproject.thalitest
,07-14 13:28:36.038  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:36.038  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-14 13:28:36.223  9513  9599 D BluetoothAdapter: enable()
,07-14 13:28:36.240  3707  4677 W ActivityManager: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-14 13:28:36.242  3707  4677 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-14 13:28:36.242  3707  4677 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-14 13:28:36.242  3707  4677 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-14 13:28:36.242  3707  4677 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-14 13:28:36.242  3707  4677 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-14 13:28:36.242  3707  4677 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-14 13:28:36.242  3707  4677 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-14 13:28:36.242  3707  4677 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-14 13:28:36.242  3707  4677 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-14 13:28:36.242  3707  4677 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-14 13:28:36.245  3707  4677 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-14 13:28:36.247  3707  4677 D SecContentProvider: called from com.thaliproject.thalitest
,07-14 13:28:36.625  4738  4812 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-14 13:28:36.625  4738  4812 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-14 13:28:36.625  4738  4812 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-14 13:28:36.633  4738  4812 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60113 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-14 13:28:36.751  9513  9599 D BluetoothAdapter: enable()
,07-14 13:28:36.768  3707  4737 W ActivityManager: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-14 13:28:36.770  3707  4737 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-14 13:28:36.770  3707  4737 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-14 13:28:36.770  3707  4737 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-14 13:28:36.770  3707  4737 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-14 13:28:36.770  3707  4737 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-14 13:28:36.770  3707  4737 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-14 13:28:36.770  3707  4737 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-14 13:28:36.770  3707  4737 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-14 13:28:36.770  3707  4737 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
,07-14 13:28:36.770  3707  4737 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-14 13:28:36.773  3707  4737 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-14 13:28:36.775  3707  4737 D SecContentProvider: called from com.thaliproject.thalitest
,07-14 13:28:36.845  3295  3770 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-14 13:28:37.138  3707  3802 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,07-14 13:28:37.279  9513  9599 D BluetoothAdapter: enable()
,07-14 13:28:37.295  3707  4679 W ActivityManager: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-14 13:28:37.297  3707  4679 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-14 13:28:37.297  3707  4679 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-14 13:28:37.297  3707  4679 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-14 13:28:37.297  3707  4679 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-14 13:28:37.297  3707  4679 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-14 13:28:37.297  3707  4679 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-14 13:28:37.297  3707  4679 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-14 13:28:37.297  3707  4679 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-14 13:28:37.297  3707  4679 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-14 13:28:37.298  3707  4679 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-14 13:28:37.301  3707  4679 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-14 13:28:37.303  3707  4679 D SecContentProvider: called from com.thaliproject.thalitest
,07-14 13:28:37.310  3707  3802 D MountService: getExternalStorageMountMode : 3
07-14 13:28:37.310  3707  3802 D MountService: getExternalStorageMountMode : 3
07-14 13:28:37.311  3707  3802 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 1002, packageName : com.android.bluetooth
,07-14 13:28:37.349  9640  9640 E Zygote  : v2
07-14 13:28:37.349  9640  9640 I libpersona: KNOX_SDCARD checking this for 1002
,07-14 13:28:37.349  9640  9640 I libpersona: KNOX_SDCARD not a persona
,07-14 13:28:37.351  9640  9640 E Zygote  : accessInfo : 0
07-14 13:28:37.352  9640  9640 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:37.353  3707  3802 I ActivityManager: Start proc 9640:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-14 13:28:37.354  9640  9640 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.android.bluetooth 
,07-14 13:28:37.393  9640  9640 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:37.394  9640  9640 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:37.398  3707  3743 I ActivityManager: DSS on for com.android.bluetooth and scale is 1.0
,07-14 13:28:37.477  9640  9640 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-14 13:28:37.484  9640  9640 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:37.493  9640  9640 I HeadsetProvider: onCreate
,07-14 13:28:37.506  9640  9640 D BtSettings.ProfileConfig: Adding GattService
07-14 13:28:37.506  9640  9640 D BtSettings.ProfileConfig: Adding HeadsetService
07-14 13:28:37.507  9640  9640 D BtSettings.ProfileConfig: Adding A2dpService
07-14 13:28:37.507  9640  9640 D BtSettings.ProfileConfig: Adding HidService
07-14 13:28:37.507  9640  9640 D BtSettings.ProfileConfig: Adding HealthService
07-14 13:28:37.507  9640  9640 D BtSettings.ProfileConfig: Adding PanService
07-14 13:28:37.507  9640  9640 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-14 13:28:37.507  9640  9640 D BtSettings.ProfileConfig: Adding SapService
07-14 13:28:37.507  9640  9640 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-14 13:28:37.507  9640  9640 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-14 13:28:37.508  9640  9640 D BtSettings.ProfileConfig: Adding HidDevService
07-14 13:28:37.508  9640  9640 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-14 13:28:37.518  3707  3908 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-14 13:28:37.521  3707  3908 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:37.525  3707  4679 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-14 13:28:37.528  3707  4679 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:37.532  3707  4313 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-14 13:28:37.534  3707  4313 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:37.538  3707  3987 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-14 13:28:37.540  3707  3987 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:37.545  3707  3743 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-14 13:28:37.547  3707  3743 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:37.551  3707  4836 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-14 13:28:37.552  3707  4836 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:37.554  3707  4717 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-14 13:28:37.555  3707  4717 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:37.558  3707  3937 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-14 13:28:37.559  3707  3937 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:37.561  3707  3744 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-14 13:28:37.562  3707  3744 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:37.564  3707  4718 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-14 13:28:37.565  3707  4718 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:37.567  3707  4312 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-14 13:28:37.568  3707  4312 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:37.661  9640  9640 D BluetoothAdapterState: make() - Creating AdapterState
,07-14 13:28:37.664  9640  9653 I BluetoothAdapterState: Entering OffState
,07-14 13:28:37.668  9640  9655 W bt_osi_thread: run_thread: thread id 9655, thread name stack_manager started
07-14 13:28:37.668  9640  9655 I bt_core_module: module_init Initializing module "osi_module"
,07-14 13:28:37.668  9640  9655 I bt_core_module: module_init Initialized module "osi_module"
07-14 13:28:37.668  9640  9655 I bt_core_module: module_init Initializing module "bt_utils_module"
07-14 13:28:37.668  9640  9655 I bt_core_module: module_init Initialized module "bt_utils_module"
07-14 13:28:37.668  9640  9655 I bt_core_module: module_init Initializing module "btif_config_module"
,07-14 13:28:37.670  9640  9658 W bt_osi_thread: run_thread: thread id 9658, thread name alarm_default_ca started
,07-14 13:28:37.670  9640  9659 W bt_osi_thread: run_thread: thread id 9659, thread name alarm_dispatcher started
07-14 13:28:37.670  9640  9655 I bt_core_module: module_init Initialized module "btif_config_module"
07-14 13:28:37.670  9640  9655 I bt_core_module: module_init Initializing module "interop_module"
07-14 13:28:37.670  9640  9655 I bt_core_module: module_init Initialized module "interop_module"
07-14 13:28:37.671  9640  9655 I bt_core_module: module_init Initializing module "stack_config_module"
,07-14 13:28:37.672  9640  9655 I bt_core_module: module_init Initialized module "stack_config_module"
,07-14 13:28:37.673  9640  9660 W bt_osi_thread: run_thread: thread id 9660, thread name bt_jni_workqueue started
,07-14 13:28:37.673  9640  9640 I bt_osi_wakelock: wakelock_set_os_callouts set to non-native
07-14 13:28:37.674  9640  9640 W bt_btif : btif_get_adapter_property 2
07-14 13:28:37.674  9640  9640 W bt_btif : btif_get_adapter_property 1
,07-14 13:28:37.675  9640  9660 E BluetoothServiceJni: populateRssiValuesNative
07-14 13:28:37.675  9640  9660 I bt_btif : getModelRssiValues
07-14 13:28:37.675  9640  9660 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
,07-14 13:28:37.678  9640  9640 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-14 13:28:37.680  9640  9640 D BluetoothAdapterService: makeHashMapAvPerformance: Loading from conf
,07-14 13:28:37.696  3707  3802 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,07-14 13:28:37.702  9640  9653 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,07-14 13:28:37.703  9640  9652 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-14 13:28:37.704  9640  9652 D AdapterProvider: query
,07-14 13:28:37.709  9640  9653 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-14 13:28:37.709  9640  9653 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-14 13:28:37.710  3707  3802 D BluetoothManagerService: Ble Turning On/Off, G state: 0, S state: 0
07-14 13:28:37.710  9640  9653 D BluetoothAdapterService: Autoconnection is available 
07-14 13:28:37.710  9640  9653 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
07-14 13:28:37.711  9640  9653 D BluetoothAdapterState: Set Downloadbale DB
07-14 13:28:37.711  9640  9653 D DOWNLOADABLE_DB: initBluetoothDatabase
07-14 13:28:37.712  9640  9653 D DOWNLOADABLE_DB: initBroadcastReceiver
,07-14 13:28:37.715  9640  9653 D DOWNLOADABLE_DB: cleanupLooper
07-14 13:28:37.716  9640  9653 D DOWNLOADABLE_DB: quit init handler
,07-14 13:28:37.720  9640  9652 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@5f626d0
,07-14 13:28:37.721  9640  9652 D BluetoothAdapterService: updateEvent - already set, update
,07-14 13:28:37.722  9640  9652 W BluetoothAdapterService: updateEvent - alreadySet is true
07-14 13:28:37.722  9640  9652 D AdapterProvider: update
,07-14 13:28:37.727  9640  9652 E BluetoothAdapterService: updateEvent - update success 1
,07-14 13:28:37.737  9640  9653 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-14 13:28:37.740  3707  3987 D MountService: getExternalStorageMountMode : 1
07-14 13:28:37.740  3707  3987 D MountService: getExternalStorageMountMode : 3
,07-14 13:28:37.740  3707  3987 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10135, packageName : com.samsung.android.sm.policy
,07-14 13:28:37.761  9662  9662 E Zygote  : v2
07-14 13:28:37.761  9662  9662 I libpersona: KNOX_SDCARD checking this for 10135
07-14 13:28:37.761  9662  9662 I libpersona: KNOX_SDCARD not a persona
,07-14 13:28:37.762  9662  9662 E Zygote  : accessInfo : 0
,07-14 13:28:37.763  9662  9662 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:37.765  9662  9662 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,07-14 13:28:37.768  3707  3987 I ActivityManager: Start proc 9662:com.samsung.android.sm.policy/u0a135 for content provider com.samsung.android.sm.policy/.db.PolicyClientProvider
,07-14 13:28:37.799  9662  9662 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:37.799  9662  9662 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:37.802  3707  4717 I ActivityManager: DSS on for com.samsung.android.sm.policy and scale is 1.0
,07-14 13:28:37.809  9513  9599 D BluetoothAdapter: enable()
,07-14 13:28:37.820  9640  9661 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-14 13:28:37.821  9640  9661 D AdapterProvider: query
,07-14 13:28:37.837  9640  9661 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@d0c5685
,07-14 13:28:37.838  9662  9662 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient_N/lib/arm64
07-14 13:28:37.839  9640  9661 D BluetoothAdapterService: updateEvent - already set, update
07-14 13:28:37.839  9640  9661 W BluetoothAdapterService: updateEvent - alreadySet is true
,07-14 13:28:37.840  9640  9661 D AdapterProvider: update
,07-14 13:28:37.846  9640  9661 E BluetoothAdapterService: updateEvent - update success 1
,07-14 13:28:37.853  3707  4717 W ActivityManager: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-14 13:28:37.854  3707  4717 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-14 13:28:37.854  3707  4717 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-14 13:28:37.854  3707  4717 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-14 13:28:37.854  3707  4717 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-14 13:28:37.854  3707  4717 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-14 13:28:37.854  3707  4717 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-14 13:28:37.854  3707  4717 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-14 13:28:37.854  3707  4717 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-14 13:28:37.854  3707  4717 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-14 13:28:37.855  3707  4717 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-14 13:28:37.856  3707  4717 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-14 13:28:37.857  9662  9662 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-14 13:28:37.857  3707  4717 D SecContentProvider: called from com.thaliproject.thalitest
,07-14 13:28:37.896  9640  9653 D DOWNLOADABLE_DB: Local DB version is = 20160428 SCPM Client DB version is= 20160428
07-14 13:28:37.896  9640  9653 D DOWNLOADABLE_DB: latest polices have already been updated for BT_HFP
,07-14 13:28:37.913  9640  9653 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-14 13:28:37.935  9640  9653 D DOWNLOADABLE_DB: Local DB version is = 20160617 SCPM Client DB version is= 20160617
07-14 13:28:37.935  9640  9653 D DOWNLOADABLE_DB: latest polices have already been updated for BT_BLE
,07-14 13:28:37.952  9640  9653 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-14 13:28:37.974  9640  9653 D DOWNLOADABLE_DB: Local DB version is = 201612050001 SCPM Client DB version is= 201612050001
07-14 13:28:37.974  9640  9653 D DOWNLOADABLE_DB: latest polices have already been updated for BT_A2DP
,07-14 13:28:37.986  9640  9653 D BluetoothSecureManager: getInstant: null
07-14 13:28:37.986  9640  9653 D BluetoothSecureManager: calling getMethod for getService
07-14 13:28:37.986  9640  9653 D BluetoothSecureManager: calling getService
,07-14 13:28:37.988  9640  9653 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@421950b
,07-14 13:28:37.990  3707  4737 D BluetoothSecureManagerService: isSecureModeEnabled
07-14 13:28:37.990  3707  4737 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,07-14 13:28:37.991  9640  9653 D BtConfig.SecureMode: isSecureModeOn:false
07-14 13:28:37.991  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-14 13:28:37.992  9640  9653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,07-14 13:28:37.993  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-14 13:28:37.994  9640  9653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-14 13:28:37.994  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-14 13:28:37.995  9640  9653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-14 13:28:37.996  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-14 13:28:37.997  9640  9653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-14 13:28:37.997  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-14 13:28:37.999  9640  9653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-14 13:28:37.999  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-14 13:28:38.000  9640  9653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-14 13:28:38.000  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-14 13:28:38.001  9640  9653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,07-14 13:28:38.002  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-14 13:28:38.003  9640  9653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
,07-14 13:28:38.003  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-14 13:28:38.004  9640  9653 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-14 13:28:38.004  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
,07-14 13:28:38.006  9640  9653 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
07-14 13:28:38.006  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-14 13:28:38.008  9640  9653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidDevService
,07-14 13:28:38.009  9640  9653 D BluetoothBondStateMachine: make
,07-14 13:28:38.011  9640  9675 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-14 13:28:38.019  9640  9653 I BluetoothAdapterState: Entering PendingCommandState
07-14 13:28:38.020  9640  9640 I BtGatt.JNI: classInitNative(L979): classInitNative: Success!
,07-14 13:28:38.028  9640  9640 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-14 13:28:38.029  9640  9640 D BtGatt.GattService: Received start request. Starting profile...
07-14 13:28:38.029  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:38.029  9640  9640 D BtGatt.GattService: start()
,07-14 13:28:38.031  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:38.031  9640  9640 D BtGatt.AdvertiseManager: advertise manager created
07-14 13:28:38.031  9640  9640 D BtGatt.AdvertiseManager: start
,07-14 13:28:38.038  9640  9640 D BtGatt.ScanManager: start
,07-14 13:28:38.072  9640  9640 D BtGatt.GattService: setGattService(): set to: com.android.bluetooth.gatt.GattService@aeedd32
,07-14 13:28:38.072  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:38.073  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:38.073  9640  9640 D BtGatt.GattService: refreshAbusiveScanPackages
,07-14 13:28:38.075  9640  9640 D DOWNLOADABLE_DB: getAbuseScanPackages
,07-14 13:28:38.091  9640  9640 D BtGatt.GattService: refreshAbusiveScanValue()
,07-14 13:28:38.093  9640  9640 D DOWNLOADABLE_DB: getAbuseMaxScanCount
,07-14 13:28:38.107  9640  9640 D DOWNLOADABLE_DB: getAbuseAccumulatedScanTime
,07-14 13:28:38.122  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:38.123  9640  9640 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
,07-14 13:28:38.123  9640  9640 D BtGatt.GattService: notifyProfileServiceStateChanged
07-14 13:28:38.123  9640  9640 E BluetoothAdapterService: handleMessage() - Message: 1
,07-14 13:28:38.127  9640  9640 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,07-14 13:28:38.128  9640  9640 V BluetoothAdapterState: isTurningOff()=false
07-14 13:28:38.128  9640  9640 V BluetoothAdapterState: isTurningOn()=false
,07-14 13:28:38.129  9640  9640 V BluetoothAdapterState: isBleTurningOn()=true
07-14 13:28:38.129  9640  9640 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:38.130  9640  9653 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,07-14 13:28:38.140  9640  9655 I bt_core_module: module_start_up Starting module "btif_config_module"
07-14 13:28:38.140  9640  9655 I bt_core_module: module_start_up Started module "btif_config_module"
07-14 13:28:38.140  9640  9655 I bt_core_module: module_start_up Starting module "btsnoop_module"
07-14 13:28:38.141  9640  9655 I bt_core_module: module_start_up Started module "btsnoop_module"
07-14 13:28:38.141  9640  9655 I bt_core_module: module_start_up Starting module "hci_module"
07-14 13:28:38.141  9640  9655 I bt_hci  : start_up
07-14 13:28:38.141  9640  9660 W bt_btif : btif_dm_generic_evt: event=33035
,07-14 13:28:38.142  9640  9689 W bt_osi_thread: run_thread: thread id 9689, thread name hci_thread started
,07-14 13:28:38.154  9640  9655 I bt_vendor: alloc value 0xe4fc3d35
07-14 13:28:38.155  9640  9655 I bt_vendor: init
07-14 13:28:38.155  9640  9655 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-14 13:28:38.155  9640  9655 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-14 13:28:38.155  9640  9655 I bt_upio : upio_set_bluetooth_power(on: 0)
07-14 13:28:38.157  9640  9655 I bt_upio : upio_set_bluetooth_power(on: 1)
,07-14 13:28:38.265  9640  9655 D bt_hci  : start_up starting async portion
,07-14 13:28:38.265  9640  9689 I bt_hci  : event_finish_startup
07-14 13:28:38.265  9640  9689 I bt_hci_h4: hal_open
07-14 13:28:38.265  9640  9689 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,07-14 13:28:38.267  9640  9689 I bt_userial_vendor: userial_vendor_open():UART is setup
,07-14 13:28:38.267  9640  9689 I bt_userial_vendor: device fd = 95 open
,07-14 13:28:38.268  9640  9692 W bt_osi_thread: run_thread: thread id 9692, thread name hci_single_chann started
07-14 13:28:38.268  9640  9689 E bt_hwcfg: Start CFG HW, HCI reset
,07-14 13:28:38.272  9640  9689 E bt_hwcfg: Read Local Name after HCI reset
,07-14 13:28:38.296  9640  9689 D bt_hwcfg: Chipset BCM4359C0
07-14 13:28:38.296  9640  9689 D bt_hwcfg: Target name = [BCM4359C0]
,07-14 13:28:38.297  9640  9689 I bt_hwcfg: module_type[semco_b90s_c0].
07-14 13:28:38.297  9640  9689 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
07-14 13:28:38.297  9640  9689 E bt_hwcfg: ORG patchram base 0092
07-14 13:28:38.297  9640  9689 E bt_hwcfg: ORG patchram minor 0143
07-14 13:28:38.297  9640  9689 E bt_hwcfg: fw ver (org)92.143
07-14 13:28:38.297  9640  9689 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
,07-14 13:28:38.306  9640  9689 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-14 13:28:38.310  9640  9689 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,07-14 13:28:38.364  9513  9599 D BluetoothAdapter: enable()
,07-14 13:28:38.375  9640  9652 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,07-14 13:28:38.376  9640  9652 D AdapterProvider: query
,07-14 13:28:38.392  9640  9652 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@93d5bdf
,07-14 13:28:38.395  9640  9652 D BluetoothAdapterService: updateEvent - already set, update
07-14 13:28:38.396  9640  9652 W BluetoothAdapterService: updateEvent - alreadySet is true
,07-14 13:28:38.397  9640  9652 D AdapterProvider: update
,07-14 13:28:38.402  9640  9652 E BluetoothAdapterService: updateEvent - update success 1
,07-14 13:28:38.410  3707  4717 W ActivityManager: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-14 13:28:38.411  3707  4717 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-14 13:28:38.411  3707  4717 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9513, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-14 13:28:38.411  3707  4717 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-14 13:28:38.411  3707  4717 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-14 13:28:38.411  3707  4717 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-14 13:28:38.411  3707  4717 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-14 13:28:38.411  3707  4717 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-14 13:28:38.411  3707  4717 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-14 13:28:38.411  3707  4717 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-14 13:28:38.411  3707  4717 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-14 13:28:38.413  3707  4717 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-14 13:28:38.414  3707  4717 D SecContentProvider: called from com.thaliproject.thalitest
,07-14 13:28:38.657  3707  4313 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{80369f7: PendingIntentRecord{fc79064 com.google.android.gms broadcastIntent}}
,07-14 13:28:38.660  4576  6622 W NearbyMessages: Runnable[ScanComplete] not posted since EventLoop is destroyed
,07-14 13:28:38.862  3707  3863 D SamsungAlarmManager: Expired : 4
,07-14 13:28:38.867  3707  3863 D SamsungAlarmManager: setInexact Intent (T:1/F:8/AC:false) 20170804T170408 - CU:1000/CP:3707
07-14 13:28:38.867  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T133456, SetElapsed=577224, nowELAPSED=199983
,07-14 13:28:38.868  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170714T132900, SetElapsed=221116, nowELAPSED=199983
07-14 13:28:38.868  3707  3863 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@a22f288 alarm=Alarm{74f22cd type 2 when 163199 android}
,07-14 13:28:38.872  3707  3927 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
,07-14 13:28:38.873  3707  3863 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@c5a567a alarm=Alarm{da7782 type 2 when 199978 android}
07-14 13:28:38.876  4225  4225 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-14 13:28:38.877  3707  3863 V SamsungAlarmManager: Sending to uid : 1000 action=com.mobeam.barcodeService.UPLOAD_BEAM_RECORD alarm=Alarm{dfaae93 type 1 when 1500031661586 com.mobeam.barcodeService}
,07-14 13:28:38.877  4225  4225 I wpa_supplicant: P2P: Current p2p state = IDLE
07-14 13:28:38.884  3707  3863 D MountService: getExternalStorageMountMode : 1
07-14 13:28:38.885  3707  3863 D MountService: getExternalStorageMountMode : 3
07-14 13:28:38.885  3707  3863 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.mobeam.barcodeService
07-14 13:28:38.885  4225  4225 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-14 13:28:38.922  9693  9693 E Zygote  : v2
,07-14 13:28:38.923  9693  9693 I libpersona: KNOX_SDCARD checking this for 1000
07-14 13:28:38.923  9693  9693 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:38.924  9693  9693 E Zygote  : accessInfo : 0
07-14 13:28:38.924  9640  9689 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-14 13:28:38.924  9693  9693 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
07-14 13:28:38.924  9640  9689 I bt_hwcfg: FW Download delta = 652082
07-14 13:28:38.924  9640  9689 D bt_hwcfg: Settlement delay -- 100 ms
07-14 13:28:38.925  9640  9689 I bt_hwcfg: Setting fw settlement delay to 100 
07-14 13:28:38.926  9693  9693 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.mobeam.barcodeService 
07-14 13:28:38.927  9513  9599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:38.927  9513  9599 E io.jxcore.node.ConnectivityMonitorTest: BT is not enabled after 5s!
07-14 13:28:38.928  3707  3863 I ActivityManager: Start proc 9693:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
07-14 13:28:38.930  3707  3707 D SamsungAlarmManager: setInexact Listener (T:2/F:0/AC:false) 20170714T142545 - CU:1000/CP:3707
07-14 13:28:38.931  9513  9577 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,07-14 13:28:38.933  3707  3955 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170714T132853 - CU:1000/CP:3707
,07-14 13:28:38.933  3707  3955 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132853, SetElapsed=214998, nowELAPSED=200048
,07-14 13:28:38.935  3707  3927 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170714T133046 - CU:1000/CP:3707
,07-14 13:28:38.938  9513  9577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:38.941  3707  4717 D WifiService: setWifiEnabled: false pid=9513, uid=10033
,07-14 13:28:38.941  3707  4717 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-14 13:28:38.942  3707  4717 D WifiControlHistoryProvider: query
,07-14 13:28:38.960  3707  4015 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
07-14 13:28:38.961  9693  9693 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:38.962  9693  9693 D ActivityThread: Added TimaKeyStore provider
07-14 13:28:38.962  3707  3707 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,07-14 13:28:38.962  3707  4717 D WifiNative-wlan0: callSECApiVoid - ID [312]
,07-14 13:28:38.964  3707  4717 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-14 13:28:38.965  3707  4737 I ActivityManager: DSS on for com.mobeam.barcodeService and scale is 1.0
07-14 13:28:38.969  3707  4717 D SecContentProvider: called from android.uid.system:1000
,07-14 13:28:38.970  3707  4717 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-14 13:28:38.974  3707  4717 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-14 13:28:38.975  3707  3926 D SecContentProvider: insert(), uri = 2
07-14 13:28:38.976  3707  3926 D SecContentProvider: called from android.uid.system:1000
,07-14 13:28:38.976  3707  3926 D SecContentProvider: insert(), uri = 2
,07-14 13:28:38.977  3707  3926 D SecContentProvider: called from android.uid.system:1000
,07-14 13:28:38.978  3707  3927 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-14 13:28:38.980  3707  3927 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@f3c89ce
,07-14 13:28:38.980  5368  5368 D [SAUI]  : Global::recovered::false
07-14 13:28:38.981  3707  3927 D WifiStateMachine: isFindLocationId() - Location Id : 1
07-14 13:28:38.981  3707  3927 D WifiStateMachine: ConnectedState - exit() - stopLearning id : 1
07-14 13:28:38.981  3707  3927 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-14 13:28:38.982  3707  3927 D SLocation: system
07-14 13:28:38.982  3707  3927 D SLocation: stopLearning ID = 1
07-14 13:28:38.982  3707  3927 D SLocation: setLearningStatus ID = 1 / status = false
07-14 13:28:38.984  3707  3927 D SecContentProvider: insert(), uri = 2
07-14 13:28:38.984  5368  5368 D WaitQueueForNetworkActivate: notifyNetworkActivated
07-14 13:28:38.985  5368  5368 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
07-14 13:28:38.986  3707  3927 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:38.986  3707  3927 D WifiStateMachine: Wifi got Disconnected in connectedstate, Send provisioning intent mAutoRoamingfalse
,07-14 13:28:38.989  3707  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiStateMachine$ConnectedState.exit:11809 com.android.internal.util.StateMachine$SmHandler.invokeExitMethods:1009 com.android.internal.util.StateMachine$SmHandler.performTransitions:865 com.android.internal.util.StateMachine$SmHandler.handleMessage:809 
,07-14 13:28:38.990  3707  3927 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-14 13:28:38.993  3707  3932 D DhcpClient: doQuit
07-14 13:28:38.993  3707  3932 D ApfFilter: (wlan0): shutting down
07-14 13:28:38.993  3707  5103 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@4139144
07-14 13:28:38.993  9693  9693 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
07-14 13:28:38.994  3707  5103 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@ef35429
,07-14 13:28:38.996  3707  3923 D WifiP2pService: InactiveState{ what=143375 }
07-14 13:28:38.997  3707  3923 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-14 13:28:38.998  3707  5103 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@e1a2cba
07-14 13:28:38.998  9601  9601 I WifiApBroadcastReceiver: onReceive: action com.samsung.intent.action.START_PROVISIONING userID :0
,07-14 13:28:39.000  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=-2ms what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-14 13:28:39.001  3707  3958 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-14 13:28:39.001  3707  3958 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 12
,07-14 13:28:39.002  3707  3958 V NetworkStats: updateIfacesLocked()
07-14 13:28:39.002  3707  3958 V NetworkStats: performPollLocked(flags=0x1)
07-14 13:28:39.002  3707  3958 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:39.003  3707  4718 I WifiService: Wi-Fi Sharing settings has not been accessed
07-14 13:28:39.007  3707  4015 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
,07-14 13:28:39.012  3707  3927 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
,07-14 13:28:39.012  3707  3927 I WifiConnectivityManager: Set WiFi disabled
07-14 13:28:39.012  3707  3927 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@7962b18
07-14 13:28:39.013  3707  3927 I WifiStateMachine: deinitGeofence
07-14 13:28:39.013  9693  9693 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:39.015  3707  3958 V NetworkStats: performPollLocked() took 13ms
07-14 13:28:39.015  3707  3958 D NtpTrustedTime: currentTimeMillis() cache hit
,07-14 13:28:39.020  4043  4043 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-14 13:28:39.021  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-14 13:28:39.022  3707  3927 D SLocation: stopGeofence ID = 1
07-14 13:28:39.022  3707  3707 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-14 13:28:39.022  3707  3707 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-14 13:28:39.022  3707  3707 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
07-14 13:28:39.022  3707  3707 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-14 13:28:39.023  3707  3958 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
07-14 13:28:39.023  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.023  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-14 13:28:39.023  3707  3958 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [] ]
07-14 13:28:39.023  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.023  3707  3958 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-14 13:28:39.023  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.024  3707  3958 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.024  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [] ]
07-14 13:28:39.024  3707  3958 D ConnectivityService: sending notification LOST for NetworkRequest [ id=7, legacyType=-1, [] ]
07-14 13:28:39.024  3707  3954 I WifiHs20Service: Message received 5007
07-14 13:28:39.025  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:39.025  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:39.027  3707  4013 D DnsEventListenerService: Logging 25 results for netId 502
07-14 13:28:39.024  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.028  3707  3783 D MountService: getExternalStorageMountMode : 1
07-14 13:28:39.028  3707  3783 D MountService: getExternalStorageMountMode : 3
07-14 13:28:39.028  3707  3783 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10106, packageName : com.enhance.gameservice
07-14 13:28:39.028  3707  3958 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-14 13:28:39.029  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.029  3707  3958 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.029  4283  4404 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [false]
07-14 13:28:39.029  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.031  3707  3958 D ConnectivityService: sending notification LOST for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.031  4283  4418 D PdnController: handleMessage: what 106
07-14 13:28:39.031  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:39.031  4283  4418 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [false]
07-14 13:28:39.031  3707  3958 D ConnectivityService: sending notification LOST for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:39.032  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.032  3707  3958 D ConnectivityService: sending notification LOST for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.032  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:39.032  3707  3958 D ConnectivityService: sending notification LOST for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:39.033  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:39.033  3707  3802 D EntConnectivity: Not allowed due to - mEnabled false
07-14 13:28:39.033  3707  3958 D ConnectivityService: sending notification LOST for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:39.034  4283  4404 D GeolocationController: WIFI : onLost
07-14 13:28:39.034  3707  3958 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.034  3707  5099 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-14 13:28:39.034  3707  4024 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.035  3707  5099 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: unregister CaptivePortalReceiver
07-14 13:28:39.035  3707  4024 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-14 13:28:39.035  3707  4024 D Ethernet: evalRequest
07-14 13:28:39.035  3707  4024 D Ethernet:   done
07-14 13:28:39.035  3707  3923 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.035  3707  3923 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-14 13:28:39.035  3707  3923 D WIFI_P2P: evalRequest
07-14 13:28:39.035  3707  3923 D WIFI_P2P:   done
07-14 13:,28:39.036  4043  4043 D PhoneSwitcherNetworkRequstListener: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.036  4283  4418 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [false]
07-14 13:28:39.036  4043  4043 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-14 13:28:39.036  4043  4043 D PhoneSwitcherNetworkRequstListener: evalRequest
07-14 13:28:39.036  4043  4043 D PhoneSwitcherNetworkRequstListener:   done
07-14 13:28:39.036  4283  4418 D ResipRegiMgr: handleMessage(): 3
07-14 13:28:39.036  4283  4418 D RegiMgrBase: handleMessage: what 3
,07-14 13:28:39.050  9640  9689 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,07-14 13:28:39.056  3239  3239 E audit   : type=1320 audit(1500031719.048:231): 
07-14 13:28:39.060  9711  9711 E Zygote  : v2
,07-14 13:28:39.061  9711  9711 I libpersona: KNOX_SDCARD checking this for 10106
,07-14 13:28:39.061  9711  9711 I libpersona: KNOX_SDCARD not a persona
,07-14 13:28:39.062  9711  9711 E Zygote  : accessInfo : 0
07-14 13:28:39.063  9711  9711 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:39.065  9711  9711 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.enhance.gameservice 
,07-14 13:28:39.067  3707  3783 I ActivityManager: Start proc 9711:com.enhance.gameservice/u0a106 for broadcast com.enhance.gameservice/.GameServiceReceiver
,07-14 13:28:39.068  3707  4015 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-14 13:28:39.069  3707  3707 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
07-14 13:28:39.075  3707  5103 D DhcpClient: onQuitting
07-14 13:28:39.078  3239  3239 E audit   : type=1320 audit(1500031719.068:232): 
,07-14 13:28:39.078  3295  3781 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-14 13:28:39.086  3707  4675 I ActivityManager: KPU : put [com.samsung.android.sm.provider] : 28312 K
,07-14 13:28:39.086  3707  4675 I ActivityManager: Killing 4511:com.samsung.android.sm.provider/1000 (adj 906): DHA:empty #33
07-14 13:28:39.091  3239  3239 E audit   : type=1320 audit(1500031719.078:233): 
07-14 13:28:39.092  9711  9711 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:39.092  9711  9711 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:39.103  3239  3239 E audit   : type=1320 audit(1500031719.088:234): 
,07-14 13:28:39.104  3295  3781 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-14 13:28:39.106  3707  4836 I ActivityManager: DSS on for com.enhance.gameservice and scale is 1.0
07-14 13:28:39.107  3707  3958 D ConnectivityService: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
07-14 13:28:39.108  3707  3958 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-14 13:28:39.112  3707  3802 D EntConnectivity: Not allowed due to - mEnabled false
,07-14 13:28:39.114  3707  3927 E SLocation: pendingIntent set to null
,07-14 13:28:39.114  3707  3927 D SLocation: setStatus ID = 1 / status = 0
07-14 13:28:39.114  3707  3927 D SLocation: updateSession : trigger = false
07-14 13:28:39.114  3707  3927 D SLocation: updateSession : mSessionStatus = 0
07-14 13:28:39.114  3707  3927 D WifiStateMachine:  stopGeofence() - id : 1
07-14 13:28:39.115  3707  3927 D wifi    : android_net_wifi_reset_alert_handler = 0x70ffa4abc0
07-14 13:28:39.115  3707  3927 E WifiHAL : failed to request reset; result = -95
,07-14 13:28:39.115  3707  3927 D wifi    : android_net_wifi_reset_log_handler = 0x70ffa4abc0
07-14 13:28:39.115  3707  3927 I WifiHAL : Failed to remove command 1: 0x0
07-14 13:28:39.115  3707  3927 D WifiHAL : Success to clear alerthandler
07-14 13:28:39.116  3295  3781 D CommandListener: Clearing all IP addresses on wlan0
07-14 13:28:39.116  3707  4238 D SLocation: Session stopped
07-14 13:28:39.116  3707  4238 D SLocation: triggerAlarm
07-14 13:28:39.117  3707  4238 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / op:PendingIntent{9f4867c: PendingIntentRecord{dff3b05 android broadcastIntent}}
07-14 13:28:39.117  3707  4238 D SLocation: All alarm stopped
,07-14 13:28:39.119  3707  3927 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-14 13:28:39.120  3707  3927 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.120  3707  3927 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-14 13:28:39.120  3707  3927 D WIFI_UT : evalRequest
07-14 13:28:39.120  3707  3927 D WIFI_UT :   done
07-14 13:28:39.120  3707  3927 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:39.120  3707  3923 D WifiP2pService: InactiveState{ what=131204 }
07-14 13:28:39.120  3707  3927 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-14 13:28:39.120  3707  3927 D WIFI    : evalRequest
07-14 13:28:39.120  3707  3927 D WIFI    :   needNetworkFor
07-14 13:28:39.120  3707  3923 D WifiP2pService: P2pEnabledState{ what=131204 }
07-14 13:28:39.121  3707  4679 D ActivityManager: cleanUpApplicationRecord -- 4511
,07-14 13:28:39.127  3707  3955 I WifiScanningService: wifi driver unloaded
,07-14 13:28:39.128  3707  3955 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.scanner.SupplicantWifiScannerImpl$2@6acbee7
,07-14 13:28:39.129  3707  3707 D RttService: SCAN_AVAILABLE : 1
,07-14 13:28:39.130  3707  3957 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-14 13:28:39.130  3707  3927 E WifiConnectivityManager: SingleScanListener onFailure: reason: -1 description: Scan was interrupted
07-14 13:28:39.131  4225  4225 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
07-14 13:28:39.131  4225  4225 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
07-14 13:28:39.134  3707  3707 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-14 13:28:39.135  3707  3923 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-14 13:28:39.135  3707  3707 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = true
,07-14 13:28:39.136  3707  9727 I ApplicationPolicy: updateDataUsageMap
07-14 13:28:39.136  9711  9711 W System  : ClassLoader referenced unknown path: /system/app/GameOptimizer/lib/arm64
,07-14 13:28:39.142  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-14 13:28:39.144  3707  3914 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
07-14 13:28:39.144  3707  3914 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
07-14 13:28:39.145  3707  3707 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-14 13:28:39.145  3707  3707 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
07-14 13:28:39.145  3707  3915 I KnoxVpnEngineService: vpn handle : Message received
07-14 13:28:39.145  3707  3915 I KnoxVpnEngineService: vpn handle : Message received
07-14 13:28:39.145  3707  3707 D Tethering: Tethering got CONNECTIVITY_ACTION
07-14 13:28:39.145  3707  3915 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = true
07-14 13:28:39.145  3707  3960 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
07-14 13:28:39.145  3707  3960 D Tethering: MasterInitialState.processMessage what=327683
,07-14 13:28:39.152  3707  3918 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
07-14 13:28:39.152  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
,07-14 13:28:39.152  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
,07-14 13:28:39.152  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
,07-14 13:28:39.152  9640  9689 I bt_hwcfg: vendor lib fwcfg completed
07-14 13:28:39.152  9640  9689 I bt_vendor: firmware callback
07-14 13:28:39.152  3707  3918 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
07-14 13:28:39.153  9640  9689 I bt_hci  : firmware_config_callback
07-14 13:28:39.153  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:39.153  3707  3707 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
,07-14 13:28:39.153  3707  3707 V MARsPolicyManager: DataConnection: false
07-14 13:28:39.153  3707  4238 D SLocation: checkWifiInfo
07-14 13:28:39.153  3707  4238 W SLocation: No Active Data Connection
07-14 13:28:39.153  3707  4238 W SLocation: No Active Data Connection
07-14 13:28:39.154  9640  9655 I bt_core_module: module_start_up Started module "hci_module"
07-14 13:28:39.156  3707  3918 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
07-14 13:28:39.157  3707  4040 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-14 13:28:39.157  9640  9728 W bt_osi_thread: run_thread: thread id 9728, thread name bt_workqueue started
07-14 13:28:39.159  9640  9728 I bt_core_module: module_init Initializing module "bte_logmsg_module"
07-14 13:28:39.159  9640  9728 I bt_core_module: module_init Initialized module "bte_logmsg_module"
07-14 13:28:39.159  9640  9660 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-14 13:28:39.161  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 9640
07-14 13:28:39.161  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
07-14 13:28:39.161  9640  9660 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-14 13:28:39.161  9640  9660 W bt_btif : get_secure_storage_key - ss_is_supported = 1
07-14 13:28:39.162  9640  9660 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
07-14 13:28:39.162  9640  9660 W bt_btif : btif_dm_generic_evt: event=33035
07-14 13:28:39.162  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,07-14 13:28:39.163  3707  4040 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-14 13:28:39.167  5059  5059 I CastMediaRouteProvider: Network connectivity changed
,07-14 13:28:39.169  8861  8861 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
07-14 13:28:39.170  8861  8861 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
,07-14 13:28:39.172  3707  3927 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170714T132841 - CU:1000/CP:3707
07-14 13:28:39.172  3707  3927 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132841, SetElapsed=202246, nowELAPSED=200287
,07-14 13:28:39.172  8913  8913 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@8a068c4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-14 13:28:39.175  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-14 13:28:39.181  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-14 13:28:39.181  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-14 13:28:39.206  4069  4348 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
,07-14 13:28:39.214  3707  3803 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
07-14 13:28:39.216  3295  3771 I Netd    : Destroyed 15 sockets on 192.168.1.105 in 1.2 ms
07-14 13:28:39.216  9640  9660 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-14 13:28:39.216  4576  6628 V NativeCrypto: Read error: ssl=0x712d046700: I/O error during system call, Software caused connection abort
07-14 13:28:39.216  9711  9711 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-14 13:28:39.217  4615  4626 D ForegroundUtils: could not check pending caller
07-14 13:28:39.219  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 9640
07-14 13:28:39.219  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
07-14 13:28:39.219  9513  9513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-14 13:28:39.220  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-14 13:28:39.220  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:39.220  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:39.220  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-14 13:28:39.220  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-14 13:28:39.220  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-14 13:28:39.220  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-14 13:28:39.220  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-14 13:28:39.220  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-14 13:28:39.221  4576  6628 V NativeCrypto: SSL shutdown failed: ssl=0x712d046700: I/O error during system call, Broken pipe
07-14 13:28:39.221  9513  9513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-14 13:28:39.221  9513  9513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
07-14 13:28:39.223  3707  3923 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-14 13:28:39.226  8861  8861 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 2
07-14 13:28:39.227  3707  3987 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{223c532: PendingIntentRecord{6fa1b1e com.google.android.gms broadcastIntent}}
07-14 13:28:39.227  3707  3803 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-14 13:28:39.227  3707  3803 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-14 13:28:39.227  3707  3803 D WifiDisplayController: disconnect
07-14 13:28:39.227  3707  3803 D WifiDisplayAdapter: onFeatureStateChanged empty
07-14 13:28:39.227  3707  3803 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-14 13:28:39.228  3707  3923 D SecContentProvider: insert(), uri = 2
07,-14 13:28:39.229  4576  6628 E GCM     : Wifi connection closed with errorCode 20
07-14 13:28:39.232  3239  3239 E audit   : type=1320 audit(1500031719.218:235): 
07-14 13:28:39.233  3707  3923 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:39.233  3707  3803 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: false, roaming: false, metered: false]
07-14 13:28:39.233  3707  3923 D WifiP2pService: P2pDisablingState
07-14 13:28:39.234  3707  3923 D WifiP2pService: P2pDisablingState{ what=147458 }
07-14 13:28:39.234  3707  3923 D WifiP2pService: p2p socket connection lost
07-14 13:28:39.235  3707  3923 D SecContentProvider: insert(), uri = 2
07-14 13:28:39.236  8913  8913 I NetworkConnectivity: Network state changed: null
07-14 13:28:39.238  3707  3923 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:39.239  3707  3927 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-14 13:28:39.242  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-14 13:28:39.242  3707  4015 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
07-14 13:28:39.243  3239  3239 E audit   : type=1320 audit(1500031719.228:236): 
07-14 13:28:39.244  4753  4753 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-14 13:28:39.245  3707  3927 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-14 13:28:39.247  3707  3923 D WifiP2pService: P2pDisabledState
07-14 13:28:39.247  3707  3923 D WifiP2pService: P2pDisabledState{ what=143375 }
07-14 13:28:39.248  3707  3923 D WifiP2pService: DefaultState{ what=143375 }
07-14 13:28:39.249  3707  3707 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-14 13:28:39.250  4225  4225 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-14 13:28:39.250  3707  3927 D SecContentProvider: insert(), uri = 2
07-14 13:28:39.251  3707  3927 D SecContentProvider: called from android.uid.system:1000
,07-14 13:28:39.253  3707  3707 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-14 13:28:39.253  3707  3707 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-14 13:28:39.254  3707  3954 I WifiHs20Service: Message received 5007
07-14 13:28:39.257  4043  4043 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
07-14 13:28:39.259  3707  3927 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-14 13:28:39.260  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-14 13:28:39.262  3707  3783 D MountService: getExternalStorageMountMode : 3
07-14 13:28:39.262  3707  3783 D MountService: getExternalStorageMountMode : 3
07-14 13:28:39.262  3707  3783 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 5017, packageName : com.samsung.android.radiobasedlocation
07-14 13:28:39.264  8861  8861 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
07-14 13:28:39.267  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-14 13:28:39.272  9513  9513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-14 13:28:39.273  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-14 13:28:39.273  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:39.273  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:39.273  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-14 13:28:39.273  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-14 13:28:39.273  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-14 13:28:39.273  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-14 13:28:39.273  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-14 13:28:39.273  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-14 13:28:39.274  9513  9513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-14 13:28:39.274  9513  9513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
07-14 13:28:39.276  8913  8913 I NetworkPolicyMonitor: Download-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
07-14 13:28:39.277  3295  3781 E Netd    : netlink response contains error (No such file or directory)
07-14 13:28:39.281  3707  3958 D ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-14 13:28:39.284  8913  8913 I NetworkPolicyMonitor: Stream-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
,07-14 13:28:39.286  3707  3958 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED
,07-14 13:28:39.289  3707  3958 D ConnectivityService: ignoring duplicate network state non-change
07-14 13:28:39.290  9734  9734 E Zygote  : v2
07-14 13:28:39.290  9734  9734 I libpersona: KNOX_SDCARD checking this for 5017
07-14 13:28:39.290  9734  9734 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:39.291  9734  9734 E Zygote  : accessInfo : 0
07-14 13:28:39.292  9734  9734 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
07-14 13:28:39.294  9734  9734 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.radiobasedlocation 
07-14 13:28:39.296  3295  3774 D EnterpriseController: netId is 0
07-14 13:28:39.296  3295  3774 D Netd    : getNetworkForDns: using netid 0 for uid 10001
07-14 13:28:39.297  3295  3774 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-14 13:28:39.298  3707  3783 I ActivityManager: Start proc 9734:com.samsung.android.radiobasedlocation/5017 for broadcast com.samsung.android.radiobasedlocation/.RblServiceReceiver
07-14 13:28:39.301  3707  3707 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-14 13:28:39.301  3707  3707 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-14 13:28:39.301  3707  3707 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-14 13:28:39.302  3707  3707 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
07-14 13:28:39.302  3707  4238 D SLocation: checkWifiInfo
07-14 13:28:39.302  3707  4015 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-14 13:28:39.303  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135173 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-14 13:28:39.303  3707  3954 I WifiHs20Service: Message received 5011
07-14 13:28:39.305  3707  4040 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-14 13:28:39.305  3295  3771 D Netd    : Iface p2p0 link up
07-14 13:28:39.308  3707  3801 D Tethering: interfaceLinkStateChanged p2p0, true
07-14 13:28:39.308  3707  3801 D Tethering: interfaceStatusChanged p2p0, true
,07-14 13:28:39.311  3707  3743 I ActivityManager: KPU : put [com.samsung.android.sm.devicesecurity] : 27772 K
07-14 13:28:39.311  3707  3743 I ActivityManager: Killing 6892:com.samsung.android.sm.devicesecurity/5012 (adj 906): DHA:empty #33
07-14 13:28:39.311  3707  4040 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-14 13:28:39.315  9734  9734 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:39.315  9734  9734 D ActivityThread: Added TimaKeyStore provider
07-14 13:28:39.321  3707  3908 I ActivityManager: DSS on for com.samsung.android.radiobasedlocation and scale is 1.0
07-14 13:28:39.325  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:39.338  5059  5499 W MdnsClient_Cast: Multicast lock held. Releasing. Subtypes:"805741C9"
07-14 13:28:39.339  3707  4716 D ActivityManager: cleanUpApplicationRecord -- 6892
07-14 13:28:39.339  9734  9734 I art     : Starting a blocking GC AddRemoveAppImageSpace
07-14 13:28:39.340  9734  9734 W System  : ClassLoader referenced unknown path: /system/priv-app/RadioBasedLocation/lib/arm64
07-14 13:28:39.341  4615  4626 D ForegroundUtils: could not check pending caller
07-14 13:28:39.341  8913  8913 I DevicePlayback: Got network change: mobile=falsewifi=false
07-14 13:28:39.341  8913  8913 I DevicePlayback: Disabling Woodstock in 200000ms
07-14 13:28:39.347  5059  5499 W MdnsClient: unicast receiver thread is already dead.
07-14 13:28:39.350  9734  9734 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:39.354  9734  9734 I [RBL] PathProvider: @onCreate
,07-14 13:28:39.357  9734  9734 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-14 13:28:39.361  3707  4677 I ActivityManager: KPU : put [com.samsung.android.themecenter] : 27028 K
07-14 13:28:39.361  3707  4677 I ActivityManager: Killing 8848:com.samsung.android.themecenter/1000 (adj 906): DHA:empty #33
,07-14 13:28:39.364  4225  4225 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-14 13:28:39.369  3707  4677 D MountService: getExternalStorageMountMode : 1
07-14 13:28:39.369  3707  4677 D MountService: getExternalStorageMountMode : 3
07-14 13:28:39.369  3707  4677 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.diagmonagent
,07-14 13:28:39.369  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
07-14 13:28:39.369  9640  9660 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,07-14 13:28:39.370  9640  9749 W bt_osi_thread: run_thread: thread id 9749, thread name module_wrapper started
,07-14 13:28:39.370  9640  9749 I bt_core_module: module_start_up Starting module "controller_module"
07-14 13:28:39.371  4225  4225 E wpa_supplicant: can't get BSS information
07-14 13:28:39.371  4225  4225 I wpa_supplicant: CTRL_IFACE: Detach monitor that cannot receive messages: /data/misc/wifi/sockets/wpa_ctrl_3707-2\x00
07-14 13:28:39.371  4225  4225 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.E6.C2 reason=3 locally_generated=1
,07-14 13:28:39.375  5105  9732 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
07-14 13:28:39.375  5105  9732 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-14 13:28:39.375  5105  9732 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
07-14 13:28:39.375  5105  9732 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
07-14 13:28:39.375  5105  9732 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
07-14 13:28:39.375  5105  9732 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
07-14 13:28:39.375  5105  9732 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
07-14 13:28:39.375  5105  9732 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-14 13:28:39.375  5105  9732 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
07-14 13:28:39.375  5105  9732 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
07-14 13:28:39.375  5105  9732 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
07-14 13:28:39.375  5105  9732 E         : 	at java.lang.Thread.run(Thread.java:762)
07-14 13:28:39.375  5105  9732 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-14 13:28:39.375  5105  9732 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
07-14 13:28:39.375  5105  9732 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
07-14 13:28:39.375  5105  9732 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.intern,al.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:175)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
07-14 13:28:39.375  5105  9732 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
07-14 13:28:39.375  5105  9732 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
07-14 13:28:39.375  5105  9732 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
07-14 13:28:39.375  5105  9732 E         : 	... 9 more
07-14 13:28:39.375  5105  9732 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-14 13:28:39.375  5105  9732 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-14 13:28:39.375  5105  9732 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-14 13:28:39.375  5105  9732 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
07-14 13:28:39.375  5105  9732 E         : 	... 26 more
07-14 13:28:39.375  5105  9732 E         : 
,07-14 13:28:39.378  5105  9732 E         : Unable to fetch advertisement frequency.
07-14 13:28:39.378  5105  9732 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-14 13:28:39.378  5105  9732 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
07-14 13:28:39.378  5105  9732 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
07-14 13:28:39.378  5105  9732 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
07-14 13:28:39.378  5105  9732 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
07-14 13:28:39.378  5105  9732 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
07-14 13:28:39.378  5105  9732 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-14 13:28:39.378  5105  9732 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
07-14 13:28:39.378  5105  9732 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
07-14 13:28:39.378  5105  9732 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
07-14 13:28:39.378  5105  9732 E         : 	at java.lang.Thread.run(Thread.java:762)
07-14 13:28:39.378  5105  9732 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-14 13:28:39.378  5105  9732 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
07-14 13:28:39.378  5105  9732 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
07-14 13:28:39.378  5105  9732 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(R,outeSelector.java:175)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
07-14 13:28:39.378  5105  9732 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
07-14 13:28:39.378  5105  9732 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
07-14 13:28:39.378  5105  9732 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
07-14 13:28:39.378  5105  9732 E         : 	... 9 more
07-14 13:28:39.378  5105  9732 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-14 13:28:39.378  5105  9732 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-14 13:28:39.378  5105  9732 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-14 13:28:39.378  5105  9732 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
07-14 13:28:39.378  5105  9732 E         : 	... 26 more
07-14 13:28:39.378  5105  9732 E         : 
07-14 13:28:39.380  3295  3771 D Netd    : Iface wlan0 link up
,07-14 13:28:39.381  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:28:39.381  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
,07-14 13:28:39.389  9750  9750 E Zygote  : v2
07-14 13:28:39.389  9750  9750 I libpersona: KNOX_SDCARD checking this for 1000
07-14 13:28:39.389  9750  9750 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:39.389  9750  9750 E Zygote  : accessInfo : 0
07-14 13:28:39.389  9750  9750 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
07-14 13:28:39.390  3707  4677 I ActivityManager: Start proc 9750:com.sec.android.diagmonagent/1000 for broadcast com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
07-14 13:28:39.390  9750  9750 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.diagmonagent 
,07-14 13:28:39.401  3707  3922 D ActivityManager: cleanUpApplicationRecord -- 8848
,07-14 13:28:39.403  4615  4627 D ForegroundUtils: could not check pending caller
07-14 13:28:39.404  9750  9750 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:39.405  9750  9750 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:39.406  3707  4679 I ActivityManager: DSS on for com.sec.android.diagmonagent and scale is 1.0
,07-14 13:28:39.418  4069  4198 D vol.MediaSessions: onQueueChanged com.google.android.music []
,07-14 13:28:39.420  9750  9750 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,07-14 13:28:39.429  9750  9750 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:39.442  9750  9750 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,07-14 13:28:39.454  9640  9749 I bt_core_module: module_start_up Started module "controller_module"
,07-14 13:28:39.455  9640  9749 W bt_osi_thread: run_thread: thread id 9749, thread name module_wrapper exited
,07-14 13:28:39.466  9750  9750 E SQLiteLog: (1) no such column: currentid
,07-14 13:28:39.467  9750  9750 E DIAGMON_AGENT: [llllIIIIlllIIIlIllIl(906/lllIlIlIIIllIIlIllIl)] android.database.sqlite.SQLiteException: no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1
07-14 13:28:39.467  9750  9750 E DIAGMON_AGENT: #################################################################
07-14 13:28:39.467  9750  9750 E DIAGMON_AGENT: Error Code : 1 (SQLITE_ERROR)
07-14 13:28:39.467  9750  9750 E DIAGMON_AGENT: Caused By : SQL(query) error or missing database.
07-14 13:28:39.467  9750  9750 E DIAGMON_AGENT: 	(no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1)
07-14 13:28:39.467  9750  9750 E DIAGMON_AGENT: #################################################################
,07-14 13:28:39.475  9640  9660 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
,07-14 13:28:39.477  9513  9599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-14 13:28:39.477  9513  9599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-14 13:28:39.477  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:39.477  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:39.477  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-14 13:28:39.477  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-14 13:28:39.477  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-14 13:28:39.477  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-14 13:28:39.477  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-14 13:28:39.477  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-14 13:28:39.480  9640  9660 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
,07-14 13:28:39.480  9640  9660 W bt_btif : btif_dm_generic_evt: event=33035
,07-14 13:28:39.480  9513  9577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:39.481  9640  9660 D bt_hci  : do_postload posting postload work item
07-14 13:28:39.481  3707  4737 D WifiService: setWifiEnabled: true pid=9513, uid=10033
07-14 13:28:39.481  9640  9660 E bt_btif_sock: btif_sock_init: !vhci_init
07-14 13:28:39.481  9640  9660 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:227 ##
07-14 13:28:39.481  9640  9689 I bt_hci  : event_postload
,07-14 13:28:39.481  9640  9689 D bt_hwcfg: hw_sco_config
07-14 13:28:39.481  9640  9689 I bt_hwcfg: I2SPCM config {0x1, 0x0, 0x0, 0x1}
07-14 13:28:39.482  9640  9689 I bt_vendor: sco_config_cb
07-14 13:28:39.482  9640  9689 I bt_hci  : sco_config_callback postload finished.
07-14 13:28:39.482  3707  4737 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-14 13:28:39.482  3707  4737 D WifiControlHistoryProvider: query
07-14 13:28:39.483  9640  9660 I         : iop_db_open: iop_db_open status 0
07-14 13:28:39.484  9640  9660 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
07-14 13:28:39.484  9640  9660 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
07-14 13:28:39.484  9640  9660 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
07-14 13:28:39.484  9640  9660 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Grace SWB-B90S eLNA-0092
07-14 13:28:39.484  9640  9660 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0092.0143_semco.hcd
07-14 13:28:39.484  9640  9660 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
07-14 13:28:39.484  9640  9660 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = true
07-14 13:28:39.485  9640  9660 E BluetoothAdapterState: stateChangeCallback : 1
07-14 13:28:39.485  4225  4225 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
07-14 13:28:39.485  9640  9653 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
07-14 13:28:39.486  9750  9750 E SQLiteLog: (1) table profilelist has no column named currentid
07-14 13:28:39.487  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-14 13:28:39.487  3707  4737 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-14 13:28:39.487  9640  9653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.487  9640  9653 D DOWNLOADABLE_DB: refreshDbFile
,07-14 13:28:39.487  9640  9653 D BluetoothServiceJni: refreshDownloadableDbFileNative:
07-14 13:28:39.487  9640  9653 I bt_btif : refreshDownloadableDbFile
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: Error inserting number=0 len=0 profilename3=Mformation notiretrycount=0 currentid=-1 size=0 oplevel=0 serviceid= appid=0 profilename2=dm-Server notievent=0 sessionid=null profilename1=api-server status=0 uictype=0 text= holdingid=-1 sessionsavestate=0 profileindex=0 opmode= result=0 pushjobid= notiuievent=0
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: android.database.sqlite.SQLiteException: table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: #################################################################
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: Error Code : 1 (SQLITE_ERROR)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: Caused By : SQL(query) error or missing database.
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	(table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?))
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: #################################################################
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1005)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.prepare(SQLiteConnection.java:570)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.prepare(SQLiteSession.java:588)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.database.sqlite.SQLiteProgram.<init>(SQLiteProgram.java:59)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.<init>(SQLiteStatement.java:31)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1771)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1643)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:667)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:399)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:116)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:60)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1032)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5885)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap3(ActivityThread.java)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1703)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:154)
07-14 13:28:39.487  9750  9750 E SQLite,Database: 	at android.app.ActivityThread.main(ActivityThread.java:6692)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1468)
07-14 13:28:39.487  9750  9750 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1358)
07-14 13:28:39.487  3707  4737 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:39.488  3707  4737 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-14 13:28:39.489  9640  9653 I         : iop_db_open: iop_db_open status 0
07-14 13:28:39.490  9640  9653 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-14 13:28:39.490  9640  9653 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-14 13:28:39.490  3707  4737 I WifiService: Wi-Fi Sharing settings has not been accessed
07-14 13:28:39.492  3707  4737 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-14 13:28:39.492  3707  3926 D SecContentProvider: insert(), uri = 2
07-14 13:28:39.493  3707  3926 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:39.493  3707  3926 D SecContentProvider: insert(), uri = 2
07-14 13:28:39.494  3707  3926 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:39.496  9640  9653 D BluetoothAdapterService: Autoconnection is available 
07-14 13:28:39.496  9640  9653 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
07-14 13:28:39.496  9640  9653 I BluetoothAdapterState: Entering BleOnState
07-14 13:28:39.498  3707  3802 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-14 13:28:39.499  3707  3802 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-14 13:28:39.500  3707  3802 D SecContentProvider: called from android.uid.system:1000
,07-14 13:28:39.501  9640  9652 E BluetoothBondStateMachine: initStateMachine
07-14 13:28:39.501  9640  9653 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,07-14 13:28:39.503  9640  9653 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-14 13:28:39.503  9640  9653 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-14 13:28:39.503  3707  3802 D BluetoothManagerService: Turning On/Off, G state: 0, S state: 0, mBLE count: 0, s BLE count: 0
07-14 13:28:39.503  9640  9653 D BluetoothAdapterService: Autoconnection is available 
07-14 13:28:39.503  9640  9653 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
07-14 13:28:39.504  9640  9653 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-14 13:28:39.504  9640  9653 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
07-14 13:28:39.504  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-14 13:28:39.508  9750  9750 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(64/onCreate)] nStatus : 0
,07-14 13:28:39.509  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-14 13:28:39.512  9750  9750 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(77/onCreate)] DiagMon DM Application Start !
,07-14 13:28:39.512  4069  4348 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:39.512  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-14 13:28:39.512  4069  4348 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
07-14 13:28:39.513  9640  9689 I bt_hwcfg: SCO PCM configure {0x0, 0x1, 0x0, 0x0, 0x0}
,07-14 13:28:39.513  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-14 13:28:39.513  9750  9750 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-14 13:28:39.513  9750  9750 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
07-14 13:28:39.513  3707  3707 D BluetoothPhoneService: Bluetooth Adapter state : 11
,07-14 13:28:39.514  9640  9689 I bt_vendor: low_power_mode_cb
,07-14 13:28:39.516  3707  3707 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,07-14 13:28:39.516  3707  3707 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:39.516  3707  3707 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
07-14 13:28:39.516  9640  9640 D HeadsetService: Received start request. Starting profile...
07-14 13:28:39.517  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.519  9601  9601 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:39.522  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:39.522  9601  9601 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-14 13:28:39.524  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-14 13:28:39.525  3295  3771 D Netd    : Iface wlan0 link up
07-14 13:28:39.525  3295  3771 D Netd    : Iface wlan0 link up
07-14 13:28:39.525  4225  4225 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-14 13:28:39.526  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:28:39.526  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
07-14 13:28:39.527  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:28:39.527  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
07-14 13:28:39.529  9640  9640 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
07-14 13:28:39.530  3707  4677 I ActivityManager: KPU : put [com.samsung.svoice.sync] : 21192 K
07-14 13:28:39.530  3707  4677 I ActivityManager: Killing 8876:com.samsung.svoice.sync/u0a40 (adj 906): DHA:empty #33
,07-14 13:28:39.533  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-14 13:28:39.534  9640  9640 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-14 13:28:39.534  9640  9640 D HeadsetStateMachine: make
07-14 13:28:39.535  3707  3965 D MountService: getExternalStorageMountMode : 1
07-14 13:28:39.535  3707  3965 D MountService: getExternalStorageMountMode : 3
07-14 13:28:39.535  3707  3965 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.app.RilErrorNotifier
07-14 13:28:39.537  9640  9640 E HeadsetStateMachine: # of Max HF connection is 3
,07-14 13:28:39.554  9766  9766 E Zygote  : v2
07-14 13:28:39.554  9766  9766 I libpersona: KNOX_SDCARD checking this for 1000
,07-14 13:28:39.554  9766  9766 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:39.555  9766  9766 E Zygote  : accessInfo : 0
07-14 13:28:39.555  9766  9766 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
07-14 13:28:39.556  9766  9766 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.app.RilErrorNotifier 
07-14 13:28:39.557  3707  3965 I ActivityManager: Start proc 9766:com.sec.app.RilErrorNotifier/1000 for broadcast com.sec.app.RilErrorNotifier/.PhoneErrorReceiver
07-14 13:28:39.562  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-14 13:28:39.575  9766  9766 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-14 13:28:39.575  9766  9766 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:39.581  3707  3908 I ActivityManager: DSS on for com.sec.app.RilErrorNotifier and scale is 1.0
07-14 13:28:39.581  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-14 13:28:39.587  3707  4716 D ActivityManager: cleanUpApplicationRecord -- 8876
,07-14 13:28:39.595  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-14 13:28:39.604  9766  9766 W System  : ClassLoader referenced unknown path: /system/priv-app/PhoneErrService/lib/arm64
,07-14 13:28:39.606  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-14 13:28:39.606  9640  9653 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-14 13:28:39.606  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
07-14 13:28:39.607  9640  9653 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
07-14 13:28:39.607  9640  9653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-14 13:28:39.608  4615  4627 D ForegroundUtils: could not check pending caller
07-14 13:28:39.608  9640  9640 I DualScoManager: Instantiating Dual Sco Manager
,07-14 13:28:39.609  9640  9640 I DualScoManager: Set HeadsetServiceHelper
,07-14 13:28:39.609  9640  9640 I DualScoManager: setNotificationManager
07-14 13:28:39.610  9640  9640 I DualScoManager: setAudioManager
07-14 13:28:39.611  9640  9640 D BluetoothAtMessage: createCMTIContentObservers
07-14 13:28:39.613  9640  9653 I BluetoothAdapterState: Entering PendingCommandState
,07-14 13:28:39.621  9766  9766 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:39.623  9640  9640 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@85afacf
07-14 13:28:39.623  9640  9689 I bt_hwcfg: SCO PCM data format {0x0, 0x0, 0x3, 0x0, 0x0}
,07-14 13:28:39.624  9640  9640 I HeadsetService: getHeadsetDB(true) - 44:78:3E:94:4A:XX, 300, 1
,07-14 13:28:39.624  9640  9640 I DualScoManager: setSystemAudioInbandSupported : true
07-14 13:28:39.625  9640  9640 I HeadsetStateMachine: isAutoAppInstalled : false
07-14 13:28:39.625  9640  9640 I HeadsetStateMachine: IBR : true (SysA : 1 / DB : 1)
07-14 13:28:39.626  9640  9689 I bt_hwcfg: sco I2S/PCM config result 0 [0-Success, 1-Fail]
07-14 13:28:39.626  9640  9689 I bt_vendor: sco_audiostate_cb(status: 0)
07-14 13:28:39.626  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:39.627  9640  9640 D DOWNLOADABLE_DB: getNotAllowedVoiceRecognitionDeviceList
,07-14 13:28:39.628  9766  9766 I PhoneErrorReceiver: onReceive
,07-14 13:28:39.636  9415  9415 I usagelog: received in receiver
07-14 13:28:39.636  9415  9415 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-14 13:28:39.637  9415  9415 I KnoxUsageLogPro: premStatus:2
,07-14 13:28:39.638  9415  9415 I KnoxUsageLogPro: isEulaShown : false
07-14 13:28:39.638  9415  9415 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-14 13:28:39.641  9640  9765 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,07-14 13:28:39.645  3707  4313 I ActivityManager: KPU : put [com.sec.android.app.sbrowser] : 21712 K
07-14 13:28:39.645  3707  4313 I ActivityManager: Killing 8929:com.sec.android.app.sbrowser/u0a134 (adj 906): DHA:empty #33
,07-14 13:28:39.652  9640  9765 D HeadsetStateMachine: Clear mHeadsetBrsf
07-14 13:28:39.652  9640  9765 D HeadsetStateMachine: map size, before remove : 0
07-14 13:28:39.652  9640  9765 D HeadsetStateMachine: map size, after remove: 0
07-14 13:28:39.652  9640  9765 D HeadsetStateMachine: connectNextConnectingDevice(false) : null
,07-14 13:28:39.657  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.657  9640  9640 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
07-14 13:28:39.657  9640  9640 D HeadsetService: notifyProfileServiceStateChanged
,07-14 13:28:39.660  9640  9640 D A2dpService: Received start request. Starting profile...
07-14 13:28:39.661  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:39.661  9640  9640 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-14 13:28:39.674  5059  5059 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-14 13:28:39.675  3707  3987 D ActivityManager: cleanUpApplicationRecord -- 8929
,07-14 13:28:39.677  5059  7939 I iu.UploadsManager: num queued entries: 0
07-14 13:28:39.678  5059  7939 I iu.UploadsManager: num updated entries: 0
07-14 13:28:39.678  4615  4626 D ForegroundUtils: could not check pending caller
07-14 13:28:39.679  3707  3927 D wifi    : In wifi stop Hal
07-14 13:28:39.679  3707  3927 D wifi    : halHandle = 0x711f76e7e0, mVM = 0x712d090300, mCls = 0x10100e
07-14 13:28:39.679  3707  4224 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-14 13:28:39.679  3707  4224 D WifiHAL : Got a signal to exit!!!
07-14 13:28:39.679  3707  4224 I WifiHAL : Exit wifi_event_loop
07-14 13:28:39.680  3707  3927 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-14 13:28:39.680  3707  3927 E WifiHAL : Event processing terminated
,07-14 13:28:39.682  5059  7939 I iu.SyncManager: NEXT; no task
,07-14 13:28:39.685  3707  3707 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-14 13:28:39.685  3707  3953 D HS20StateMachine: WIFI_STATE_DISABLED
07-14 13:28:39.685  3707  3953 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
,07-14 13:28:39.686  3707  3707 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-14 13:28:39.686  3707  3954 I WifiHs20Service: Message received 5011
,07-14 13:28:39.688  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-14 13:28:39.689  3295  3771 D Netd    : Iface p2p0 link down
07-14 13:28:39.690  3707  3801 D Tethering: interfaceLinkStateChanged p2p0, false
07-14 13:28:39.690  3707  3801 D Tethering: interfaceStatusChanged p2p0, false
,07-14 13:28:39.692  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-14 13:28:39.697  3707  3707 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-14 13:28:39.697  3707  4238 D SLocation: checkWifiInfo
,07-14 13:28:39.697  3707  4040 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-14 13:28:39.699  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-14 13:28:39.700  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-14 13:28:39.701  4576  5084 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-14 13:28:39.701  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
07-14 13:28:39.705  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:39.709  3707  4040 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-14 13:28:39.710  3707  3987 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:39.710  9640  9640 I Avrcp   : No of Audio players :: 1
07-14 13:28:39.710  9640  9640 I Avrcp   : App Package name is GM
,07-14 13:28:39.724  9640  9640 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,07-14 13:28:39.727  9640  9640 I Avrcp   : No of Video players :: 2
07-14 13:28:39.727  9640  9640 I Avrcp   : Video App Package name is VP
,07-14 13:28:39.732  9640  9640 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-14 13:28:39.732  9640  9640 I Avrcp   : Video App Package name is others
,07-14 13:28:39.734  3707  4836 D MountService: getExternalStorageMountMode : 1
07-14 13:28:39.734  3707  4836 D MountService: getExternalStorageMountMode : 3
07-14 13:28:39.734  3707  4836 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10041, packageName : com.osp.app.signin
,07-14 13:28:39.741  9640  9640 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-14 13:28:39.741  9640  9640 I Avrcp   : Add tempPlayer
07-14 13:28:39.741  9640  9640 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-14 13:28:39.741  9640  9640 V Avrcp   : no_of_players : 4
07-14 13:28:39.741  9640  9640 I Avrcp   : Total no of players: 4
07-14 13:28:39.741  9640  9640 V Avrcp   : Samsung player is the 1st player
,07-14 13:28:39.742  9640  9640 D Avrcp   : Compose Browsing Service Candidate
,07-14 13:28:39.743  9640  9640 D Avrcp   : ResolveInfo info ResolveInfo{4bd68e1 com.android.bluetooth/.a2dpsink.mbs.A2dpMediaBrowserService m=0x108000}
07-14 13:28:39.743  9640  9640 D Avrcp   : ResolveInfo info ResolveInfo{9a06606 com.google.android.music/.browse.MediaBrowserService m=0x108000}
07-14 13:28:39.744  9640  9640 D Avrcp   : Initialize Media Controller
,07-14 13:28:39.744  3707  3927 D wifi    : In wifi cleaned up handler
,07-14 13:28:39.744  3707  3927 I WifiHAL : Internal cleanup completed
,07-14 13:28:39.746  9640  9640 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,07-14 13:28:39.751  9640  9640 E Avrcp   : getActiveSessions
07-14 13:28:39.751  9640  9640 D Avrcp   : pick active media Controller
07-14 13:28:39.751  9640  9640 D Avrcp   : Get the active Media Controller 
,07-14 13:28:39.753  9640  9640 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-14 13:28:39.753  9640  9640 D A2dpStateMachine: make
,07-14 13:28:39.755  9780  9780 E Zygote  : v2
07-14 13:28:39.755  9780  9780 I libpersona: KNOX_SDCARD checking this for 10041
07-14 13:28:39.755  9780  9780 I libpersona: KNOX_SDCARD not a persona
,07-14 13:28:39.755  9640  9786 W bt_osi_thread: run_thread: thread id 9786, thread name media_worker started
07-14 13:28:39.755  3707  4836 I ActivityManager: Start proc 9780:com.osp.app.signin/u0a41 for broadcast com.osp.app.signin/.OspReceiver
,07-14 13:28:39.755  9640  9640 E bt_btif : warning : media task started media_task_refcnt 1 
07-14 13:28:39.755  9640  9640 W bt_btif : btif_ar_init
07-14 13:28:39.756  9780  9780 E Zygote  : accessInfo : 0
07-14 13:28:39.757  9640  9660 W bt_btif : SETUP CHANNEL SERVER 0
07-14 13:28:39.757  9780  9780 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:39.759  9780  9780 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.osp.app.signin 
07-14 13:28:39.760  9640  9640 E A2dpStateMachine: isDualPlayEnabled : Dual Play not supported
,07-14 13:28:39.761  9640  9783 D A2dpStateMachine: Enter Disconnected: -2
07-14 13:28:39.764  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.764  9640  9640 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
07-14 13:28:39.764  9640  9640 D A2dpService: notifyProfileServiceStateChanged
07-14 13:28:39.765  9640  9640 I BluetoothHidServiceJni: classInitNative: succeeds
,07-14 13:28:39.768  9640  9640 D HidService: Received start request. Starting profile...
07-14 13:28:39.769  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.769  9640  9640 D HidService: setHidService(): set to: null
07-14 13:28:39.769  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.769  9640  9640 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
07-14 13:28:39.769  9640  9640 D HidService: notifyProfileServiceStateChanged
,07-14 13:28:39.771  9640  9640 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-14 13:28:39.774  9640  9640 D HealthService: Received start request. Starting profile...
07-14 13:28:39.774  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:39.779  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:39.779  9640  9640 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
07-14 13:28:39.779  9640  9640 D HealthService: notifyProfileServiceStateChanged
,07-14 13:28:39.780  9640  9640 I BluetoothPanServiceJni: classInitNative(L139): succeeds
,07-14 13:28:39.783  9640  9640 D PanService: Received start request. Starting profile...
07-14 13:28:39.784  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.784  9640  9640 D BluetoothPanServiceJni: initializeNative(L144): pan
,07-14 13:28:39.789  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.789  9640  9640 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
07-14 13:28:39.789  9640  9640 D PanService: notifyProfileServiceStateChanged
,07-14 13:28:39.790  3707  4718 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170714T135839 - CU:10124/CP:4958
,07-14 13:28:39.792  9640  9640 D BluetoothMapService: Received start request. Starting profile...
07-14 13:28:39.793  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:28:39.798  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.798  9640  9640 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
07-14 13:28:39.798  9640  9640 D BluetoothMapService: notifyProfileServiceStateChanged
07-14 13:28:39.798  9640  9640 D HeadsetStateMachine: Proxy object connected
,07-14 13:28:39.801  9640  9640 V SapService: SapBinder()
,07-14 13:28:39.802  9780  9780 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:39.802  9780  9780 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:39.803  9640  9640 D SapService: Received start request. Starting profile...
,07-14 13:28:39.804  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.804  9640  9640 V SapService: start()
07-14 13:28:39.805  9640  9640 D SapService: Disable sap : false
,07-14 13:28:39.805  3707  4836 I ActivityManager: DSS on for com.osp.app.signin and scale is 1.0
,07-14 13:28:39.817  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.817  9640  9640 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
07-14 13:28:39.817  9640  9640 D SapService: notifyProfileServiceStateChanged
07-14 13:28:39.818  9640  9640 V BluetoothHidDevServiceJni: classInitNative: done
07-14 13:28:39.822  9640  9640 D HidDevService: Received start request. Starting profile...
07-14 13:28:39.822  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.822  9640  9640 D HidDevService: start()
07-14 13:28:39.822  9640  9640 V BluetoothHidDevServiceJni: initNative enter
07-14 13:28:39.822  9640  9640 V BluetoothHidDevServiceJni: initNative done
07-14 13:28:39.822  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:39.822  9640  9640 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Message sending
07-14 13:28:39.822  9640  9640 D HidDevService: notifyProfileServiceStateChanged
07-14 13:28:39.823  9640  9640 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:39.823  9640  9640 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
07-14 13:28:39.823  9640  9640 V BluetoothAdapterState: isTurningOff()=false
07-14 13:28:39.823  9640  9640 V BluetoothAdapterState: isTurningOn()=true
07-14 13:28:39.823  9640  9640 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:39.823  9640  9640 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:39.826  9640  9640 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-14 13:28:39.826  9640  9640 D A2dpService: A2dpService - WIFI_STATE_DISABLED
07-14 13:28:39.826  9640  9640 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:39.826  9640  9640 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
07-14 13:28:39.827  9640  9640 V BluetoothAdapterState: isTurningOff()=false
07-14 13:28:39.826  9640  9765 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-14 13:28:39.827  9640  9640 V BluetoothAdapterState: isTurningOn()=true
07-14 13:28:39.827  9640  9640 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:39.827  9640  9640 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:39.827  9640  9640 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:39.827  9640  9640 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
07-14 13:28:39.827  9640  9640 V BluetoothAdapterState: isTurningOff()=false
07-14 13:28:39.827  9640  9640 V BluetoothAdapterState: isTurningOn()=true
07-14 13:28:39.827  9640  9640 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:39.827  9640  9640 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:39.827  9640  9765 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-14 13:28:39.827  9640  9640 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:39.827  9640  9640 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
07-14 13:28:39.827  9640  9640 V BluetoothAdapterState: isTurningOff()=false
07-14 13:28:39.827  9640  9640 V BluetoothAdapterState: isTurningOn()=true
07-14 13:28:39.827  9640  9640 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:39.827  9640  9640 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:39.827  9640  9765 D HeadsetStateMachine: Disconnected process message: 1,1, size: 0
07-14 13:28:39.828  9640  9765 E HeadsetStateMachine: Unknown message: 11
07-14 13:28:39.829  9640  9640 D BluetoothUtils: readSalesCode :: sales code is XEO
07-14 13:28:39.829  9640  9640 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:39.829  9640  9640 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
07-14 13:28:39.829  9640  9640 V BluetoothAdapterState: isTurningOff()=false
07-14 13:28:39.829  9640  9640 V BluetoothAdapterState: isTurningOn()=true
07-14 13:28:39.829  9640  9640 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:39.829  9640  9640 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:39.829  9640  9640 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:39.829  9640  9640 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
07-14 13:28:39.829  9640  9640 V BluetoothAdapterState: isTurningOff()=false
07-14 13:28:39.829  9640  9640 V BluetoothAdapterState: isTurningOn()=true
07-14 13:28:39.829  9640  9640 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:39.829  9640  9640 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:39.830  9640  9640 E BluetoothAdapterService: handleMessage() - Message: 1
,07-14 13:28:39.830  9640  9640 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
07-14 13:28:39.830  9640  9640 V BluetoothAdapterState: isTurningOff()=false
07-14 13:28:39.830  9640  9640 V BluetoothAdapterState: isTurningOn()=true
07-14 13:28:39.830  9640  9640 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:39.830  9640  9640 V BluetoothAdapterState: isBleTurningOff()=false
07-14 13:28:39.830  9640  9640 E BluetoothAdapterService: handleMessage() - Message: 1
07-14 13:28:39.830  9640  9640 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Before synchronized
07-14 13:28:39.830  9640  9640 V BluetoothAdapterState: isTurningOff()=false
07-14 13:28:39.830  9640  9640 V BluetoothAdapterState: isTurningOn()=true
07-14 13:28:39.830  9640  9640 V BluetoothAdapterState: isBleTurningOn()=false
07-14 13:28:39.830  9640  9640 V BluetoothAdapterState: isBleTurningOff()=false
,07-14 13:28:39.831  9640  9640 I BluetoothA2dpServiceJni: Attempting to set busy level
07-14 13:28:39.831  9640  9653 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,07-14 13:28:39.833  9640  9653 E BluetoothServiceJni: enableBrEdrNative:
07-14 13:28:39.833  9640  9653 I bt_btif : enable_bredr
,07-14 13:28:39.834  9640  9660 W bt_btif : btif_dm_generic_evt: event=33035
,07-14 13:28:39.836  9640  9660 W bt_btif : btif_dm_generic_evt: event=33035
,07-14 13:28:39.838  9640  9660 W bt_btif : IsSoftphone: 
07-14 13:28:39.838  9640  9660 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
07-14 13:28:39.838  9640  9660 W bt_btif : btif_dm_generic_evt: event=33035
07-14 13:28:39.839  9640  9728 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
,07-14 13:28:39.842  9640  9660 E BluetoothServiceJni: populateRssiValuesNative
07-14 13:28:39.842  9640  9660 I bt_btif : getModelRssiValues
07-14 13:28:39.842  9640  9660 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
07-14 13:28:39.847  9640  9728 D CODEC_IF_MOD: codec_open: codec_open
07-14 13:28:39.847  9640  9728 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
07-14 13:28:39.847  9640  9728 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
07-14 13:28:39.847  9640  9728 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
07-14 13:28:39.847  9640  9728 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-14 13:28:39.847  9640  9728 D CODEC_IF: codec_if_close: codec_if_close hdl -730394620
07-14 13:28:39.847  9640  9728 D CODEC_IF_MOD: codec_close: codec_close
07-14 13:28:39.847  9640  9728 D CODEC_IF_MOD: codec_close: freed apt-x encoder
07-14 13:28:39.847  9640  9728 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
07-14 13:28:39.847  9640  9728 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,07-14 13:28:39.851  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:39.856  9640  9728 D CODEC_IF_SSHD: codec_open: codec_open
07-14 13:28:39.856  9640  9728 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
07-14 13:28:39.856  9640  9728 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
07-14 13:28:39.856  9640  9728 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-14 13:28:39.856  9640  9728 D CODEC_IF: codec_if_close: codec_if_close hdl -1006228096
07-14 13:28:39.856  9640  9728 D CODEC_IF_SSHD: codec_close: codec_close
07-14 13:28:39.856  9640  9728 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
07-14 13:28:39.856  9640  9728 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
07-14 13:28:39.856  9640  9728 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
,07-14 13:28:39.858  9640  9660 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-14 13:28:39.859  9640  9660 E bt_btif : btif_handle_bluetooth_enable_evt
,07-14 13:28:39.859  9640  9660 E bt_btif : ANT+ socket does not initialize.
,07-14 13:28:39.861  9640  9802 W bt_osi_thread: run_thread: thread id 9802, thread name btif_sock started
07-14 13:28:39.861  9640  9660 E BluetoothAdapterState: stateChangeCallback : 17
07-14 13:28:39.861  9640  9660 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
07-14 13:28:39.861  9640  9653 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,07-14 13:28:39.863  9640  9653 D BluetoothAdapterProperties: ScanMode =  20
07-14 13:28:39.864  9640  9653 D BluetoothAdapterProperties: State =  11
,07-14 13:28:39.866  9640  9728 D CODEC_IF_SSHD2: codec_open: codec_open
07-14 13:28:39.866  9640  9728 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
07-14 13:28:39.866  9640  9728 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
07-14 13:28:39.866  9640  9728 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-14 13:28:39.866  9640  9728 D CODEC_IF: codec_if_close: codec_if_close hdl -979730432
07-14 13:28:39.866  9640  9728 D CODEC_IF_SSHD2: codec_close: codec_close
07-14 13:28:39.866  9640  9728 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
,07-14 13:28:39.866  9640  9728 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
07-14 13:28:39.867  9640  9660 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
07-14 13:28:39.867  9640  9660 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
07-14 13:28:39.867  9640  9660 E bt_btif : no av control block available at state:3
07-14 13:28:39.867  9640  9660 E bt_btif : no av control block available at state:3
07-14 13:28:39.867  9640  9660 E bt_btif : no av control block available at state:2
07-14 13:28:39.867  9640  9660 E bt_btif : warning : no command pending, ignore ack
07-14 13:28:39.867  9640  9660 E bt_btif : no av control block available at state:3
07-14 13:28:39.867  9640  9660 E bt_btif : no av control block available at state:2
07-14 13:28:39.867  9640  9660 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
07-14 13:28:39.867  9640  9786 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
07-14 13:28:39.867  9640  9786 E bt_btif : warning : no command pending, ignore ack
07-14 13:28:39.867  3707  3965 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
07-14 13:28:39.869  3707  3965 D SecContentProvider: called from android.uid.bluetooth:1002
07-14 13:28:39.869  9640  9728 D CODEC_IF_MOD: codec_open: codec_open
07-14 13:28:39.869  9640  9728 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
07-14 13:28:39.869  9640  9728 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
07-14 13:28:39.869  9640  9728 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
07-14 13:28:39.869  9640  9728 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-14 13:28:39.869  9640  9728 D CODEC_IF: codec_if_close: codec_if_close hdl -730394620
07-14 13:28:39.869  9640  9728 D CODEC_IF_MOD: codec_close: codec_close
07-14 13:28:39.869  9640  9728 D CODEC_IF_MOD: codec_close: freed apt-x encoder
07-14 13:28:39.869  9640  9728 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
07-14 13:28:39.869  9640  9728 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
07-14 13:28:39.871  9640  9728 D CODEC_IF_SSHD: codec_open: codec_open
07-14 13:28:39.871  9640  9728 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
07-14 13:28:39.871  9640  9728 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
07-14 13:28:39.871  9640  9728 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-14 13:28:39.871  9640  9728 D CODEC_IF: codec_if_close: codec_if_close hdl -1006228096
07-14 13:28:39.871  9640  9728 D CODEC_IF_SSHD: codec_close: codec_close
07-14 13:28:39.871  9640  9728 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
07-14 13:28:39.871  9640  9728 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
07-14 13:28:39.871  9640  9728 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
07-14 13:28:39.872  3707  3987 D SecContentProvider: insert(), uri = 2
07-14 13:28:39.872  9640  9728 D CODEC_IF_SSHD2: codec_open: codec_open
07-14 13:28:39.872  9640  9728 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
07-14 13:28:39.872  9640  9728 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
07-14 13:28:39.872  9640  9728 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-14 13:28:39.872  9640  9728 D CODEC_IF: codec_if_close: codec_if_close hdl -979730432
07-14 13:28:39.872  9640  9728 D CODEC_IF_SSHD2: codec_close: codec_close
07-14 13:28:39.873  9640  9728 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
07-14 13:28:39.873  3707  3987 D SecContentProvider: called from android.uid.bluetooth:1002
07-14 13:28:39.873  9640  9660 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
07-14 13:28:39.873  9640  9660 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
07-14 13:28:39.873  9640  9660 E bt_btif : no av control block available at state:3
07-14 13:28:39.873  9640  9660 E bt_btif : no av control block available at state:3
07-14 ,13:28:39.873  9640  9660 E bt_btif : no av control block available at state:2
07-14 13:28:39.873  9640  9660 E bt_btif : Adding UUID=0xommand pending, ignore ack
07-14 13:28:39.873  9640  9660 E bt_btif : no av control block available at state:3
07-14 13:28:39.873  9640  9660 E bt_btif : no av control block available at state:2
07-14 13:28:39.873  9640  9660 W bt_btif : btif_media_task_aa_stop_tx media_alarm is not TA_AV_REG chars saved)
07-14 13:28:39.873  9640  9786 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
07-14 13:28:39.873  9640  9786 E bt_btif : warning : no command , is_orig 0nore ack
07-14 13:28:39.874  9640  9653 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-14 13:28:39.874  9640  9653 D BluetoothAdapterService: [VendorCapa] prevState: 11, newState: 12
07-14 13:28:39.875  9640  9653 I bt_btif : vsc_getvendorcapabilities
07-14 13:28:39.875  9640  9653 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-14 13:28:39.881  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135179 arg1=184 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-14 13:28:39.883  4069  4218 D BluetoothMap: onBluetoothStateChange: up=true
07-14 13:28:39.884  9780  9780 I art     : Starting a blocking GC AddRemoveAppImageSpace
07-14 13:28:39.884  9640  9653 D BluetoothAdapterService: Autoconnection is available 
07-14 13:28:39.884  9640  9653 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-14 13:28:39.884  9640  9653 D BluetoothAdapterService: starting service from this receiver
07-14 13:28:39.887  9780  9780 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Dream/lib/arm64
07-14 13:28:39.887  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
07-14 13:28:39.890  9640  9660 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-14 13:28:39.890  9640  9660 D BluetoothPanServiceJni: control_state_callback(L64): state:0, local_role:3, ifname:bt-pan
,07-14 13:28:39.892  9513  9513 D BluetoothAdapter: STATE_ON
07-14 13:28:39.895  9513  9513 D BluetoothAdapter: STATE_ON
07-14 13:28:39.896  9513  9513 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
07-14 13:28:39.901  9640  9640 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
07-14 13:28:39.901  9513  9513 D BluetoothAdapter: STATE_ON
07-14 13:28:39.901  9640  9640 I BluetoothPbapService: Handler(): got msg=1
,07-14 13:28:39.902  9513  9513 D BluetoothAdapter: STATE_ON
07-14 13:28:39.904  9513  9513 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,07-14 13:28:39.909  9640  9804 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-14 13:28:39.911  9780  9780 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-14 13:28:39.912  9513  9513 D BluetoothAdapter: STATE_ON
07-14 13:28:39.913  9640  9653 I BluetoothAdapterState: Entering OnState
,07-14 13:28:39.915  4069  6039 D BluetoothAdapter: onBluetoothStateChange: up=true
07-14 13:28:39.915  4069  6039 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-14 13:28:39.916  9640  9652 D BluetoothAdapter: onBluetoothStateChange: up=true
07-14 13:28:39.916  9640  9652 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-14 13:28:39.918  9601  9612 D BluetoothAdapter: onBluetoothStateChange: up=true
07-14 13:28:39.918  9601  9612 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-14 13:28:39.919  4069  4082 D BluetoothSap: onBluetoothStateChange: up=true
07-14 13:28:39.919  4069  4082 D BluetoothSap: Binding service...
,07-14 13:28:39.921  9640  9804 D BluetoothSocket: bindListen(): myUserId = 0
07-14 13:28:39.921  9640  9804 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-14 13:28:39.925  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-14 13:28:39.925  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:39.925  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:39.925  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-14 13:28:39.925  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-14 13:28:39.925  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-14 13:28:39.925  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-14 13:28:39.925  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-14 13:28:39.925  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-14 13:28:39.928  9640  9804 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-14 13:28:39.931  9513  9513 D BluetoothAdapter: STATE_ON
07-14 13:28:39.932  9780  9780 I SA      : [SSP] onCreated
,07-14 13:28:39.936  9513  9513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,07-14 13:28:39.936  9601  9613 D BluetoothSap: onBluetoothStateChange: up=true
07-14 13:28:39.936  9601  9613 D BluetoothSap: Binding service...
,07-14 13:28:39.945  4069  4069 D BluetoothMap: Proxy object connected
,07-14 13:28:39.945  4069  4069 D MapProfile: Bluetooth service connected
07-14 13:28:39.945  4069  4069 D BluetoothMap: getConnectedDevices()
07-14 13:28:39.947  9601  9612 D BluetoothPan: onBluetoothStateChange on: true
07-14 13:28:39.956  9601  9601 D BluetoothSap: Proxy object connected
07-14 13:28:39.956  9601  9601 D SapProfile: Bluetooth service connected
07-14 13:28:39.957  4069  4069 D BluetoothSap: Proxy object connected
07-14 13:28:39.957  4069  4069 D SapProfile: Bluetooth service connected
,07-14 13:28:39.960  3707  3802 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-14 13:28:39.962  4576  4590 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-14 13:28:39.962  4576  4590 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-14 13:28:39.963  4069  6039 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-14 13:28:39.967  9640  9660 W bt_btif : btif_dm_generic_evt: event=34050
07-14 13:28:39.968  9640  9660 D BluetoothAdapterProperties: [VendorCapa] : mDbfwSupported: 1 , mA2dpLinkFeedbackSupported: 1
,07-14 13:28:39.970  9640  9652 D A2dpStateMachine: getConnectedDevices : size=0
07-14 13:28:39.970  9780  9780 D SamsungAnalytics:1.8.22: cf feature is supported
07-14 13:28:39.970  9601  9601 D BluetoothPan: BluetoothPAN Proxy object connected
07-14 13:28:39.970  4069  4082 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-14 13:28:39.970  9601  9601 D PanProfile: Bluetooth service connected
,07-14 13:28:39.975  3707  3802 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-14 13:28:39.975  3707  3802 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-14 13:28:39.977  4069  4069 D BluetoothInputDevice: Proxy object connected
,07-14 13:28:39.977  4069  4069 D HidProfile: Bluetooth service connected
07-14 13:28:39.977  9780  9780 D SamsungAnalytics:1.8.22: [Tracker] Tracker start:1.8.22
07-14 13:28:39.977  4069  4349 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-14 13:28:39.980  4615  4626 D BluetoothAdapter: onBluetoothStateChange: up=true
07-14 13:28:39.980  4615  4626 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-14 13:28:39.981  7412  7423 D BluetoothAdapter: onBluetoothStateChange: up=true
07-14 13:28:39.981  7412  7423 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-14 13:28:39.981  4069  4069 D A2dpProfile: Bluetooth service connected
,07-14 13:28:39.982  4069  4082 D BluetoothPbap: onBluetoothStateChange: up=true
,07-14 13:28:39.984  9780  9780 I SA      : LBE isSupportBixbyModel() FALSE
,07-14 13:28:39.985  9640  9651 D A2dpStateMachine: getConnectedDevices : size=0
,07-14 13:28:39.987  4069  4883 D BluetoothPan: onBluetoothStateChange on: true
,07-14 13:28:39.988  4069  4069 D BluetoothPbap: Proxy object connected
07-14 13:28:39.988  4069  4069 D PbapServerProfile: Bluetooth service connected
,07-14 13:28:39.990  4069  4069 D BluetoothPan: BluetoothPAN Proxy object connected
07-14 13:28:39.990  4069  4069 D PanProfile: Bluetooth service connected
,07-14 13:28:39.990  9513  9525 D BluetoothAdapter: onBluetoothStateChange: up=true
07-14 13:28:39.990  9513  9525 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-14 13:28:39.990  4043  4436 D BluetoothAdapter: onBluetoothStateChange: up=true
07-14 13:28:39.991  4043  4436 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-14 13:28:39.992  9780  9780 I SA      : [TPM] There is no property file
,07-14 13:28:39.995  4069  4348 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,07-14 13:28:39.995  3707  3707 D Telecom : SecBluetoothManager : register BluetoothHeadset after STATE_ON : null
07-14 13:28:39.995  3707  3707 D Telecom : SecBluetoothManager : registerBluetoothHeadsetMessageListener fail
07-14 13:28:39.995  3707  3707 D BluetoothPhoneService: Bluetooth Adapter state : 12
,07-14 13:28:39.996  3707  3707 I BluetoothPhoneService: queryPhoneState
,07-14 13:28:39.996  3707  3707 I BluetoothPhoneService: updateHeadsetWithCallState : true
07-14 13:28:39.997  4069  4348 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-14 13:28:39.999  3707  3908 D WifiService: setWifiEnabled: true pid=9513, uid=10033
,07-14 13:28:40.000  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
07-14 13:28:40.001  9780  9780 I SA      : [SCU] isHaveSA() - false
,07-14 13:28:40.002  9640  9640 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-14 13:28:40.002  9640  9640 D PanService: BT STATE ON
07-14 13:28:40.003  9640  9640 D EnhancedTetheringManager: EnhancedTetheringManager()
07-14 13:28:40.003  9640  9640 D EnhancedTetheringManager: start
07-14 13:28:40.003  9601  9601 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:40.003  9601  9601 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
07-14 13:28:40.004  3707  3908 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-14 13:28:40.004  3707  3908 D WifiControlHistoryProvider: query
07-14 13:28:40.004  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:40.008  9780  9780 I SA      : [SS] no samsung account is signed in
,07-14 13:28:40.009  9640  9640 D ETMLeHelper: ETMLeHelper()
,07-14 13:28:40.009  9640  9640 D ETMLeHelper: initTetherAdv
07-14 13:28:40.010  9601  9601 E BluetoothEventManager: unregisterProfileIntentReceiver :: mProfileConnectionReceiver was not registered.
07-14 13:28:40.010  9601  9601 D LocalBluetoothProfileManager: Adding local A2DP profile
07-14 13:28:40.011  3707  3707 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-14 13:28:40.011  3707  3707 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:40.011  3707  3707 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
07-14 13:28:40.011  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-14 13:28:40.012  3707  3908 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-14 13:28:40.012  9780  9780 I SA      : [TPM] getModelProperty : null
07-14 13:28:40.012  9780  9780 I SA      : [TPM] getCSCProperty : null
07-14 13:28:40.013  3707  3908 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:40.014  3707  3908 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-14 13:28:40.015  9780  9780 I SA      : [SCU] isHaveSA() - false
07-14 13:28:40.016  9780  9780 I SA      : [SCU] == networkStateCheck == false
07-14 13:28:40.016  9780  9780 I SA      : [SS] network off, couldn't connect to DIR
,07-14 13:28:40.017  3707  3908 I WifiService: Wi-Fi Sharing settings has not been accessed
07-14 13:28:40.017  9640  9640 D BluetoothAdapter: STATE_ON
07-14 13:28:40.017  3707  3908 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-14 13:28:40.017  9601  9601 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-14 13:28:40.018  3707  3926 E WifiController: illegal state found both WifiController and WifiStateMachine
07-14 13:28:40.018  9640  9640 D BluetoothAdapter: STATE_ON
07-14 13:28:40.020  9780  9780 D BixbyApi_0.1.6: Version Name:2.2.03-46
07-14 13:28:40.021  9640  9640 D BluetoothAdapter: STATE_ON
07-14 13:28:40.021  9601  9601 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-14 13:28:40.023  9640  9640 D BluetoothAdapter: isSecureModeEnabled
07-14 13:28:40.023  9640  9640 D BtConfig.SecureMode: isSecureModeOn:false
07-14 13:28:40.023  9780  9780 I SA      : [DM] init START
07-14 13:28:40.024  9640  9640 D ETMLeHelper: initTetherScan
07-14 13:28:40.025  4069  4348 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
07-14 13:28:40.025  4069  4348 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
07-14 13:28:40.025  4069  4348 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
07-14 13:28:40.025  4069  4348 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
07-14 13:28:40.025  4069  4348 W LocalBluetoothProfileManager: updateLocalProfiles :: Spp profile was created already 
07-14 13:28:40.026  9601  9601 E BluetoothHeadset: BTStateChangeCB is registed
07-14 13:28:40.028  9640  9640 D BluetoothAdapter: STATE_ON
07-14 13:28:40.028  9640  9640 D BluetoothAdapter: STATE_ON
07-14 13:28:40.029  9780  9780 I SA      : [DM] This device is not a Vodafone
07-14 13:28:40.030  9601  9601 D BluetoothMap: Create BluetoothMap proxy object
07-14 13:28:40.031  9640  9640 D BluetoothMapUtils: [RCS] imsConfigCscFeatures : , enableCpmFeature : false
07-14 13:28:40.032  9640  9640 D BluetoothMapUtils: mRcsSupported : false
07-14 13:28:40.033  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.034  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.034  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.034  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.035  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.035  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.035  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.036  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.036  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.036  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.037  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.037  3707  3744 D MountService: getExternalStorageMountMode : 1
07-14 13:28:40.037  3707  3744 D MountService: getExternalStorageMountMode : 3
07-14 13:28:40.037  3707  3744 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
07-14 13:28:40.039  9780  9780 W ResourceType: Failure getting entry for 0x7f0b0002 (t=10 e=2) (error -75)
07-14 13:28:40.039  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.040  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.040  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.040  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.040  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.041  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.041  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.041  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.042  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.042  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.042  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.043  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.043  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.043  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.044  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.044  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.044  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.045  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.045  9780  9780 W ResourceType: Failure getting entry for 0x7f0b0005 (t=10 e=5) (error -75)
07-14 13:28:40.045  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.045  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.046  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.046  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.046  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.047  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.047  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.047  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.048  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.050  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.050  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.050  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.051  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.051  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.051  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.052  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-14 13:28:40.052  9780  9780 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-14 13:28:40.054  9780  9780 I SA      : support phone number id : true
07-14 13:28:40.054  9780  9780 I SA      : [DM] Supports Ref Jpn : true
07-14 13:28:40.054  9780  9780 I SA      : [DM] init END
,07-14 13:28:40.054  9780  9780 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
,07-14 13:28:40.057  9780  9780 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,07-14 13:28:40.057  9780  9780 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
07-14 13:28:40.062  3707  3744 I ActivityManager: Start proc 9817:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
07-14 13:28:40.062  9817  9817 E Zygote  : v2
07-14 13:28:40.062  9817  9817 I libpersona: KNOX_SDCARD checking this for 10049
07-14 13:28:40.062  9817  9817 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:40.062  9817  9817 E Zygote  : isSdpEnabledProcess - SDP enabled
07-14 13:28:40.063  9817  9817 E Zygote  : accessInfo : 64
07-14 13:28:40.063  9817  9817 E Zygote  : isSdpEnabledProcess - SDP enabled
,07-14 13:28:40.063  9817  9817 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
,07-14 13:28:40.064  9817  9817 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
07-14 13:28:40.065  9817  9817 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
07-14 13:28:40.068  9780  9780 I SA      : [SLFUCHKMGR] constructor called
,07-14 13:28:40.082  9601  9601 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
07-14 13:28:40.082  9780  9780 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-14 13:28:40.082  9780  9780 I SA      : [OR] == isSIMCardReady false ==
,07-14 13:28:40.083  9780  9780 I SA      : [SCU] == networkStateCheck == false
07-14 13:28:40.083  9780  9780 I SA      : [OR] onReceive END
,07-14 13:28:40.087  9817  9817 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:40.088  9817  9817 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:40.090  3707  3937 I ActivityManager: KPU : put [com.sec.android.widgetapp.samsungapps] : 26944 K
,07-14 13:28:40.090  3707  3937 I ActivityManager: Killing 8950:com.sec.android.widgetapp.samsungapps/u0a105 (adj 906): DHA:empty #33
07-14 13:28:40.092  3707  4718 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
07-14 13:28:40.101  9601  9601 D LocalBluetoothProfileManager: Adding local Spp profile
07-14 13:28:40.102  3707  3783 D MountService: getExternalStorageMountMode : 1
07-14 13:28:40.102  3707  3783 D MountService: getExternalStorageMountMode : 3
07-14 13:28:40.102  3707  3783 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.svcagent
,07-14 13:28:40.123  9831  9831 E Zygote  : v2
07-14 13:28:40.123  9831  9831 I libpersona: KNOX_SDCARD checking this for 1000
,07-14 13:28:40.123  9831  9831 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:40.123  9817  9817 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
07-14 13:28:40.124  9831  9831 E Zygote  : accessInfo : 0
07-14 13:28:40.124  9831  9831 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:40.125  9831  9831 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.svcagent 
07-14 13:28:40.127  3707  3783 I ActivityManager: Start proc 9831:com.samsung.android.svcagent/1000 for broadcast com.samsung.android.svcagent/com.samsung.android.service.svcagent.BootReceiver
07-14 13:28:40.128  3707  4836 D ActivityManager: cleanUpApplicationRecord -- 8950
,07-14 13:28:40.132  4615  4626 D ForegroundUtils: could not check pending caller
,07-14 13:28:40.139  9817  9817 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-14 13:28:40.139  9601  9601 D A2dpProfile: Bluetooth service connected
,07-14 13:28:40.142  9640  9812 D A2dpStateMachine: getConnectedDevices : size=0
07-14 13:28:40.142  9601  9601 D BluetoothMap: Proxy object connected
,07-14 13:28:40.143  9601  9601 D MapProfile: Bluetooth service connected
07-14 13:28:40.143  9601  9601 D BluetoothMap: getConnectedDevices()
,07-14 13:28:40.146  9601  9601 D BluetoothPbap: Proxy object connected
,07-14 13:28:40.147  9601  9601 D PbapServerProfile: Bluetooth service connected
07-14 13:28:40.147  9601  9601 D BluetoothInputDevice: Proxy object connected
,07-14 13:28:40.148  9601  9601 D HidProfile: Bluetooth service connected
07-14 13:28:40.149  9831  9831 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-14 13:28:40.149  9831  9831 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:40.152  3707  4675 I ActivityManager: DSS on for com.samsung.android.svcagent and scale is 1.0
,07-14 13:28:40.154  3707  4312 D RCPManagerService: exchangeData() failure , invalid userId
,07-14 13:28:40.156  3707  4239 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / op:PendingIntent{77932f9: PendingIntentRecord{1b8c23e android broadcastIntent}}
,07-14 13:28:40.159  3707  4239 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20170715T132840 - CU:1000/CP:3707
,07-14 13:28:40.170  9831  9831 W System  : ClassLoader referenced unknown path: /system/priv-app/SVCAgent/lib/arm64
,07-14 13:28:40.172  9817  9817 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,07-14 13:28:40.172  9817  9817 I QBNRClientHelper: init SyncClientHelper : Email
07-14 13:28:40.172  9817  9817 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : EMAILFOLDER, 55LAYJm0O2, com.samsung.android.email.provider.service.sCloudBNRService2
07-14 13:28:40.173  9817  9817 I QBNRClientHelper: init SyncClientHelper : EMAILFOLDER
,07-14 13:28:40.182  9831  9831 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:40.190  9831  9831 I SVCAgent: Ignore network change.
,07-14 13:28:40.193  3707  4836 D MountService: getExternalStorageMountMode : 1
,07-14 13:28:40.193  3707  4836 D MountService: getExternalStorageMountMode : 3
07-14 13:28:40.193  3707  4836 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10064, packageName : com.samsung.android.themestore
,07-14 13:28:40.212  9845  9845 E Zygote  : v2
,07-14 13:28:40.212  9845  9845 I libpersona: KNOX_SDCARD checking this for 10064
07-14 13:28:40.212  9845  9845 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:40.213  9845  9845 E Zygote  : accessInfo : 0
07-14 13:28:40.213  3707  4836 I ActivityManager: Start proc 9845:com.samsung.android.themestore/u0a64 for broadcast com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,07-14 13:28:40.213  9845  9845 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:40.215  9845  9845 I SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,07-14 13:28:40.219  3707  3937 D RCPManagerService: exchangeData() failure , invalid userId
,07-14 13:28:40.219  3707  4836 I ActivityManager: KPU : put [com.wssnps] : 26908 K
,07-14 13:28:40.219  3707  4836 I ActivityManager: Killing 8972:com.wssnps/1000 (adj 906): DHA:empty #33
,07-14 13:28:40.224  9817  9850 D skia    : ---- fAsset->read(8192) returned 0
07-14 13:28:40.224  9817  9817 D SamsungAnalytics:1.8.25: cf feature is supported
07-14 13:28:40.224  9817  9850 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-14 13:28:40.233  9817  9817 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
,07-14 13:28:40.234  9817  9850 D skia    : ---- fAsset->read(8192) returned 0
07-14 13:28:40.234  9817  9850 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-14 13:28:40.236  9817  9850 D skia    : ---- fAsset->read(8192) returned 0
07-14 13:28:40.236  9817  9850 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-14 13:28:40.241  3707  4717 D MountService: getExternalStorageMountMode : 1
,07-14 13:28:40.241  3707  4717 D MountService: getExternalStorageMountMode : 3
07-14 13:28:40.241  3707  4717 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
,07-14 13:28:40.245  9845  9845 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-14 13:28:40.246  9845  9845 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:40.261  9865  9865 E Zygote  : v2
07-14 13:28:40.261  9865  9865 I libpersona: KNOX_SDCARD checking this for 10049
07-14 13:28:40.261  9865  9865 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:40.261  9865  9865 E Zygote  : isSdpEnabledProcess - SDP enabled
,07-14 13:28:40.262  9865  9865 E Zygote  : accessInfo : 64
07-14 13:28:40.262  9865  9865 E Zygote  : isSdpEnabledProcess - SDP enabled
07-14 13:28:40.262  9865  9865 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
07-14 13:28:40.263  9865  9865 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:40.264  9865  9865 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,07-14 13:28:40.267  3707  4717 I ActivityManager: Start proc 9865:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,07-14 13:28:40.268  3707  4679 D ActivityManager: cleanUpApplicationRecord -- 8972
,07-14 13:28:40.269  4615  4627 D ForegroundUtils: could not check pending caller
,07-14 13:28:40.271  3707  4313 I ActivityManager: DSS on for com.samsung.android.themestore and scale is 1.0
,07-14 13:28:40.288  9865  9865 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:40.289  9865  9865 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:40.291  3707  4717 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
,07-14 13:28:40.297  9845  9845 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-14 13:28:40.297  4497  4497 D io_stats: !@   8,0 r 25137 2259004 w 4660 199432 d 599 72948 f 1880 1880 iot 10960 10469 th 468280 0 0 pt 0 inp 0 0 201.412
07-14 13:28:40.298  9845  9845 W System  : ClassLoader referenced unknown path: /system/priv-app/GalaxyThemes/lib/arm64
,07-14 13:28:40.311  9601  9601 D HeadsetProfile: Bluetooth service connected
07-14 13:28:40.312  9845  9845 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-14 13:28:40.312  4069  4069 D HeadsetProfile: Bluetooth service connected
,07-14 13:28:40.320  3707  3707 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.bluetooth.SecBluetoothMessageListener@9c3b69b
07-14 13:28:40.320  3707  3707 D BluetoothHeadset: registerMessageListener
,07-14 13:28:40.322  9640  9813 D HeadsetService: registerMessageListener
07-14 13:28:40.323  9640  9813 D HeadsetService: registerMessageListener
07-14 13:28:40.323  9640  9765 D HeadsetStateMachine: Disconnected process message: 70, size: 0
,07-14 13:28:40.323  3707  3707 I Telecom : SecBluetoothManager : register MessageListener
07-14 13:28:40.323  9640  9765 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1f251f9
07-14 13:28:40.325  9640  9798 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,07-14 13:28:40.327  9865  9865 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
,07-14 13:28:40.328  9640  9880 D BluetoothSocket: bindListen(): myUserId = 0
07-14 13:28:40.328  9640  9880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-14 13:28:40.329  9640  9798 D BluetoothSocket: bindListen(): myUserId = 0
07-14 13:28:40.329  9640  9798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-14 13:28:40.330  9845  9845 D a       : Exist Config : false
,07-14 13:28:40.331  3707  3707 I Telecom : SecBluetoothManager : not single connected gear
07-14 13:28:40.331  9845  9845 D a       : getMcc
,07-14 13:28:40.332  9640  9880 D BluetoothSdpJni: sdpCreateSapsRecordNative:
07-14 13:28:40.332  9640  9880 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-14 13:28:40.335  3295  3771 D Netd    : Iface wlan0 link down
07-14 13:28:40.336  9845  9845 D as      : isQaMode
07-14 13:28:40.337  3707  4224 D wifi    : set interface wlan0 flags (DOWN)
07-14 13:28:40.337  9640  9798 D BluetoothSocket: bindListen(): myUserId = 0
07-14 13:28:40.337  9640  9798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-14 13:28:40.338  3707  3927 D WifiNative-HAL: HAL event thread stopped successfully
07-14 13:28:40.339  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, false
07-14 13:28:40.339  3707  3801 D Tethering: interfaceStatusChanged wlan0, false
,07-14 13:28:40.342  9865  9865 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-14 13:28:40.342  3707  3707 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
07-14 13:28:40.342  3707  3707 I BluetoothPhoneService: updateHeadsetWithCallState : true
07-14 13:28:40.343  9845  9845 D a       : getMnc
07-14 13:28:40.343  9845  9845 D a       : getCsc
07-14 13:28:40.343  9845  9845 D a       : getSystemCountryCode
07-14 13:28:40.343  3707  4365 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ADA_0
07-14 13:28:40.343  9845  9845 D a       : getImei
07-14 13:28:40.343  3707  4365 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ADA_0
,07-14 13:28:40.345  9640  9798 D ObexServerSockets: Succeed to create listening sockets 
07-14 13:28:40.345  9640  9798 D ObexServerSockets: startAccept()
07-14 13:28:40.345  9845  9845 D as      : getMd5HashString
07-14 13:28:40.346  9845  9845 D as      : getSha256HashString
07-14 13:28:40.346  9845  9845 D a       : getModelName
07-14 13:28:40.346  9640  9765 D HeadsetStateMachine: Disconnected process message: 9, size: 0
07-14 13:28:40.346  9845  9845 D a       : getVirtualModelName
07-14 13:28:40.346  3707  4365 I Telecom : SecBluetoothManager : not single connected gear
07-14 13:28:40.347  9845  9845 D a       : getAndroidSDKVersion
07-14 13:28:40.347  9845  9845 D a       : getLanguageCode
07-14 13:28:40.347  9640  9765 D A2dpSinkService: getA2dpSinkService(): service is NULL
07-14 13:28:40.347  9845  9845 D a       : getCountryCode
07-14 13:28:40.347  9640  9765 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
07-14 13:28:40.347  3707  4365 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ADA_0
07-14 13:28:40.348  9640  9882 D ObexServerSockets: Accepting socket connection for masId0
,07-14 13:28:40.348  9640  9798 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-14 13:28:40.348  9845  9845 D a       : getNetworkType
07-14 13:28:40.348  9640  9798 D BluetoothSdpJni: SDP Create record success - handle: 1
07-14 13:28:40.348  9640  9883 D ObexServerSockets: Accepting socket connection for masId0
07-14 13:28:40.353  3274  3274 D audio_hw_primary: adev_set_parameters: enter: kvpairs: A2dpSuspended=false
07-14 13:28:40.355  9640  9765 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
07-14 13:28:40.359  9845  9845 D w       : isSupportedAodSystemFeature
07-14 13:28:40.360  9845  9845 D a       : getThemeFrameworkVersion
,07-14 13:28:40.364  9845  9845 D a       : isLogPrintMode
,07-14 13:28:40.366  9845  9845 D as      : isQaMode
,07-14 13:28:40.369  9845  9845 D a       : getVerName
,07-14 13:28:40.370  9845  9845 D a       : getVerCode
,07-14 13:28:40.371  9845  9845 D a       : getPackageName
07-14 13:28:40.371  9845  9845 D a       : getAutoUpgradeInterval
07-14 13:28:40.372  9845  9845 D a       : loadCountrySearchEx
,07-14 13:28:40.375  9845  9845 D a       : com.samsung.android.themestore.g.c.b.u; class invalid for deserialization
,07-14 13:28:40.375  9845  9845 I a       : # initConfig Time : 48
07-14 13:28:40.375  9845  9845 I a       : ● MCC/NNC: /0
07-14 13:28:40.375  9845  9845 I a       : ● Model: SM-G930F_TM
07-14 13:28:40.375  9845  9845 I a       : ● MyApp Version: 2.1.56-70306
07-14 13:28:40.375  9845  9845 I a       : ● OS Version: 24
07-14 13:28:40.375  9845  9845 I a       : ● IsSupportedSView: true
,07-14 13:28:40.378  3707  5610 D SSRM:f  : SIOP:: AP = 290, PST = 282 (W:10), CP = 233, CUR = 119, LCD = 57
07-14 13:28:40.380  3707  3937 D RCPManagerService: exchangeData() failure , invalid userId
,07-14 13:28:40.383  9845  9845 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,07-14 13:28:40.386  9865  9865 D SamsungAnalytics:1.8.25: cf feature is supported
,07-14 13:28:40.388  9865  9885 D skia    : ---- fAsset->read(8192) returned 0
07-14 13:28:40.388  9865  9885 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-14 13:28:40.393  9865  9885 D skia    : ---- fAsset->read(8192) returned 0
07-14 13:28:40.393  9865  9885 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-14 13:28:40.397  9865  9885 D skia    : ---- fAsset->read(8192) returned 0
07-14 13:28:40.397  9865  9885 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-14 13:28:40.397  9845  9845 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,07-14 13:28:40.400  9865  9865 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
,07-14 13:28:40.408  3707  3987 I ActivityManager: KPU : put [com.samsung.android.app.watchmanager:contentprovider] : 27176 K
,07-14 13:28:40.408  3707  3987 I ActivityManager: Killing 9006:com.samsung.android.app.watchmanager:contentprovider/u0a18 (adj 906): DHA:empty #33
,07-14 13:28:40.415  7715  7715 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,07-14 13:28:40.415  7715  7715 E SPPClientService: [SystemStateMoniter] Current Time : 201531
,07-14 13:28:40.417  7715  7715 E SPPClientService: [SystemStateMoniter] No Connect : true
,07-14 13:28:40.425  3707  3783 D MountService: getExternalStorageMountMode : 1
,07-14 13:28:40.425  3707  3783 D MountService: getExternalStorageMountMode : 3
07-14 13:28:40.425  3707  3783 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 5005, packageName : com.samsung.android.allshare.service.fileshare
,07-14 13:28:40.442  9901  9901 E Zygote  : v2
07-14 13:28:40.442  9901  9901 I libpersona: KNOX_SDCARD checking this for 5005
,07-14 13:28:40.442  9901  9901 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:40.443  9901  9901 E Zygote  : accessInfo : 0
07-14 13:28:40.443  9901  9901 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:40.444  9901  9901 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.allshare.service.fileshare 
,07-14 13:28:40.446  3707  3783 I ActivityManager: Start proc 9901:com.samsung.android.allshare.service.fileshare/5005 for broadcast com.samsung.android.allshare.service.fileshare/.FileShareBroadcastReceiver
,07-14 13:28:40.453  3707  3965 D ActivityManager: cleanUpApplicationRecord -- 9006
,07-14 13:28:40.458  7715  9914 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
07-14 13:28:40.459  4615  4627 D ForegroundUtils: could not check pending caller
,07-14 13:28:40.462  9901  9901 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-14 13:28:40.463  9901  9901 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:40.467  3707  3743 I ActivityManager: DSS on for com.samsung.android.allshare.service.fileshare and scale is 1.0
,07-14 13:28:40.490  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:40.491  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.491  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.491  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.491  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.491  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.491  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.491  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.491  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.492  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:40.502  9901  9901 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:40.507  9901  9901 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-14 13:28:40.509  9901  9901 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
,07-14 13:28:40.522  3707  4836 D WifiService: setWifiEnabled: true pid=9513, uid=10033
07-14 13:28:40.523  3707  4836 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-14 13:28:40.523  3707  4836 D WifiControlHistoryProvider: query
07-14 13:28:40.524  9901  9901 D FileShare: Outbound.stopDelayTimer - 
,07-14 13:28:40.539  3707  3927 E WifiHW  : ##################### set firmware type 0 #####################
,07-14 13:28:40.541  3295  3781 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-14 13:28:40.542  3295  3781 I WifiHW  : module is semco
07-14 13:28:40.542  3295  3781 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-14 13:28:40.542  3295  3781 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-14 13:28:40.542  3295  3781 E WifiHW  : TEMP_FAILURE_RETRY complete
07-14 13:28:40.542  3295  3781 D SoftapController: Softap fwReload - Ok
07-14 13:28:40.542  9734  9734 I [RBL] ServiceReceiver: @onReceive - rawData : null
07-14 13:28:40.543  3707  3927 E NetworkManagement: wifiFirmwareReload Error reloading wlan0 fw in STA mode: event = 200 65 Softap operation succeeded
,07-14 13:28:40.545  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-14 13:28:40.546  3295  3781 D CommandListener: Setting iface cfg
,07-14 13:28:40.547  3295  3781 D CommandListener: Trying to bring down wlan0
,07-14 13:28:40.548  3295  3781 D CommandListener: Clearing all IP addresses on wlan0
,07-14 13:28:40.551  3707  3987 I ActivityManager: KPU : put [com.google.android.apps.photos:CameraShortcut] : 35480 K
07-14 13:28:40.551  3707  3987 I ActivityManager: Killing 9019:com.google.android.apps.photos:CameraShortcut/u0a129 (adj 906): DHA:empty #33
07-14 13:28:40.554  3707  3927 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-14 13:28:40.562  3707  4836 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-14 13:28:40.563  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-14 13:28:40.563  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-14 13:28:40.563  3707  4836 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:40.563  9750  9750 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-14 13:28:40.564  3707  4836 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-14 13:28:40.568  3707  4836 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-14 13:28:40.568  3707  4836 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-14 13:28:40.569  3707  3926 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-14 13:28:40.571  9766  9766 I PhoneErrorReceiver: onReceive
,07-14 13:28:40.577  9415  9415 I usagelog: received in receiver
07-14 13:28:40.577  9415  9415 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-14 13:28:40.577  9415  9415 I KnoxUsageLogPro: premStatus:2
,07-14 13:28:40.578  9415  9415 I KnoxUsageLogPro: isEulaShown : false
,07-14 13:28:40.578  9415  9415 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-14 13:28:40.588  9396  9396 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-14 13:28:40.588  9396  9396 D SecurityLogAgent: NetworkReceiver : Wifi_state is 0
,07-14 13:28:40.591  3707  4675 D ActivityManager: cleanUpApplicationRecord -- 9019
,07-14 13:28:40.592  4615  4627 D ForegroundUtils: could not check pending caller
,07-14 13:28:40.596  3707  3937 D MountService: getExternalStorageMountMode : 1
07-14 13:28:40.596  3707  3937 D MountService: getExternalStorageMountMode : 3
07-14 13:28:40.596  3707  3937 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10172, packageName : com.example.ThaliTestApp
,07-14 13:28:40.613  9916  9916 E Zygote  : v2
07-14 13:28:40.614  9916  9916 I libpersona: KNOX_SDCARD checking this for 10172
07-14 13:28:40.614  9916  9916 I libpersona: KNOX_SDCARD not a persona
,07-14 13:28:40.616  9916  9916 E Zygote  : accessInfo : 0
,07-14 13:28:40.616  9916  9916 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:40.618  9916  9916 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.example.ThaliTestApp 
,07-14 13:28:40.619  3707  3937 I ActivityManager: Start proc 9916:com.example.ThaliTestApp/u0a172 for broadcast com.example.ThaliTestApp/io.jxcore.node.ConnectivityChangeListener
,07-14 13:28:40.624  9916  9916 I art     : Late-enabling -Xcheck:jni
,07-14 13:28:40.653  9916  9916 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-14 13:28:40.654  9916  9916 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:40.657  3707  4313 I ActivityManager: DSS on for com.example.ThaliTestApp and scale is 1.0
,07-14 13:28:40.700  9916  9916 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-14 13:28:40.724  9916  9916 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:40.734  3707  4312 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:40.735  3707  4312 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.735  3707  4312 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.735  3707  4312 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:40.736  3707  4312 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.736  3707  4312 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.736  3707  4312 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.736  3707  4312 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.737  3707  4312 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.737  3707  4312 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:40.783  9916  9916 D jxcore_app_log: JniHelper::setJavaVM(0xe65b4000), pthread_self() = -374049484
,07-14 13:28:40.783  9916  9916 E JX-Cordova: JXcore wasn't initialized yet
,07-14 13:28:40.789  3707  3743 D MountService: getExternalStorageMountMode : 3
07-14 13:28:40.790  3707  3743 D MountService: getExternalStorageMountMode : 3
07-14 13:28:40.790  3707  3743 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 10173, packageName : com.rockwellautomation.AppPlatformP2P
,07-14 13:28:40.831  3707  3743 I ActivityManager: Start proc 9931:com.rockwellautomation.AppPlatformP2P/u0a173 for broadcast com.rockwellautomation.AppPlatformP2P/io.jxcore.node.ConnectivityChangeListener
,07-14 13:28:40.837  9931  9931 E Zygote  : v2
,07-14 13:28:40.837  9931  9931 I libpersona: KNOX_SDCARD checking this for 10173
07-14 13:28:40.837  9931  9931 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:40.838  9931  9931 E Zygote  : accessInfo : 0
07-14 13:28:40.838  9931  9931 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:40.840  3707  3743 I ActivityManager: KPU : put [com.google.android.apps.photos] : 37484 K
,07-14 13:28:40.840  3707  3743 I ActivityManager: Killing 8987:com.google.android.apps.photos/u0a129 (adj 906): DHA:empty #33
07-14 13:28:40.840  9931  9931 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.rockwellautomation.AppPlatformP2P 
,07-14 13:28:40.843  9931  9931 I art     : Late-enabling -Xcheck:jni
,07-14 13:28:40.871  9931  9931 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-14 13:28:40.872  9931  9931 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:40.875  3707  4836 I ActivityManager: DSS on for com.rockwellautomation.AppPlatformP2P and scale is 1.0
,07-14 13:28:40.883  3707  3744 D ActivityManager: cleanUpApplicationRecord -- 8987
,07-14 13:28:40.885  4615  4626 D ForegroundUtils: could not check pending caller
,07-14 13:28:40.913  9931  9931 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-14 13:28:40.933  9931  9931 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:40.956  3707  3987 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.957  3707  3987 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.957  3707  3987 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.957  3707  3987 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.957  3707  3987 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:40.957  3707  3987 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.958  3707  3987 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.958  3707  3987 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:40.958  3707  3987 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:40.958  3707  3987 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:41.007  9931  9931 D jxcore_app_log: JniHelper::setJavaVM(0xe65b4000), pthread_self() = -374049484
07-14 13:28:41.008  9931  9931 E JX-Cordova: JXcore wasn't initialized yet
,07-14 13:28:41.022  3707  4716 I ActivityManager: KPU : put [com.android.vending] : 34160 K
07-14 13:28:41.022  3707  4716 I ActivityManager: Killing 8568:com.android.vending/u0a32 (adj 906): DHA:empty #33
,07-14 13:28:41.032  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:41.033  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.033  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.033  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.034  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.034  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.034  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.034  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.035  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.035  3707  3922 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:41.074  3707  3743 D ActivityManager: cleanUpApplicationRecord -- 8568
07-14 13:28:41.074  3707  4312 D WifiService: setWifiEnabled: true pid=9513, uid=10033
,07-14 13:28:41.075  9601  9601 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:41.075  9601  9601 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,07-14 13:28:41.076  4615  4627 D ForegroundUtils: could not check pending caller
,07-14 13:28:41.082  3707  4312 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-14 13:28:41.082  3707  4312 D WifiControlHistoryProvider: query
,07-14 13:28:41.091  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-14 13:28:41.094  3707  4312 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-14 13:28:41.095  3707  4312 D SecContentProvider: called from android.uid.system:1000
,07-14 13:28:41.096  3707  4312 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-14 13:28:41.100  3707  4312 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-14 13:28:41.101  3707  4312 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-14 13:28:41.103  3707  3926 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-14 13:28:41.130  3707  3863 D SamsungAlarmManager: Expired : 4
07-14 13:28:41.130  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132853, SetElapsed=214998, nowELAPSED=202246
,07-14 13:28:41.131  3707  3863 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@7bb593d alarm=Alarm{acb3502 type 2 when 202246 android}
,07-14 13:28:41.141  9396  9396 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-14 13:28:41.141  9396  9396 D SecurityLogAgent: NetworkReceiver : Wifi_state is 1
,07-14 13:28:41.158  3707  3743 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.158  3707  3743 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.158  3707  3743 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.158  3707  3743 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.158  3707  3743 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.158  3707  3743 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.158  3707  3743 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.158  3707  3743 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.159  3707  3743 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.159  3707  3743 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:41.167  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.168  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.168  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.168  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.168  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.168  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.168  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.168  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.168  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.168  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:41.176  3707  4675 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.177  3707  4675 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.177  3707  4675 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.177  3707  4675 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.177  3707  4675 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.177  3707  4675 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.177  3707  4675 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.177  3707  4675 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.177  3707  4675 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.177  3707  4675 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.192  9601  9601 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-14 13:28:41.205  9640  9640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:28:41.206  9640  9640 D BtConfig.SecureMode: isSecureModeOn:false
07-14 13:28:41.208  9601  9601 D DockEventReceiver: finishStartingService: stopping service
07-14 13:28:41.221  9640  9640 V BtOppService: isOwner == true
07-14 13:28:41.224  3707  4675 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20270712T132841 - CU:10019/CP:4576
07-14 13:28:41.236  9601  9601 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-14 13:28:41.236  9601  9601 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,07-14 13:28:41.273  3707  4718 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-14 13:28:41.274  3707  4718 D SecContentProvider: called from android.uid.bluetooth:1002
,07-14 13:28:41.290  9640  9961 D BluetoothSocket: bindListen(): myUserId = 0
07-14 13:28:41.290  9640  9961 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-14 13:28:41.293  9640  9961 I BtOppRfcommListener: Accept thread started.
,07-14 13:28:41.309  4576  4576 D BluetoothAdapter: STATE_ON
07-14 13:28:41.310  4576  4576 D BluetoothAdapter: STATE_ON
,07-14 13:28:41.311  4576  4576 I BeaconBle: Using BLE 'L' hardware layer
,07-14 13:28:41.314  4576  4576 W Nearby  : Bind call too late - someone already tried to get: interface atxb
,07-14 13:28:41.499  3707  3908 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BleCentralService newState = 1 callingPackage = 10019
,07-14 13:28:41.505  3707  3743 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BlePeripheralService newState = 1 callingPackage = 10019
,07-14 13:28:41.685  3707  4718 D WifiService: setWifiEnabled: true pid=9513, uid=10033
,07-14 13:28:41.689  3707  4718 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-14 13:28:41.689  3707  4718 D WifiControlHistoryProvider: query
07-14 13:28:41.696  3707  3927 D wifi    : set interface wlan0 flags (UP)
07-14 13:28:41.696  3295  3771 D Netd    : Iface wlan0 link up
07-14 13:28:41.696  3707  3927 I WifiHAL : Initializing wifi
07-14 13:28:41.696  3707  3927 I WifiHAL : Creating socket
07-14 13:28:41.698  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:28:41.698  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
07-14 13:28:41.700  3707  3927 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-14 13:28:41.700  3707  3927 D wifi    : Did set static halHandle = 0x711f76e7e0
07-14 13:28:41.700  3707  3927 D wifi    : halHandle = 0x711f76e7e0, mVM = 0x712d090300, mCls = 0x1036ca
07-14 13:28:41.700  3707  3927 D wifi    : array field set
07-14 13:28:41.700  3707  3744 D MountService: getExternalStorageMountMode : 1
07-14 13:28:41.700  3707  3744 D MountService: getExternalStorageMountMode : 3
07-14 13:28:41.700  3707  3744 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10003, packageName : com.sec.android.provider.badge
07-14 13:28:41.704  3707  3927 I WifiHW  : CCMode is disabled, skip verifying wpa_supplicant
07-14 13:28:41.705  3707  9971 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=485859190752
07-14 13:28:41.705  3707  9971 D wifi    : waitForHalEvents called, vm = 0x712d090300, obj = 0x1036ca, env = 0x70ffa71000
07-14 13:28:41.707  3707  3927 E WifiHW  : supplicant_name : p2p_supplicant
,07-14 13:28:41.729  9973  9973 E Zygote  : v2
07-14 13:28:41.729  9973  9973 I libpersona: KNOX_SDCARD checking this for 10003
07-14 13:28:41.729  9973  9973 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:41.730  3707  3744 I ActivityManager: Start proc 9973:com.sec.android.provider.badge/u0a3 for broadcast com.sec.android.provider.badge/.BadgeCountReceiver
07-14 13:28:41.730  9973  9973 E Zygote  : accessInfo : 0
07-14 13:28:41.730  9973  9973 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
07-14 13:28:41.732  9973  9973 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
07-14 13:28:41.735  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=-2ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-14 13:28:41.737  5059  6572 I Authzen : [PermitStore] Getting all permits...
07-14 13:28:41.742  3707  4718 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-14 13:28:41.743  3707  4718 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:41.744  3707  4718 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-14 13:28:41.748  3707  4718 I WifiService: Wi-Fi Sharing settings has not been accessed
07-14 13:28:41.749  3707  4718 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-14 13:28:41.749  3707  3926 E WifiController: illegal state found both WifiController and WifiStateMachine
07-14 13:28:41.760  9973  9973 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:41.761  9973  9973 D ActivityThread: Added TimaKeyStore provider
07-14 13:28:41.763  3707  3908 I ActivityManager: DSS on for com.sec.android.provider.badge and scale is 1.0
,07-14 13:28:41.780  9972  9972 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 9972 | /system/bin/wpa_supplicant
07-14 13:28:41.780  9972  9972 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
07-14 13:28:41.783  9972  9972 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-14 13:28:41.783  9972  9972 I wpa_supplicant: Successfully initialized wpa_supplicant
07-14 13:28:41.784  4576  9955 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
07-14 13:28:41.785  9973  9973 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_N/lib/arm64
07-14 13:28:41.786  9972  9972 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x400008), vendorssid_list()
07-14 13:28:41.787  9972  9972 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-14 13:28:41.787  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 9972
07-14 13:28:41.788  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-14 13:28:41.788  9972  9972 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-14 13:28:41.788  9972  9972 I wpa_supplicant: ssSupport state is = 1
07-14 13:28:41.788  9972  9972 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
07-14 13:28:41.788  9972  9972 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-14 13:28:41.788  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
07-14 13:28:41.788  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 9972
07-14 13:28:41.788  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
07-14 13:28:41.797  9973  9973 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-14 13:28:41.802  9973  9973 D BadgeProvider: onCreate
07-14 13:28:41.803  9973  9973 D BadgeProvider: DatabaseHelper
,07-14 13:28:41.806  9973  9973 D BadgeCountReceiver: badge intent : Intent { act=com.sec.intent.action.BADGE_COUNT_UPDATE flg=0x10 cmp=com.sec.android.provider.badge/.BadgeCountReceiver launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-14 13:28:41.806  9973  9973 D BadgeCountReceiver: packageName: com.samsung.android.email.provider, className: com.samsung.android.email.ui.activity.MessageListXL, count: 0
07-14 13:28:41.808  3707  3927 D SecContentProvider: insert(), uri = 2
07-14 13:28:41.809  3707  3927 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:41.811  3707  3927 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-14 13:28:41.811  9973  9973 D BadgeProvider: onOpen
07-14 13:28:41.812  3707  3927 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-14 13:28:41.813  9973  9973 D BaseReflect: null getOwnClass TEST
07-14 13:28:41.813  9973  9973 D MethodReflector: android.content.ContentResolver getClass TEST
07-14 13:28:41.813  9973  9973 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
07-14 13:28:41.813  9973  9973 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
07-14 13:28:41.814  3707  3707 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-14 13:28:41.815  3707  3707 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-14 13:28:41.815  3707  3954 I WifiHs20Service: Message received 5011
07-14 13:28:41.816  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=2 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-14 13:28:41.820  3707  3707 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-14 13:28:41.821  3707  4238 D SLocation: checkWifiInfo
07-14 13:28:41.822  3707  4040 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-14 13:28:41.822  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-14 13:28:41.825  3707  4040 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-14 13:28:41.828  4818  4818 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
07-14 13:28:41.828  9973  9973 D MethodReflector: notifyChange is called
07-14 13:28:41.829  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:41.829  4818  4818 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
07-14 13:28:41.829  9973  9973 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-14 13:28:41.829  9973  9973 D BadgeProvider: sendNotify, [notify] : null
07-14 13:28:41.830  9973  9973 D BadgeProvider: update, getCallingPackage() : com.sec.android.provider.badge
07-14 13:28:41.830  9973  9973 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-14 13:28:41.830  9973  9973 D BadgeProvider: update, [uri.query] : null
07-14 13:28:41.830  9973  9973 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-14 13:28:41.830  9973  9973 D BadgeProvider: update, [UpdateCount] : 1
07-14 13:28:41.839  9396  9396 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-14 13:28:41.839  9396  9396 D SecurityLogAgent: NetworkReceiver : Wifi_state is 2
,07-14 13:28:41.852  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.852  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.853  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.853  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.853  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.853  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.854  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.854  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.854  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.855  3707  4737 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.865  3707  4679 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.866  3707  4679 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.866  3707  4679 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.866  3707  4679 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.866  3707  4679 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.867  3707  4679 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.867  3707  4679 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.867  3707  4679 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.867  3707  4679 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.868  3707  4679 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.877  3707  4313 I ActivityManager: KPU : put [com.samsung.android.oneconnect] : 27220 K
07-14 13:28:41.877  3707  4313 I ActivityManager: Killing 9167:com.samsung.android.oneconnect/u0a197 (adj 906): DHA:empty #33
07-14 13:28:41.881  3707  4677 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.881  3707  4677 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.881  3707  4677 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:41.881  3707  4677 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.882  3707  4677 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.882  3707  4677 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.882  3707  4677 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.882  3707  4677 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.883  3707  4677 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:41.883  3707  4677 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:41.912  3707  4716 D ActivityManager: cleanUpApplicationRecord -- 9167
07-14 13:28:41.913  4615  4627 D ForegroundUtils: could not check pending caller
,07-14 13:28:41.925  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-14 13:28:41.967  9972  9972 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,07-14 13:28:41.998  9972  9972 W wpa_supplicant: Loading system cred
07-14 13:28:41.998  9972  9972 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-14 13:28:41.999  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9972
07-14 13:28:41.999  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,07-14 13:28:41.999  9972  9972 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-14 13:28:41.999  9972  9972 I wpa_supplicant: ssSupport state is = 1
07-14 13:28:42.000  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-14 13:28:42.001  9972  9972 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-14 13:28:42.001  9972  9972 I wpa_supplicant: [getIMSI]: sim_num 0
,07-14 13:28:42.030  4818  4818 D LauncherApplication: run: mBadgeRefreshHandler reloadBadges
07-14 13:28:42.031  4818  4818 D Launcher.Model: reloadBadges entered.
,07-14 13:28:42.046  9972  9972 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-14 13:28:42.048  3295  3771 D Netd    : Iface wlan0 link up
07-14 13:28:42.048  3295  3771 D Netd    : Iface wlan0 link up
,07-14 13:28:42.049  9973  9985 D BadgeProvider: query, [selection] : null
07-14 13:28:42.050  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:28:42.050  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
07-14 13:28:42.051  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:28:42.051  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
,07-14 13:28:42.054  4818  4933 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
07-14 13:28:42.054  4818  4933 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
07-14 13:28:42.054  4818  4933 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
07-14 13:28:42.054  4818  4933 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
07-14 13:28:42.055  4818  4933 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
07-14 13:28:42.055  4818  4933 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
07-14 13:28:42.055  4818  4933 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.lool = 0
07-14 13:28:42.055  4818  4933 D BadgeCache: 1. updateBadgeCounts: com.wssyncmldm = 0
,07-14 13:28:42.058  4818  4933 D BadgeCache: updated Badged:0
07-14 13:28:42.058  4818  4933 D BadgeCache: updateBadgeCounts:0
,07-14 13:28:42.179  9972  9972 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-14 13:28:42.180  9972  9972 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-14 13:28:42.181  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9972
,07-14 13:28:42.181  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-14 13:28:42.181  9972  9972 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-14 13:28:42.182  9972  9972 I wpa_supplicant: ssSupport state is = 1
07-14 13:28:42.182  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-14 13:28:42.185  9972  9972 E wpa_supplicant: nl80211: Could not configure driver mode
07-14 13:28:42.185  9972  9972 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-14 13:28:42.185  9972  9972 E wpa_supplicant: p2p0: Failed to initialize driver interface
,07-14 13:28:42.188  9972  9972 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,07-14 13:28:42.188  9972  9972 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
07-14 13:28:42.190  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9972
,07-14 13:28:42.190  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,07-14 13:28:42.190  9972  9972 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-14 13:28:42.190  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-14 13:28:42.191  9972  9972 I wpa_supplicant: ssSupport state is = 1
,07-14 13:28:42.227  9972  9972 I wpa_supplicant: rfkill: Cannot get wiphy information
,07-14 13:28:42.242  9972  9972 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,07-14 13:28:42.258  3707  3908 D WifiService: setWifiEnabled: true pid=9513, uid=10033
07-14 13:28:42.259  3707  3908 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-14 13:28:42.260  3707  3908 D WifiControlHistoryProvider: query
,07-14 13:28:42.272  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-14 13:28:42.272  3707  3908 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-14 13:28:42.278  3707  3908 D SecContentProvider: called from android.uid.system:1000
,07-14 13:28:42.279  3707  3908 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-14 13:28:42.284  3707  3908 I WifiService: Wi-Fi Sharing settings has not been accessed
07-14 13:28:42.285  3707  3908 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-14 13:28:42.795  3707  3937 D WifiService: setWifiEnabled: true pid=9513, uid=10033
07-14 13:28:42.796  3707  3937 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-14 13:28:42.797  3707  3937 D WifiControlHistoryProvider: query
,07-14 13:28:42.810  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-14 13:28:42.811  3707  3937 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-14 13:28:42.813  3707  3937 D SecContentProvider: called from android.uid.system:1000
,07-14 13:28:42.815  3707  3937 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-14 13:28:42.822  3707  3937 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-14 13:28:42.823  3707  3937 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-14 13:28:42.849  3707  3792 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=203940 mStackState=3 mControllerTxTimeMs=0 mControllerTxTimePerLevelMs=[] mControllerRxTimeMs=0 mControllerIdleTimeMs=0 mControllerEnergyUsed=0 }
,07-14 13:28:42.891  9972  9972 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-14 13:28:42.894  3707  3927 I WifiConnectivityManager: User band preference: 0
,07-14 13:28:42.897  3707  3927 D WifiConfigManager: Loading config and enabling all networks 
,07-14 13:28:42.916  3707  3927 D WifiConfigStore: readNetwork skipInternetCheck
,07-14 13:28:42.943  3707  3927 D WifiConfigStore: readNetwork skipInternetCheck
,07-14 13:28:42.966  3707  3927 D WifiConfigStore: readNetwork skipInternetCheck
,07-14 13:28:42.999  3707  3927 D WifiConfigStore: readNetwork skipInternetCheck
,07-14 13:28:43.011  3707  3927 D WifiConfigStore: readNetwork skipInternetCheck
,07-14 13:28:43.025  3707  3927 D WifiConfigStore: readNetwork skipInternetCheck
,07-14 13:28:43.034  3707  3927 W WifiNetworkHistory: Upgrading network 4 to android.uid.system:1000
,07-14 13:28:43.034  3707  3927 W WifiNetworkHistory: Upgrading network 0 to android.uid.system:1000
07-14 13:28:43.035  3707  3927 W WifiNetworkHistory: Upgrading network 1 to android.uid.system:1000
,07-14 13:28:43.035  3707  3927 W WifiNetworkHistory: Upgrading network 5 to android.uid.system:1000
07-14 13:28:43.036  3707  3927 W WifiNetworkHistory: Upgrading network 2 to android.uid.system:1000
07-14 13:28:43.036  3707  3927 W WifiNetworkHistory: Upgrading network 3 to android.uid.system:1000
07-14 13:28:43.037  3707  3927 D WifiConfigManager: loaded 0 passpoint configs
,07-14 13:28:43.041  3707  3927 D WifiNative-wlan0: callSECApiBoolean - ID [301]
,07-14 13:28:43.041  3707  3707 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-14 13:28:43.041  3707  3707 D WifiHs20Service: reason: 2
07-14 13:28:43.041  3707  3954 I WifiHs20Service: Message received 5014
07-14 13:28:43.041  3707  3954 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
07-14 13:28:43.041  9972  9972 I wpa_supplicant: HOTSPOT20_ENABLE called ON
07-14 13:28:43.041  3707  3954 E WifiHs20Service: The changed config is NULL
,07-14 13:28:43.054  3707  3927 D WifiNative-wlan0: callSECApiInt - ID [65]
,07-14 13:28:43.058  3707  3707 D WifiController: [FCC]setFccChannel() is called !!!
,07-14 13:28:43.058  3707  3707 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
07-14 13:28:43.058  3707  3707 D WifiStateMachine: setFccChannel: channel = 0
07-14 13:28:43.058  3707  3707 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-14 13:28:43.059  3707  3707 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,07-14 13:28:43.059  3707  3953 D HS20StateMachine: WIFI_STATE_ENABLED
07-14 13:28:43.059  3707  3954 I WifiHs20Service: Message received 5011
07-14 13:28:43.059  3707  3953 D HS20StateMachine: reloadCredentialsToSupplicant
07-14 13:28:43.059  3707  3953 D WifiHs20DBHandler: getCredentialIds
07-14 13:28:43.061  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=3 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-14 13:28:43.064  3707  3707 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-14 13:28:43.064  3707  4238 D SLocation: checkWifiInfo
07-14 13:28:43.064  3707  4238 W SLocation: No Active Data Connection
,07-14 13:28:43.065  3707  4040 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-14 13:28:43.066  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-14 13:28:43.067  9640  9640 D A2dpService: A2dpService - WIFI_STATE_ENABLED
07-14 13:28:43.067  9640  9640 I BluetoothA2dpServiceJni: Attempting to set busy level
07-14 13:28:43.070  3707  4040 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-14 13:28:43.072  3707  3927 D WifiNative-wlan0: callSECApiBoolean - ID [13]
07-14 13:28:43.072  9972  9972 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-14 13:28:43.076  9513  9513 D BluetoothAdapter: STATE_ON
07-14 13:28:43.076  9396  9396 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-14 13:28:43.076  9396  9396 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,07-14 13:28:43.078  9396  9396 D SecurityLogAgent: NetworkReceiver : SendSecurityReport is off
07-14 13:28:43.078  3707  3953 D MountService: getExternalStorageMountMode : 1
07-14 13:28:43.078  3707  3953 D MountService: getExternalStorageMountMode : 3
07-14 13:28:43.078  3707  3953 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10114, packageName : com.samsung.hs20provider
,07-14 13:28:43.080  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-14 13:28:43.080  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:43.080  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:43.080  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-14 13:28:43.080  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-14 13:28:43.080  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-14 13:28:43.080  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-14 13:28:43.080  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-14 13:28:43.080  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-14 13:28:43.083  9513  9513 D BluetoothAdapter: STATE_ON
,07-14 13:28:43.086  9513  9513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,07-14 13:28:43.099  9990  9990 E Zygote  : v2
07-14 13:28:43.100  9990  9990 I libpersona: KNOX_SDCARD checking this for 10114
07-14 13:28:43.100  9990  9990 I libpersona: KNOX_SDCARD not a persona
,07-14 13:28:43.101  9990  9990 E Zygote  : accessInfo : 0
,07-14 13:28:43.102  9990  9990 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:43.104  9990  9990 I SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,07-14 13:28:43.107  3707  3953 I ActivityManager: Start proc 9990:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
,07-14 13:28:43.110  3707  3927 D WifiNative-HAL: Setting external_sim to 1
,07-14 13:28:43.111  3707  3927 D wifi    : setting dfs flag to true, 0x70ffae7560
,07-14 13:28:43.111  3707  3927 D WifiStateMachine: Setting OUI to DA-A1-19
,07-14 13:28:43.112  3707  3927 D wifi    : setting scan oui 0x70ffae7560
07-14 13:28:43.112  3707  3927 D WifiHAL : Sending mac address OUI
07-14 13:28:43.114  3707  3927 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
07-14 13:28:43.114  3707  3927 E WifiStateMachine: SupplicantStarted - enter() isAirplaneModeEnabled !!  
,07-14 13:28:43.114  3707  3927 D WifiCountryCode: [setCountryCodeNative] Default CSC Country Code : PL
,07-14 13:28:43.119  3707  3965 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:43.120  3707  3965 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.120  3707  3965 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.120  3707  3965 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.120  3707  3965 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.120  3707  3965 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.121  3707  3965 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.121  3707  3965 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.121  3707  3965 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.121  3707  3965 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:43.134  3707  4313 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:43.135  3707  4313 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:43.135  3707  4313 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.135  3707  4313 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.135  3707  4313 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.136  3707  4313 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.136  3707  4313 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.136  3707  4313 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.136  3707  4313 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.136  3707  4313 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.138  9990  9990 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:43.139  9990  9990 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:43.143  3707  3908 I ActivityManager: DSS on for com.samsung.hs20provider and scale is 1.0
,07-14 13:28:43.157  3707  3937 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:43.158  3707  3937 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.158  3707  3937 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.159  3707  3937 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.159  3707  3937 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.159  3707  3937 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.160  3707  3937 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.160  3707  3937 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.160  3707  3937 W NetworkIdentity: Active mobile network without subscriber!
07-14 13:28:43.160  3707  3937 W NetworkIdentity: Active mobile network without subscriber!
,07-14 13:28:43.165  9972  9972 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-14 13:28:43.167  3707  3927 D WifiCountryCode: Succeeded to set country code to: PL
,07-14 13:28:43.167  3707  3927 D wifi    : android_net_wifi_get_firmware_version = 0x70ffae7560
07-14 13:28:43.167  3707  3927 E WifiHAL : Failed to register debug response; result = -95
07-14 13:28:43.167  3707  3927 E wifi    : Fail to get Firmware version
07-14 13:28:43.167  3707  3927 D wifi    : android_net_wifi_get_driver_version = 0x70ffae7560
07-14 13:28:43.167  3707  3927 E WifiHAL : Failed to register debug response; result = -95
07-14 13:28:43.167  3707  3927 E wifi    : Fail to get driver version
07-14 13:28:43.167  3707  3927 D wifi    : android_net_wifi_set_log_handler = 0x70ffae7560
07-14 13:28:43.168  3707  3927 D wifi    : android_net_wifi_get_ring_buffer_status = 0x70ffae7560
07-14 13:28:43.168  3707  3927 E WifiHAL : Failed to register debug response; result = -95
07-14 13:28:43.168  3707  3927 E WifiLogger: no ring buffers found
07-14 13:28:43.168  3707  3927 D WifiHAL : Start get packet fate command
07-14 13:28:43.168  3707  3927 D WifiHAL : createRequest Monitor packet fate request
07-14 13:28:43.168  3707  3927 E WifiHAL : Failed to register get pkt fate response; result = -95
07-14 13:28:43.168  3707  3927 E WifiLogger: Failed to start packet fate monitoring
,07-14 13:28:43.169  3707  4015 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
07-14 13:28:43.170  9990  9990 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,07-14 13:28:43.186  9990  9990 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:43.197  3707  3923 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-14 13:28:43.198  3707  3927 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-14 13:28:43.199  3707  3955 I WifiScanningService: wifi driver loaded with scan capabilities: max buckets=16
,07-14 13:28:43.199  3707  3927 I WifiConnectivityManager: Set WiFi enabled
,07-14 13:28:43.199  3707  3927 E WifiStateMachine: ConnectModeState - enter !! - mIsSupportGeofence !!
07-14 13:28:43.200  3707  3707 I WifiStateMachine: initGeofence
07-14 13:28:43.200  3707  3927 D WifiStateMachine: Remembered scan first is enabled
07-14 13:28:43.201  3295  3781 D CommandListener: Setting iface cfg
07-14 13:28:43.201  3295  3781 D CommandListener: Trying to bring up p2p0
07-14 13:28:43.202  3295  3771 D Netd    : Iface p2p0 link up
07-14 13:28:43.204  3707  3801 D Tethering: interfaceLinkStateChanged p2p0, true
07-14 13:28:43.204  3707  3923 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-14 13:28:43.204  3707  3801 D Tethering: interfaceStatusChanged p2p0, true
07-14 13:28:43.205  3707  3923 D SecContentProvider: insert(), uri = 2
07-14 13:28:43.207  3707  3923 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:43.207  3707  3923 D WifiP2pService: P2pEnablingState
07-14 13:28:43.208  3707  3923 D WifiP2pService: P2pEnablingState{ what=147457 }
07-14 13:28:43.208  3707  3923 D WifiP2pService: P2p socket connection successful
07-14 13:28:43.209  3707  3923 D WifiP2pService: P2pEnabledState
07-14 13:28:43.209  3707  3923 D SecContentProvider: insert(), uri = 2
07-14 13:28:43.210  3707  3923 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:43.212  3707  3803 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-14 13:28:43.212  3707  3803 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-14 13:28:43.212  3707  3803 D WifiDisplayController: disconnect
07-14 13:28:43.212  3707  3803 D WifiDisplayAdapter: onFeatureStateChanged empty
07-14 13:28:43.212  3707  3803 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-14 13:28:43.213  3707  3923 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-14 13:28:43.213  3707  3958 D ConnectivityService: ignoring duplicate network state non-change
07-14 13:28:43.217  3707  3927 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@7962b18
07-14 13:28:43.217  9990 10001 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-14 13:28:43.218  3707  3927 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
07-14 13:28:43.218  9990 10001 D HotspotProvider: CREDENTIAL
07-14 13:28:43.218  9990 10001 D HotspotProvider: No prepend tags
07-14 13:28:43.218  3707  3927 E wifi    : failed to get channel list : -95
07-14 13:28:43.218  3707  3927 D WifiConfigManager: getChannelsForBand(WifiScanner.WIFI_BAND_24_GHZ) is null. So set default 2.4GHz 14 channels.
07-14 13:28:43.220  9972  9972 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-14 13:28:43.221  9972  9972 I wpa_supplicant: P2P: Current p2p state = IDLE
07-14 13:28:43.225  9972  9972 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-14 13:28:43.225  3707  3803 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
07-14 13:28:43.229  9972  9972 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
07-14 13:28:43.231  9972  9972 I wpa_supplicant: P2P: Set Samsung Discovery name = 
07-14 13:28:43.240  3707  3927 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170714T132851 - CU:1000/CP:3707
07-14 13:28:43.240  3707  3927 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132851, SetElapsed=212336, nowELAPSED=204356
07-14 13:28:43.243  3707  3955 D SamsungAlarmManager: setInexact Listener (T:2/F:,8/AC:false) 20170714T132858 - CU:1000/CP:3707
07-14 13:28:43.245  9901  9901 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
07-14 13:28:43.246  9901  9901 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
07-14 13:28:43.246  9901  9901 D FileShare: Outbound.stopDelayTimer - 
07-14 13:28:43.248  3707  3927 D WifiStateMachine: setFccChannelNative: channel = 0
07-14 13:28:43.248  3707  3927 D WifiNative-wlan0: callSECApiInt - ID [230]
07-14 13:28:43.251  4043  4055 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
07-14 13:28:43.265  3707  3927 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-14 13:28:43.270  3707  3927 D WifiNative-wlan0: callSECApiVoid - ID [311]
07-14 13:28:43.271  3707  3953 D HS20StateMachine: updateNumOfHS20Cred, numOfHS20Cred = 1
07-14 13:28:43.271  3707  3927 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-14 13:28:43.271  3707  3953 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
07-14 13:28:43.272  3707  3953 D HS20StateMachine: enter : DiscoveringState
07-14 13:28:43.278  3707  3707 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-14 13:28:43.279  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:43.280  3707  3707 D SLocation: system
07-14 13:28:43.280  3707  3707 D SLocation: startGeofence ID = 1
07-14 13:28:43.283  4738  4812 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 4ms lastUpdatedAfter : 6650 ms mFlush_time_threasold : 2000 mCurrentSize : 184
07-14 13:28:43.284  3707  3923 E WifiP2pService: Failed to set my phone number info into probe response
07-14 13:28:43.285  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:43.300  3707  3923 D WifiNative-HAL: p2pGetDeviceAddress
,07-14 13:28:43.300  3707  3923 D WifiNative-HAL: p2pGetDeviceAddress returning 4e:66:41:a9:15:41
07-14 13:28:43.301  3707  3923 D WifiP2pService: DeviceAddress: 4e:15:41
,07-14 13:28:43.302  3707  3803 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:15:41
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  primary type: 10-0050F204-5
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  secondary type: null
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  wps: 0
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  grpcapab: 0
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  devcapab: 0
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  status: 3
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  WFD CtrlPort: 0
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  WFD MaxThroughput: 0
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  groupownerAddress: null
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  GOdeviceName: null
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  interfaceAddress: 
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  SConnectInfo : null
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  contactInfoHash : null
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  ssDevInfo : 0
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  iconIdx : 0
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  semSamsungDeviceType : 0
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  serviceData : null
07-14 13:28:43.302  3707  3803 D WifiDisplayController:  fw_invite : 0
,07-14 13:28:43.310  3707  3923 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-14 13:28:43.311  3707  3923 D WifiP2pService: InactiveState
07-14 13:28:43.311  3707  3923 D WifiP2pService: InactiveState{ what=143376 }
07-14 13:28:43.311  3707  3923 D WifiP2pService: P2pEnabledState{ what=143376 }
07-14 13:28:43.311  3707  3923 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
07-14 13:28:43.311  3707  3707 D SLocation: addReceiver type4
07-14 13:28:43.311  3707  3707 D SLocation: already exsit record!
,07-14 13:28:43.331  9513  9599 D BluetoothAdapter: STATE_ON
,07-14 13:28:43.333  9513  9599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-14 13:28:43.333  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:43.333  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:43.333  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-14 13:28:43.333  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-14 13:28:43.333  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-14 13:28:43.333  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-14 13:28:43.333  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-14 13:28:43.333  9513  9599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-14 13:28:43.334  9513  9577 D BluetoothAdapter: enable()
,07-14 13:28:43.338  9640  9652 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-14 13:28:43.338  9640  9652 D AdapterProvider: query
,07-14 13:28:43.343  3707  3707 D SLocation: setPendingIntent
07-14 13:28:43.343  3707  3707 D SLocation: setStatus ID = 1 / status = 3
,07-14 13:28:43.346  9640  9652 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@fa06e16
,07-14 13:28:43.347  9640  9652 D BluetoothAdapterService: updateEvent - already set, update
,07-14 13:28:43.348  9640  9652 W BluetoothAdapterService: updateEvent - alreadySet is true
07-14 13:28:43.348  9640  9652 D AdapterProvider: update
,07-14 13:28:43.351  9640  9652 E BluetoothAdapterService: updateEvent - update success 1
,07-14 13:28:43.352  9513  9577 D BluetoothAdapter: enable(): BT is already enabled..!
,07-14 13:28:43.358  3707  4679 D WifiService: setWifiEnabled: true pid=9513, uid=10033
07-14 13:28:43.358  3707  4679 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-14 13:28:43.358  3707  4679 D WifiControlHistoryProvider: query
,07-14 13:28:43.363  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-14 13:28:43.364  3707  4679 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-14 13:28:43.365  3707  4679 D SecContentProvider: called from android.uid.system:1000
,07-14 13:28:43.365  3707  4679 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-14 13:28:43.369  3707  4679 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-14 13:28:43.370  3707  4679 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-14 13:28:43.370  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-14 13:28:43.370  9513  9577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-14 13:28:43.370  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-14 13:28:43.370  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-14 13:28:43.370  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-14 13:28:43.370  9513  9577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a32fb7a removed from the list
07-14 13:28:43.371  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a32fb7a removed from the list
07-14 13:28:43.371  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-14 13:28:43.371  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab06f2b removed from the list
07-14 13:28:43.371  9513  9577 D io.jxcore.node.ConnectivityMonitor: stop
07-14 13:28:43.371  9513  9577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-14 13:28:43.371  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-14 13:28:43.373  9513  9577 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,07-14 13:28:43.376  9513 10004 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
07-14 13:28:43.376  9513 10004 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-14 13:28:43.406  3707  3707 D SLocation: geofence id (1) detected : 0
,07-14 13:28:43.407  3707  3707 D WifiStateMachine: startGeofence() - id : 1
,07-14 13:28:43.407  3707  3707 D RttService: SCAN_AVAILABLE : 3
07-14 13:28:43.407  3707  3957 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-14 13:28:43.412  3707  3707 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
07-14 13:28:43.413  3707  3707 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
,07-14 13:28:43.415  4043  4055 D TelephonyProvider: query: match = 7
,07-14 13:28:43.419  3707  3707 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,07-14 13:28:43.423  3707  3707 D SLocation: PendingIntent onSendFinished id:1
,07-14 13:28:43.798  3295  3771 D Netd    : Iface wlan0 link up
,07-14 13:28:43.802  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:28:43.802  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
,07-14 13:28:43.803  9972  9972 I wpa_supplicant: nl80211: Received scan results (29 BSSes)
,07-14 13:28:43.810  3707  3955 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@bb81ec9
,07-14 13:28:43.843  3707  3927 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-14 13:28:43.855  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:43.864  3707  3927 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=4 roam=false
,07-14 13:28:43.867  3707  3927 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=4
,07-14 13:28:43.880  3295  3774 D EnterpriseController: netId is 0
07-14 13:28:43.880  3295  3774 D Netd    : getNetworkForDns: using netid 0 for uid 10033
07-14 13:28:43.880  3295  3774 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-14 13:28:43.884  3707  3927 D WifiConfigStore: saveNetwork skipInternetCheck
07-14 13:28:43.884  9513 10006 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
07-14 13:28:43.885  9513 10004 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,07-14 13:28:43.887  9513 10006 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,07-14 13:28:43.888  9513 10004 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
07-14 13:28:43.888  9513 10006 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-14 13:28:43.888  9513 10004 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-14 13:28:43.888  9513 10006 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-14 13:28:43.890  9513 10004 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-14 13:28:43.890  9513 10006 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,07-14 13:28:43.892  9513 10004 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,07-14 13:28:43.892  9513 10008 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 222, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.892  9513 10008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:43.892  9513 10008 D io.jxcore.node.StreamCopyingThread:  id: 74
,07-14 13:28:43.895  9513 10010 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 224, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.895  9513 10010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:43.895  9513 10010 D io.jxcore.node.StreamCopyingThread:  id: 74
,07-14 13:28:43.895  9513 10009 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 223, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.895  9513 10009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:43.895  9513 10009 D io.jxcore.node.StreamCopyingThread:  id: 75
,07-14 13:28:43.895  9513 10011 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 225, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.895  9513 10011 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:43.895  9513 10011 D io.jxcore.node.StreamCopyingThread:  id: 75
07-14 13:28:43.896  3707  3927 D WifiConfigStore: readNetwork skipInternetCheck
07-14 13:28:43.896  9513 10011 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 225, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.896  9513 10011 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:43.896  9513 10011 D io.jxcore.node.StreamCopyingThread:  id: 75
07-14 13:28:43.896  9513 10011 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.896  9513 10011 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:43.896  9513 10011 D io.jxcore.node.StreamCopyingThread:  id: 75
07-14 13:28:43.896  9513 10011 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-14 13:28:43.896  9513 10011 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-14 13:28:43.897  9513 10010 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 224, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.897  9513 10010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:43.897  9513 10010 D io.jxcore.node.StreamCopyingThread:  id: 74
,07-14 13:28:43.897  9513 10010 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.897  9513 10010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:43.897  9513 10010 D io.jxcore.node.StreamCopyingThread:  id: 74
07-14 13:28:43.897  9513 10010 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,07-14 13:28:43.898  9513 10010 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-14 13:28:43.898  9513 10011 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-14 13:28:43.898  9513 10011 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-14 13:28:43.898  9513 10010 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-14 13:28:43.898  9513 10011 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-14 13:28:43.898  9513 10010 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-14 13:28:43.898  9513 10011 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
07-14 13:28:43.898  9513 10010 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-14 13:28:43.899  9513 10010 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
07-14 13:28:43.899  9513 10011 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 225, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.899  9513 10011 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:43.899  9513 10011 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
07-14 13:28:43.899  9513 10010 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 224, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.899  9513 10010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:43.899  9513 10010 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,07-14 13:28:43.899  9513 10009 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 223, thread name: OutgoingSocketThread/Sender): Socket closed
07-14 13:28:43.900  9513 10009 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 223, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.900  9513 10009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:43.900  9513 10009 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-14 13:28:43.900  9513 10008 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 222, thread name: IncomingSocketThread/Sender): Socket closed
07-14 13:28:43.900  9513 10009 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-14 13:28:43.900  9513 10009 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-14 13:28:43.900  9513 10008 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 222, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.900  9513 10008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:43.900  9513 10008 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
07-14 13:28:43.900  9513 10008 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-14 13:28:43.900  9513 10009 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 223, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.900  9513 10009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:43.900  9513 10009 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-14 13:28:43.900  9513 10008 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-14 13:28:43.900  9513 10008 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 222, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:43.900  9513 10008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:43.900  9513 10008 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,07-14 13:28:43.910  3707 10012 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
07-14 13:28:43.910  3707 10012 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
,07-14 13:28:43.911  3707 10012 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-14 13:28:43.911  3707 10012 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
,07-14 13:28:43.912  3707 10012 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-14 13:28:43.912  3707 10012 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-14 13:28:43.913  3707 10012 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
,07-14 13:28:43.913  3707 10012 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-14 13:28:43.913  3707 10012 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-14 13:28:43.914  3707 10012 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
,07-14 13:28:43.914  3707 10012 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-14 13:28:43.915  3707 10012 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
,07-14 13:28:43.917  3707  3927 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=4
07-14 13:28:43.918  3707  3707 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-14 13:28:43.918  3707  3707 D WifiHs20Service: reason: 2
,07-14 13:28:43.919  3707  3954 I WifiHs20Service: Message received 5014
07-14 13:28:43.919  3707  3954 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,07-14 13:28:43.921  3707 10013 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
07-14 13:28:43.921  3707 10013 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
,07-14 13:28:43.922  3707 10013 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-14 13:28:43.922  3707 10013 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-14 13:28:43.922  9972  9972 I wpa_supplicant: Trying to associate with F4.E6.C2 (SSID='NG700' freq=2472 MHz)
07-14 13:28:43.922  3707 10013 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-14 13:28:43.923  3707 10013 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-14 13:28:43.923  3707  3927 D SecContentProvider: insert(), uri = 2
07-14 13:28:43.923  3707 10013 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-14 13:28:43.923  3707 10013 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-14 13:28:43.924  3707  3927 D SecContentProvider: called from android.uid.system:1000
07-14 13:28:43.924  3707 10013 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
,07-14 13:28:43.925  3707 10013 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-14 13:28:43.925  3707 10013 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-14 13:28:43.925  3707 10013 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
,07-14 13:28:43.939  3707  3927 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-14 13:28:43.948  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:44.064  3295  3771 D Netd    : Iface wlan0 link up
07-14 13:28:44.064  3295  3771 D Netd    : Iface wlan0 link up
07-14 13:28:44.065  3295  3771 D Netd    : Iface wlan0 link up
,07-14 13:28:44.068  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:28:44.068  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
07-14 13:28:44.070  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:28:44.071  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
,07-14 13:28:44.074  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:28:44.074  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
,07-14 13:28:44.080  9972  9972 I wpa_supplicant: Associated with F4.E6.C2
,07-14 13:28:44.083  9972  9972 I wpa_supplicant: wlan0: CTRL-EVENT-SUBNET-STATUS-UPDATE status=0
,07-14 13:28:44.087  3707  3927 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-14 13:28:44.092  3707  3927 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-14 13:28:44.098  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:44.102  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:44.144  9972  9972 I wpa_supplicant: WPA: Key negotiation completed with F4.E6.C2 [PTK=CCMP GTK=CCMP]
,07-14 13:28:44.144  9972  9972 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.E6.C2 completed [id=4 id_str=%7B%22creatorUid%22%3A%221000%22%2C%22configKey%22%3A%22%5C%22NG700%5C%22WPA_PSK%22%7D]
,07-14 13:28:44.145  3295  3771 D Netd    : Iface wlan0 link up
07-14 13:28:44.147  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:28:44.147  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
07-14 13:28:44.148  3707  3927 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-14 13:28:44.152  3707  3927 D WifiNative-wlan0: callSECApiVoid - ID [50]
,07-14 13:28:44.157  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-14 13:28:44.158  3707  3927 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@bc8e3c8
07-14 13:28:44.159  3707  3927 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T134538, SetElapsed=1219171, nowELAPSED=205275
07-14 13:28:44.159  3707  3707 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-14 13:28:44.160  3707  3707 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-14 13:28:44.160  3707  3954 I WifiHs20Service: Message received 5007
07-14 13:28:44.162  3707  4015 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-14 13:28:44.162  3707  3927 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: mIsSupportAdvancedCaptivePortal is true
07-14 13:28:44.162  3707  3927 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-14 13:28:44.163  3707 10014 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=69632 obj=com.android.internal.util.AsyncChannel@e022a36 target=com.android.internal.util.StateMachine$SmHandler }
07-14 13:28:44.163  3707 10014 D NetworkMonitor: Async - Half connection with WWSM established
07-14 13:28:44.163  3707  3958 D ConnectivityService: Got NetworkAgent Messenger
07-14 13:28:44.163  3707  3958 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-14 13:28:44.163  3707  3958 D ConnectivityService: NetworkAgent connected
,07-14 13:28:44.163  3707  4015 D WifiWatchdogStateMachine: Async - Half connection with NetworkMonitor established
07-14 13:28:44.164  3707  4015 D WifiWatchdogStateMachine: Async - Full connection with NetworkMonitor established
,07-14 13:28:44.167  4043  4043 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
07-14 13:28:44.167  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-14 13:28:44.169  3707  3923 D WifiP2pService: InactiveState{ what=143375 }
,07-14 13:28:44.169  3707  3923 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-14 13:28:44.170  9640  9640 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-14 13:28:44.171  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-14 13:28:44.174  3707  3927 D WifiHAL : Getting APF capabilities, halHandle = 0x70ffae7560
07-14 13:28:44.174  3707  3927 I WifiHAL : 
07-14 13:28:44.174  3707  3927 I WifiHAL : createRequest: APF get capabilities request
,07-14 13:28:44.176  3707  3927 D WifiHAL : In SetAPFCommand::handleResponse
07-14 13:28:44.176  3707  3927 D WifiHAL : Id = 0, subcmd = 0, len = 16
07-14 13:28:44.176  3707  3927 D WifiHAL : Response recieved for get packet filter capabilities command
07-14 13:28:44.176  3707  3927 I WifiHAL : APF version is 2
07-14 13:28:44.176  3707  3927 I WifiHAL : APF max len is 2048
07-14 13:28:44.176  3707  3927 I WifiHAL : Done!
07-14 13:28:44.176  3707  3927 D WifiHAL : Getting APF capability, version = 2, max_len = 2048
07-14 13:28:44.176  3707  3927 D wifi    : APF version supported: 2
07-14 13:28:44.176  3707  3927 D wifi    : Maximum APF program size: 2048
,07-14 13:28:44.179  3707  3927 D WifiStateMachine: Start Dhcp Watchdog 2
07-14 13:28:44.187  9734  9734 I [RBL] ServiceReceiver: @onReceive - rawData : null
07-14 13:28:44.190  3707 10015 D ApfFilter: (wlan0): begin monitoring
,07-14 13:28:44.204  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-14 13:28:44.210  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-14 13:28:44.211  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-14 13:28:44.211  9750  9750 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-14 13:28:44.211  9750  9750 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-14 13:28:44.213  3707  3958 D ConnectivityService: ignoring duplicate network state non-change
07-14 13:28:44.213  3707  3927 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true)
07-14 13:28:44.213  3707  3927 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true) returned: -95
07-14 13:28:44.213  3707  3958 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-14 13:28:44.214  3707  3958 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-14 13:28:44.214  3707  3958 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,07-14 13:28:44.215  3707  3927 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-14 13:28:44.219  9766  9766 I PhoneErrorReceiver: onReceive
,07-14 13:28:44.221  3707  3927 D WifiHAL : Setting APF program, halHandle = 0x70ffae7560
07-14 13:28:44.221  3707  3927 I WifiHAL : 
07-14 13:28:44.221  3707  3927 I WifiHAL : createRequest: APF set program request
,07-14 13:28:44.222  3707  3927 I WifiHAL : Done!
,07-14 13:28:44.225  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-14 13:28:44.229  9415  9415 I usagelog: received in receiver
07-14 13:28:44.229  9415  9415 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-14 13:28:44.229  9415  9415 I KnoxUsageLogPro: premStatus:2
,07-14 13:28:44.230  9415  9415 I KnoxUsageLogPro: isEulaShown : false
07-14 13:28:44.230  9415  9415 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-14 13:28:44.237  3707  3932 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170714T132920 - CU:1000/CP:3707
07-14 13:28:44.237  3707  3932 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132920, SetElapsed=241346, nowELAPSED=205353
,07-14 13:28:44.239  3707  4015 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-14 13:28:44.239  3707  3958 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
,07-14 13:28:44.239  3707  4015 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-14 13:28:44.240  3707  4015 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
,07-14 13:28:44.240  3707  4015 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-14 13:28:44.240  3707  4015 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-14 13:28:44.245  9972  9972 I wpa_supplicant: Interworking: Fetch ANQP after connect
,07-14 13:28:44.300  3707  3932 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170714T132920 - CU:1000/CP:3707
,07-14 13:28:44.410  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=start target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-14 13:28:44.410  3707  3923 D WifiP2pService: InactiveState{ what=143375 }
07-14 13:28:44.410  3707  3923 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-14 13:28:44.416  3707 10016 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170714T132846 - CU:1000/CP:3707
07-14 13:28:44.416  3707 10016 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132846, SetElapsed=207528, nowELAPSED=205532
,07-14 13:28:44.417  3707 10016 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
07-14 13:28:44.418  3707 10016 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@d815240
,07-14 13:28:44.419  3707 10016 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132920, SetElapsed=241346, nowELAPSED=205534
,07-14 13:28:44.421  3707 10016 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170714T132902 - CU:1000/CP:3707
07-14 13:28:44.422  3707 10016 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132902, SetElapsed=223535, nowELAPSED=205537
,07-14 13:28:44.426  3707 10016 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170714T132846 - CU:1000/CP:3707
07-14 13:28:44.427  3707 10016 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132846, SetElapsed=207695, nowELAPSED=205542
,07-14 13:28:44.436  3707 10016 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
07-14 13:28:44.437  3707  3932 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@6af9172
,07-14 13:28:44.438  3707 10016 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@51a4f1f
07-14 13:28:44.439  3707 10016 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132902, SetElapsed=223535, nowELAPSED=205554
07-14 13:28:44.439  3707 10016 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@5e152be
07-14 13:28:44.440  3707 10016 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132920, SetElapsed=241346, nowELAPSED=205555
,07-14 13:28:44.442  3295  3781 D CommandListener: Setting iface cfg
,07-14 13:28:44.449  3707  3932 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@1a1ae7d
07-14 13:28:44.449  3707  3923 D WifiP2pService: InactiveState{ what=143375 }
07-14 13:28:44.450  3707  3923 D WifiP2pService: P2pEnabledState{ what=143375 }
07-14 13:28:44.450  3707  3932 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T134538, SetElapsed=1219171, nowELAPSED=205566
07-14 13:28:44.452  3707 10016 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170714T191420 - CU:1000/CP:3707
,07-14 13:28:44.453  3707  4015 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-14 13:28:44.454  3707  3958 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-14 13:28:44.455  3707  3958 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
07-14 13:28:44.455  3707  4015 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-14 13:28:44.455  3707  3927 D WifiHAL : Setting APF program, halHandle = 0x70ffae7560
07-14 13:28:44.455  3707  3927 I WifiHAL : 
07-14 13:28:44.455  3707  3927 I WifiHAL : createRequest: APF set program request
07-14 13:28:44.456  3707  4015 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-14 13:28:44.456  3707  4015 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
07-14 13:28:44.457  3707  4015 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-14 13:28:44.457  3707  4015 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-14 13:28:44.457  3707 10016 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170714T235844 - CU:1000/CP:3707
07-14 13:28:44.458  3707  3927 I WifiHAL : Done!
,07-14 13:28:44.459  3707  3958 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
07-14 13:28:44.459  3707  3958 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
,07-14 13:28:44.459  3707  4015 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-14 13:28:44.460  3707  4015 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-14 13:28:44.460  3707  3927 E WifiNative-HAL: setBssidBlacklist cmd 2 size 0
07-14 13:28:44.460  3707  4015 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-14 13:28:44.460  3707  3927 D wifi    : configure BSSID black list request [4] = 0x70ffae7560
07-14 13:28:44.460  3707  3927 D wifi    : Added 0 bssids
07-14 13:28:44.460  3707  3927 E WifiHAL : Failed to execute bssid blacklist request, result = -95
,07-14 13:28:44.461  3707  3927 D WifiStateMachine: sendConnectedState - setManualConnection: false!
,07-14 13:28:44.461  3707  4015 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-14 13:28:44.462  3707  3958 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-14 13:28:44.463  3707  3958 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,07-14 13:28:44.464  3707  3958 D ConnectivityService: Adding iface wlan0 to network 503
07-14 13:28:44.465  3707  3707 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-14 13:28:44.466  3707  3707 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-14 13:28:44.466  3707  3954 I WifiHs20Service: Message received 5007
07-14 13:28:44.468  3707  4015 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,07-14 13:28:44.473  4043  4043 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
07-14 13:28:44.474  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-14 13:28:44.477  9640  9640 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-14 13:28:44.480  3707 10016 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170715T012844 - CU:1000/CP:3707
07-14 13:28:44.481  3707 10016 D DhcpClient: Scheduling renewal in 20735s
07-14 13:28:44.481  3707 10016 D DhcpClient: Scheduling rebind in 37799s
07-14 13:28:44.481  3707 10016 D DhcpClient: Scheduling expiry in 43199s
,07-14 13:28:44.482  3707  3927 D SecContentProvider: insert(), uri = 2
07-14 13:28:44.482  3707  3927 D SecContentProvider: called from android.uid.system:1000
,07-14 13:28:44.483  3707  3927 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-14 13:28:44.484  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-14 13:28:44.485  3707  3927 I WifiConnectivityManager: scheduleWatchdogTimer
07-14 13:28:44.485  3239  3239 E audit   : type=1320 audit(1500031724.478:237): 
07-14 13:28:44.486  3707  3707 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-14 13:28:44.487  3707  3707 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-14 13:28:44.487  3707  3707 D HS20StateMachine: SSID : "NG700"
07-14 13:28:44.487  3707  3707 D HS20StateMachine: NetId : 4
07-14 13:28:44.487  3707  3707 D HS20StateMachine: checkifOSUAP  null
,07-14 13:28:44.488  3707  3707 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,07-14 13:28:44.489  3707  3954 I WifiHs20Service: Message received 5007
,07-14 13:28:44.489  3707  4015 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-14 13:28:44.492  4043  4043 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
07-14 13:28:44.493  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-14 13:28:44.500  9640  9640 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-14 13:28:44.508  9734  9734 I [RBL] ServiceReceiver: @onReceive - rawData : null
07-14 13:28:44.509  3239  3239 E audit   : type=1320 audit(1500031724.498:238): 
07-14 13:28:44.510  3707  3927 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T133101, SetElapsed=342758, nowELAPSED=205625
07-14 13:28:44.510  3707  3927 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170714T134844 - CU:1000/CP:3707
07-14 13:28:44.510  3707  3927 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T134844, SetElapsed=1405601, nowELAPSED=205626
07-14 13:28:44.513  3707  3958 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
07-14 13:28:44.515  3707  3958 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,07-14 13:28:44.517  3707  3958 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
07-14 13:28:44.519  3707  3927 D WifiStateMachine: isFindLocationId() - Location Id : 1
07-14 13:28:44.520  3707  3958 D ConnectivityService: Setting DNS servers for network 503 to [/192.168.1.1]
07-14 13:28:44.521  3295  4195 D ResolverController: DNSDBG::server[0] 192.168.1.1
07-14 13:28:44.521  3295  4195 D ResolverController: DNSDBG::netId 503 search_domain lan
07-14 13:28:44.521  3295  4195 D ResolverController: DNSDBG::netId 503 searchDomains lan
07-14 13:28:44.521  3295  4195 D ResolverController: DNSDBG::server[0] 192.168.1.1
,07-14 13:28:44.529  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-14 13:28:44.530  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-14 13:28:44.530  9750  9750 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-14 13:28:44.531  9750  9750 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-14 13:28:44.533  3707  3958 V NetworkStats: updateIfacesLocked()
07-14 13:28:44.533  3707  3958 V NetworkStats: performPollLocked(flags=0x1)
07-14 13:28:44.533  3707  3958 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:44.536  3707  3927 D WifiGeofenceDBHelper: update() - 1*1500031724519
,07-14 13:28:44.542  3707  3958 V NetworkStats: performPollLocked() took 9ms
07-14 13:28:44.543  3707  3958 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:44.551  9766  9766 I PhoneErrorReceiver: onReceive
07-14 13:28:44.552  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:44.552  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:44.555  3707  3958 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-14 13:28:44.555  3707  3958 D ConnectivityService: Not required to send intent.
07-14 13:28:44.556  3707  3958 V NetworkStats: updateIfacesLocked()
07-14 13:28:44.556  3707  3958 V NetworkStats: performPollLocked(flags=0x1)
07-14 13:28:44.556  3707  3958 D NtpTrustedTime: currentTimeMillis() cache hit
,07-14 13:28:44.564  3707  3958 V NetworkStats: performPollLocked() took 7ms
,07-14 13:28:44.564  3707  3958 D NtpTrustedTime: currentTimeMillis() cache hit
,07-14 13:28:44.569  9415  9415 I usagelog: received in receiver
,07-14 13:28:44.570  9415  9415 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-14 13:28:44.570  9415  9415 I KnoxUsageLogPro: premStatus:2
07-14 13:28:44.570  9415  9415 I KnoxUsageLogPro: isEulaShown : false
,07-14 13:28:44.570  9415  9415 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-14 13:28:44.571  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:44.571  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
,07-14 13:28:44.572  3707 10014 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-14 13:28:44.572  3707 10014 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
07-14 13:28:44.572  3707  3958 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
07-14 13:28:44.572  3707 10014 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: register CaptivePortalReceiver
07-14 13:28:44.572  3707  3958 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,07-14 13:28:44.572  3707  3958 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-14 13:28:44.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-14 13:28:44.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:44.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:44.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.573  3707  3958 D ConnectivityService: currentScore = 0, newScore = 20
07-14 13:28:44.573  3707  3958 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
07-14 13:28:44.573  3707  4015 D WifiWatchdogStateMachine: Connected - Move to CaptivePortalState
07-14 13:28:44.574  3707  3958 D ConnectivityService:    accepting network in place of null
07-14 13:28:44.574  3707  3958 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.574  3707  3923 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.574  3707  3923 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-14 13:28:44.574  3707  3923 D WIFI_P2P: evalRequest
07-14 13:28:44.574  3707  4024 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.574  3707  3923 D WIFI_P2P:   done
07-14 13:28:44.575  3707  4024 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-14 13:28:44.575  3707  4024 D Ethernet: evalRequest
07-14 13:28:44.575  3707  4024 D Ethernet:   done
07-14 13:28:44.575  4043  4043 D PhoneSwitcherNetworkRequstListener: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.576  4043  4043 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-14 13:28:44.576  4043  4043 D PhoneSwitcherNetworkRequstListener: evalRequest
07-14 13:28:44.576  4043  4043 D PhoneSwitcherNetworkRequstListener:   done
07-14 13:28:44.576  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-14 13:28:44.576  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.576  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.576  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [] ]
07-14 13:28:44.576  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:44.577  3707  3958 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified),, extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-14 13:28:44.577  3707  4015 E WifiWatchdogStateMachine: current state: com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalState@88bc428
07-14 13:28:44.584  3707  4015 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-14 13:28:44.590  3707  4015 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-14 13:28:44.591  3707  4015 D WifiWatchdogStateMachine: start to check Captive portal
07-14 13:28:44.595  3239  3239 E audit   : type=1320 audit(1500031724.588:239): 
07-14 13:28:44.597  9711 10023 I DatabaseHelper: android.app.Application@9def1ff
07-14 13:28:44.597  9711 10023 I DatabaseHelper: Create a DatabaseHelper
07-14 13:28:44.600  9734  9734 I [RBL] ServiceReceiver: @onReceive - rawData : null
07-14 13:28:44.600  9734  9734 W [RBL] ServiceReceiver: @onReceive - NETWORK_STATE_CHANGED_ACTION
07-14 13:28:44.608  3707  3927 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-14 13:28:44.608  3707  3927 D SLocation: system
07-14 13:28:44.608  3707  3927 D SLocation: startGeofence ID = 1
07-14 13:28:44.612  3239  3239 E audit   : type=1320 audit(1500031724.598:240): 
,07-14 13:28:44.615  9711 10023 I DataManager: checkResolution
07-14 13:28:44.616  3295  3781 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-14 13:28:44.617  9711 10023 I DataManager: Create a DataManager
,07-14 13:28:44.627  3239  3239 E audit   : type=1320 audit(1500031724.618:241): 
,07-14 13:28:44.639  3239  3239 E audit   : type=1320 audit(1500031724.628:242): 
,07-14 13:28:44.640  3295  3781 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-14 13:28:44.640  3707  3927 E SLocation: id 1 is already started
07-14 13:28:44.640  3707  3927 D WifiStateMachine: startGeofence() - id : 1, ERROR !!, mResult : -5
07-14 13:28:44.641  3707  3927 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-14 13:28:44.645  9734  9734 D [RBL] StoredRequest: @Oncreate
07-14 13:28:44.646  9734  9734 I [RBL] GuardedSuspension: @getInstance
07-14 13:28:44.646  3707  3927 D SLocation: system
07-14 13:28:44.646  9734  9734 I [RBL] GuardedSuspension: GuardedSuspension
07-14 13:28:44.646  3707  3927 D SLocation: startLearning ID = 1
07-14 13:28:44.646  3707  3927 D SLocation: setLearningStatus ID = 1 / status = true
07-14 13:28:44.646  3707  3927 D WifiStateMachine: ConnectedState - enter() - startLearning id : 1
07-14 13:28:44.646  3707  3927 D WifiStateMachine: ConnectedState()- id : 1,  startLearning Success !!
07-14 13:28:44.646  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-14 13:28:44.647  3707  3927 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-14 13:28:44.647  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-14 13:28:44.647  9750  9750 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-14 13:28:44.648  3707  3927 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.648  3707  3927 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-14 13:28:44.648  3707  3927 D WIFI_UT : evalRequest
07-14 13:28:44.648  3707  3927 D WIFI_UT :   done
07-14 13:28:44.649  3707  3927 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.649  3707  3927 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-14 13:28:44.649  3707  3927 D WIFI    : evalRequest
07-14 13:28:44.649  3707  3927 D WIFI    :   done
,07-14 13:28:44.649  9750  9750 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 android.content.ContextWrapper.sendBroadcast:452 android.content.ContextWrapper.sendBroadcast:452 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3306 
07-14 13:28:44.649  3707  3927 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-14 13:28:44.649  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.650  9734  9734 I [RBL] GuardedSuspension: @getInstance
07-14 13:28:44.650  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.650  9734  9734 D [RBL] RblSAccountUtil: @open
07-14 13:28:44.651  9734  9734 D [RBL] RblSAccountUtil:     - client : 1
07-14 13:28:44.651  4283  4404 D GeolocationController: WIFI : onAvailable
07-14 13:28:44.652  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.654  4283  4404 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [true]
07-14 13:28:44.656  3707  3802 D EntConnectivity: Not allowed due to - mEnabled false
07-14 13:28:44.659  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-14 13:28:44.660  9766  9766 I PhoneErrorReceiver: onReceive
07-14 13:28:44.660  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.661  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:44.661  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-14 13:28:44.661  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [] ]
07-14 13:28:44.662  4283  4418 D PdnController: handleMessage: what 105
07-14 13:28:44.662  4283  4418 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [true]
07-14 13:28:44.663  3707  3802 D EntConnectivity: Not allowed due to - mEnabled false
07-14 13:28:44.663  4283  4418 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [true]
07-14 13:28:44.664  4283  4418 D ResipRegiMgr: handleMessage(): 3
07-14 13:28:44.664  4283  4418 D RegiMgrBase: handleMessage: what 3
,07-14 13:28:44.667  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.669  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [] ]
07-14 13:28:44.670  3707  3958 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:44.670  3707  3958 D ConnectivityService: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
07-14 13:28:44.670  3707  3958 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-14 13:28:44.672  4283  4418 D RegiMgrBase: onNetworkEventChanged: new=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=true, isEpdgConnected=false]
07-14 13:28:44.673  4283  4418 D RegiMgrBase: onNetworkEventChanged: old=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=false, isEpdgConnected=false]
07-14 13:28:44.673  9711  9711 W RequestHeader: java.lang.StringIndexOutOfBoundsException: length=0; regionStart=0; regionLength=3
,07-14 13:28:44.673  4283  4418 D RegiMgrBase: out of service.
07-14 13:28:44.673  4283  4418 D RegiMgrBase: onNetworkEventChanged: nTask= 0 nRegisteredTask= 0 bExistRetryTimer= false bHaveRegisteringTask= false
07-14 13:28:44.673  9711  9711 W RequestHeader: java.lang.StringIndexOutOfBoundsException: length=0; index=3
07-14 13:28:44.677  9415  9415 I usagelog: received in receiver
07-14 13:28:44.677  9415  9415 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-14 13:28:44.677  9415  9415 I KnoxUsageLogPro: premStatus:2
07-14 13:28:44.677  9711  9711 W RequestHeaderForV3: java.lang.StringIndexOutOfBoundsException: length=0; regionStart=0; regionLength=3
07-14 13:28:44.677  9711  9711 W RequestHeaderForV3: java.lang.StringIndexOutOfBoundsException: length=0; index=3
07-14 13:28:44.678  9415  9415 I KnoxUsageLogPro: isEulaShown : false
07-14 13:28:44.678  9415  9415 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-14 13:28:44.679  4283  4418 D RegiMgrBase: onNetworkEventChanged: tryRegister
07-14 13:28:44.679  4283  4418 D RegiMgrBase: tryRegister:
07-14 13:28:44.682  4283  4418 D RegiMgrBase: RegisterTask(s) -
07-14 13:28:44.682  3707  3958 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
07-14 13:28:44.682  4283  4418 D ResipRegiMgr: handleMessage(): 32
07-14 13:28:44.682  4283  4418 D RegiMgrBase: handleMessage: what 32
07-14 13:28:44.682  4283  4418 D RegiMgrBase: onPendingUpdateRegistration: 
07-14 13:28:44.682  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.682  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-14 13:28:44.682  9734  9734 D [RBL] RblSAccountUtil:     - DB is opened
07-14 13:28:44.682  9734  9734 D [RBL] CellDbHelper: @open
07-14 13:28:44.682  9734  9734 D [RBL] CellDbHelper:     - client : 1
07-14 13:28:44.682  3707  3958 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=3, legacyType=-1, [] ]
07-14 13:28:44.683  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.683  3707  3958 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.683  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.683  3707  3958 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.683  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [] ]
07-14 13:28:44.683  3707  3958 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=7, legacyType=-1, [] ]
07-14 13:28:44.684  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.685  3707  3958 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.685  3707  3707 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-14 13:28:44.685  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.686  3707  3707 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = false
07-14 13:28:44.686  3707  3958 D ConnectivityService: sending notifi,cation PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.686  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.686  3707  3958 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.687  3707  3914 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
07-14 13:28:44.687  3707  3914 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
07-14 13:28:44.687  3707  3914 D EnterprisePremiumVpnPolicyServiceV2: run all vpn : runAllVpnService beginning
07-14 13:28:44.688  3707  3707 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-14 13:28:44.688  3707  3707 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
07-14 13:28:44.688  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:44.689  3707  3958 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:44.689  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.689  3707  3915 I KnoxVpnEngineService: vpn handle : Message received
07-14 13:28:44.689  3707  3915 I KnoxVpnEngineService: vpn handle : Message received
07-14 13:28:44.689  3707  3915 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = false
07-14 13:28:44.690  3707  3915 D KnoxVpnEngineService: run all vpn : runAllVpnService beginning
07-14 13:28:44.690  3707  3958 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:44.690  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:44.690  3707  3958 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:44.690  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:44.690  3707  3958 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:44.690  3707  3707 D Tethering: Tethering got CONNECTIVITY_ACTION
07-14 13:28:44.691  3707  3960 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
07-14 13:28:44.691  3707  3958 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-14 13:28:44.691  3707  3960 D Tethering: MasterInitialState.processMessage what=327683
07-14 13:28:44.701  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-14 13:28:44.703  5059  5059 I CastMediaRouteProvider: Network connectivity changed
07-14 13:28:44.705  4069  4348 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
07-14 13:28:44.710  9734  9734 D [RBL] CellDbHelper:     - DB is opened
07-14 13:28:44.710  9734  9734 D [RBL] PolicyDbHelper: @open
07-14 13:28:44.710  9734  9734 D [RBL] PolicyDbHelper:     - client : 1
07-14 13:28:44.711  3707  3918 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
,07-14 13:28:44.711  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:44.711  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:44.712  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:44.712  3707  3918 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
07-14 13:28:44.712  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:28:44.716  3707  3918 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
07-14 13:28:44.721  8861  8861 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
07-14 13:28:44.721  8861  8861 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
07-14 13:28:44.725  8861  8861 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 1
07-14 13:28:44.726  8861  8861 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
07-14 13:28:44.726  4753  4753 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-14 13:28:44.728  8913  8913 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@8a068c4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-14 13:28:44.732  8913  8913 I NetworkConnectivity: Network state changed: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]
07-14 13:28:44.735  9734  9734 D [RBL] PolicyDbHelper:     - DB is opened
07-14 13:28:44.736  9734 10030 D [RBL] StoredRequest: @onHandleIntent
,07-14 13:28:44.739  3707  3707 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
07-14 13:28:44.739  9734  9734 D [RBL] CellDbHelper: @close
07-14 13:28:44.739  9734  9734 D [RBL] CellDbHelper:     - client : 0
07-14 13:28:44.739  3707  3707 V MARsPolicyManager: DataConnection: true
07-14 13:28:44.739  9734  9734 D [RBL] CellDbHelper:     - DB is closed
07-14 13:28:44.739  9734  9734 D [RBL] PolicyDbHelper: @close
07-14 13:28:44.739  9734  9734 D [RBL] PolicyDbHelper:     - client : 0
07-14 13:28:44.739  3707  4238 D SLocation: checkWifiInfo
07-14 13:28:44.739  9734  9734 D [RBL] PolicyDbHelper:     - DB is closed
07-14 13:28:44.739  9734  9734 D [RBL] RblSAccountUtil: @close
07-14 13:28:44.739  9734  9734 D [RBL] RblSAccountUtil:     - client : 0
07-14 13:28:44.740  9734  9734 D [RBL] RblSAccountUtil:     - DB is closed
07-14 13:28:44.740  9734  9734 D [RBL] StoredRequest: @onDestroy
07-14 13:28:44.743  3707  4040 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-14 13:28:44.746  3707  4040 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-14 13:28:44.751  9513  9513 D BluetoothAdapter: STATE_ON
07-14 13:28:44.755  9513  9513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-14 13:28:44.755  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-14 13:28:44.755  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-14 13:28:44.755  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-14 13:28:44.755  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-14 13:28:44.755  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-14 13:28:44.755  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-14 13:28:44.755  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-14 13:28:44.755  9513  9513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-14 13:28:44.758  9513  9513 D BluetoothAdapter: STATE_ON
07-14 13:28:44.760  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
07-14 13:28:44.761  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-14 13:28:44.762  9750  9750 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
07-14 13:28:44.762  9513  9513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
07-14 13:28:44.778  3707  4238 D SLocation: cellLocation is null
07-14 13:28:44.790  8913  8913 I NetworkPolicyMonitor: Download-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
07-14 13:28:44.815  8913  8913 I NetworkPolicyMonitor: Stream-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
07-14 13:28:44.821  3707  4312 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@9799221 displayId=0
07-14 13:28:44.822  3707  4312 D InputTransport: Input channel constructed: fd=462
07-14 13:28:44.822  3707  4312 D InputTransport: Input channel constructed: fd=463
07-14 13:28:44.825  3707  4312 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
07-14 13:28:44.827  3707  4312 D InputTransport: Input channel destroyed: fd=463
07-14 13:28:44.828  4069  4348 D InputTransport: Input channel constructed: fd=148
07-14 13:28:44.828  4069  4348 D ViewRootImpl@c4465d0[Toast]: setView = android.widget.LinearLayout{f04e9c9 V.E...... ......I. 0,0-0,0 #10204d0 android:id/toast_layout_root} touchMode=true
,07-14 13:28:44.833  3707  4675 V WindowManager: Relayout Window{382e007d0 u0 Toast}: viewVisibility=0 req=755x150 WM.LayoutParams{(0,192)(wrapxwrap) gr=#51 sim=#20 ty=2005 fl=#1040088 fmt=-3 wanim=0x1030004 naviIconColor=0}
07-14 13:28:44.834  3113  3113 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=4, Uoast
07-14 13:28:44.842  3707  4675 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3707 ws=WorkSource{10062} pkg=android
07-14 13:28:44.842  3707  4675 D PowerManagerService: mDisplayReady: false
07-14 13:28:44.843  3707  3805 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-14 13:28:44.843  3707  3805 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-14 13:28:44.843  3707  3805 D DisplayPowerController: Tracking Direct to etc : 119
07-14 13:28:44.843  3707  3805 D DisplayPowerController: getFinalBrightness : Summary is 119 -> 119
07-14 13:28:44.843  3707  3805 D DisplayPowerController: Animating brightness: target=119, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-14 13:28:44.844  3707  3805 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-14 13:28:44.844  3707  3805 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-14 13:28:44.844  3707  3805 D DisplayPowerController: getFinalBrightness : Summary is 119 -> 119
07-14 13:28:44.844  3707  3805 D DisplayPowerController: Animating brightness: target=119, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-14 13:28:44.844  3707  3805 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-14 13:28:44.844  3707  3805 D PowerManagerService: mDisplayReady: true
07-14 13:28:44.844  3707  4038 D lights  : lcd : 119 +
07-14 13:28:44.850  3707  4038 D lights  : lcd : 119 -
07-14 13:28:44.850  3707  4038 D DisplayPowerState: Tracking!!: 119
,07-14 13:28:44.857  4069  4209 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [755x150]-format:1
,07-14 13:28:44.862  4069  4348 D ViewRootImpl@c4465d0[Toast]: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,07-14 13:28:44.866  5059  6570 W MdnsClient_Cast: #acquireLock. Multicast lock not held. Acquiring. Subtypes:"805741C9"
,07-14 13:28:44.869  3707  3927 D WifiHAL : Setting APF program, halHandle = 0x70ffae7560
07-14 13:28:44.869  3707  3927 I WifiHAL : 
07-14 13:28:44.869  3707  3927 I WifiHAL : createRequest: APF set program request
,07-14 13:28:44.871  3707  3927 I WifiHAL : Done!
07-14 13:28:44.871  3295  3774 D EnterpriseController: netId is 0
07-14 13:28:44.872  3295  3774 D Netd    : getNetworkForDns: using netid 503 for uid 10001
07-14 13:28:44.872  3295  3774 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-14 13:28:44.879  3707  4238 D SLocation: geofence id (1) detected : 0
,07-14 13:28:44.879  8913  8913 I DevicePlayback: Got network change: mobile=falsewifi=true
,07-14 13:28:44.879  8913  8913 I DevicePlayback: Connectivity restored - clearing all queued disable runnables
,07-14 13:28:44.880  3707  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-14 13:28:44.887  9287  9299 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-14 13:28:44.890  9287  9299 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
07-14 13:28:44.897  9287  9299 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,07-14 13:28:44.900  3707  3927 I WifiScanController: location is disabled
,07-14 13:28:44.902  3707  4718 D WifiScanController: isNLPPackage:com.google.android.gms, true
07-14 13:28:44.903  9287  9298 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
07-14 13:28:44.905  9287  9298 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
07-14 13:28:44.905  3707  3937 D WindowManager: finishDrawingWindow: Window{382e007d0 u0 Toast} mDrawState=DRAW_PENDING
07-14 13:28:44.907  3707  4021 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: GW is reachable. - 215 msec.
07-14 13:28:44.907  9287  9298 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,07-14 13:28:44.913  9662 10029 D NetworkSecurityConfig: No Network Security Config specified, using platform default
07-14 13:28:44.914  3707  3987 D MountService: getExternalStorageMountMode : 1
07-14 13:28:44.914  3707  3987 D MountService: getExternalStorageMountMode : 3
07-14 13:28:44.914  3707  3987 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.soagent
07-14 13:28:44.929  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-14 13:28:44.929  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-14 13:28:44.932  3295  3774 D EnterpriseController: netId is 0
,07-14 13:28:44.932  3295  3774 D Netd    : getNetworkForDns: using netid 503 for uid 10135
,07-14 13:28:44.932  3295  3774 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-14 13:28:44.939 10041 10041 E Zygote  : v2
,07-14 13:28:44.939 10041 10041 I libpersona: KNOX_SDCARD checking this for 1000
,07-14 13:28:44.939 10041 10041 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:44.941 10041 10041 E Zygote  : accessInfo : 0
07-14 13:28:44.941  3707  3987 I ActivityManager: Start proc 10041:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
07-14 13:28:44.941 10041 10041 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
07-14 13:28:44.943 10041 10041 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.soagent 
,07-14 13:28:44.976 10041 10041 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-14 13:28:44.977 10041 10041 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:44.978  8913  8967 I DevicePlayback: Allowing woodstock playback due to restored connection
,07-14 13:28:44.979  4069  4198 D vol.MediaSessions: onQueueChanged com.google.android.music []
07-14 13:28:44.980  3707  3922 I ActivityManager: DSS on for com.sec.android.soagent and scale is 1.0
,07-14 13:28:45.003 10041 10041 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,07-14 13:28:45.018 10041 10041 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:45.048  3707  3743 D MountService: getExternalStorageMountMode : 1
07-14 13:28:45.048  3707  3743 D MountService: getExternalStorageMountMode : 3
07-14 13:28:45.048  3707  3743 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10134, packageName : com.sec.android.app.sbrowser
,07-14 13:28:45.066 10055 10055 E Zygote  : v2
,07-14 13:28:45.066 10055 10055 I libpersona: KNOX_SDCARD checking this for 10134
07-14 13:28:45.066 10055 10055 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:45.067 10055 10055 E Zygote  : isSdpEnabledProcess - SDP enabled
,07-14 13:28:45.067 10055 10055 E Zygote  : accessInfo : 64
07-14 13:28:45.068 10055 10055 E Zygote  : isSdpEnabledProcess - SDP enabled
07-14 13:28:45.068 10055 10055 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10134 / [uid]: 10134
07-14 13:28:45.068  3707  3743 I ActivityManager: Start proc 10055:com.sec.android.app.sbrowser:CustomLogger/u0a134 for content provider com.sec.android.app.sbrowser/.logging.CustomLoggingProvider
07-14 13:28:45.068 10055 10055 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:45.069 10055 10055 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser:CustomLogger 
,07-14 13:28:45.092 10055 10055 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:28:45.093 10055 10055 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:45.095  3707  3965 I ActivityManager: DSS on for com.sec.android.app.sbrowser and scale is 1.0
,07-14 13:28:45.123 10055 10055 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_5.0/lib/arm
07-14 13:28:45.124  3707  4021 D WifiWatchdogStateMachine:  [|212]
,07-14 13:28:45.129  3707  4836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-14 13:28:45.130  3707  4836 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-14 13:28:45.130  3707  4836 D BatteryService: online:4, current avg:122, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:67
,07-14 13:28:45.130  3707  3707 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-14 13:28:45.134  3707  3707 V UiModeManager: updateLocked: null action, mDockState=0, category=null
,07-14 13:28:45.134  3707  3707 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
07-14 13:28:45.137  3707  3707 D GameManagerService: new battery level: 100
,07-14 13:28:45.139  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-14 13:28:45.140  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-14 13:28:45.140 10055 10055 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:45.146  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-14 13:28:45.149  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
07-14 13:28:45.150  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,07-14 13:28:45.158  9640  9640 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-14 13:28:45.159  9640  9765 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-14 13:28:45.172 10055 10055 I cr_ApplicationStatus: initialize application : com.sec.android.app.sbrowser.SBrowserApplication@13be907
07-14 13:28:45.176  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
07-14 13:28:45.181 10055 10055 D ReflectField: Cannot load field: SDL_INT
07-14 13:28:45.181 10055 10055 E ReflectField: Incorrect type : Fallback exception
07-14 13:28:45.182 10055 10055 D ReflectField: Cannot load field: KEYCODE_EMAIL
07-14 13:28:45.182 10055 10055 E ReflectField: Incorrect type : Fallback exception
,07-14 13:28:45.192  3707  4737 D MountService: getExternalStorageMountMode : 1
07-14 13:28:45.192  3707  4737 D MountService: getExternalStorageMountMode : 3
,07-14 13:28:45.192  3707  4737 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.wssyncmldm
,07-14 13:28:45.218 10070 10070 E Zygote  : v2
07-14 13:28:45.218 10070 10070 I libpersona: KNOX_SDCARD checking this for 1000
07-14 13:28:45.218 10070 10070 I libpersona: KNOX_SDCARD not a persona
,07-14 13:28:45.219 10070 10070 E Zygote  : accessInfo : 0
,07-14 13:28:45.220 10070 10070 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:45.222 10070 10070 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.wssyncmldm 
,07-14 13:28:45.228  3707  4737 I ActivityManager: Start proc 10070:com.wssyncmldm/1000 for content provider com.wssyncmldm/com.samsung.android.app.fotaclient.log.MasterLogProvider
,07-14 13:28:45.245 10070 10070 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-14 13:28:45.246 10070 10070 D ActivityThread: Added TimaKeyStore provider
,07-14 13:28:45.249  3707  3965 I ActivityManager: DSS on for com.wssyncmldm and scale is 1.0
,07-14 13:28:45.263  3707  3717 I art     : Background sticky concurrent mark sweep GC freed 136481(10MB) AllocSpace objects, 17(388KB) LOS objects, 22% free, 42MB/55MB, paused 3.105ms total 107.125ms
,07-14 13:28:45.273 10070 10070 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm64
,07-14 13:28:45.290 10070 10070 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:45.297 10070 10070 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(96/onCreate)] 
,07-14 13:28:45.299  4497  4497 D io_stats: !@   8,0 r 25249 2275540 w 4788 201240 d 622 73044 f 1920 1920 iot 11130 10602 th 469776 0 0 pt 0 inp 0 0 206.414
,07-14 13:28:45.332  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-14 13:28:45.332  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:45.357 10070 10070 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(422/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-14 13:28:45.411  3295  3774 D EnterpriseController: netId is 0
07-14 13:28:45.411  3295  3774 D Netd    : getNetworkForDns: using netid 503 for uid 10019
07-14 13:28:45.411  3295  3774 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-14 13:28:45.418  5059  5059 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-14 13:28:45.422  5059  7939 I iu.UploadsManager: num queued entries: 0
,07-14 13:28:45.425  5059  7939 I iu.UploadsManager: num updated entries: 0
07-14 13:28:45.426  5059  7939 I iu.SyncManager: NEXT; no task
,07-14 13:28:45.461  9780  9780 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
,07-14 13:28:45.462  9780  9780 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? ]
07-14 13:28:45.462  9780  9780 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
07-14 13:28:45.464 10070 10070 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(297/lllIlIlIIIllIIlIllIl)] Voice : true
,07-14 13:28:45.473  9780  9780 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-14 13:28:45.473  9780  9780 I SA      : [OR] == isSIMCardReady false ==
07-14 13:28:45.475  9780  9780 I SA      : [SCU] == networkStateCheck == true
07-14 13:28:45.475  9780  9780 I SA      : [DM] getCountryCodeFromCSC : PL
07-14 13:28:45.475  9780  9780 I SA      : isChinaCountryCode : false
07-14 13:28:45.475  9780  9780 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-14 13:28:45.475  9780  9780 I SA      : [OR] == networkStateCheck true ==
07-14 13:28:45.480 10070 10070 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(298/lllIlIlIIIllIIlIllIl)] SMS : true
07-14 13:28:45.482 10070 10070 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(299/lllIlIlIIIllIIlIllIl)] isDataOnly : false
,07-14 13:28:45.501  3707  4313 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170714T135845 - CU:10124/CP:4958
,07-14 13:28:45.516  9780  9780 I SA      : [OR] GetMyCountryZoneTask
,07-14 13:28:45.517  9780  9780 I SA      : [OR] onReceive END
,07-14 13:28:45.531 10070 10070 I FOTA_AGENT: [IIIlIlIIIllIIIIllIlI(645/IllIlIIIIlIIlIIIllIl)] bootTime: 1500031539681
,07-14 13:28:45.534  9831  9831 I SVCAgent: Ignore network change.
07-14 13:28:45.538 10070 10070 I FOTA_AGENT: [IIIlIlIIIllIIIIllIlI(638/lllIlIlIIIllIIlIllIl)] bootTime: 1500031539681, savedBootTime: 1500000484534
07-14 13:28:45.541  3707  4020 D WifiWatchdogStateMachine.QualitySocketHandler: response code: 204
07-14 13:28:45.542  3707  4020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiWatchdogStateMachine$QualitySocketHandler.handleMessage:4711 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:154 android.os.HandlerThread.run:61 
,07-14 13:28:45.542  9845  9845 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,07-14 13:28:45.548  3707  4015 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
07-14 13:28:45.548  3707 10014 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-14 13:28:45.548  3707 10014 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: MaybeNotifyState{ when=-1ms what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-14 13:28:45.548  3707 10014 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-1ms what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-14 13:28:45.548  3707 10014 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: CMD_ACCEPT_UNVALIDATED_WIFI
07-14 13:28:45.549  3707  3958 D ConnectivityService: NetworkMonitor.CMD_ACCEPT_UNVALIDATED_WIFI network
,07-14 13:28:45.549  3707  3958 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-14 13:28:45.549  3707  3958 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-14 13:28:45.549  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.549  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.550  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.550  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.550  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-14 13:28:45.550  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:45.550  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:45.550  3707  3958 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-14 13:28:45.550  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-14 13:28:45.550  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.550  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.550  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [] ]
07-14 13:28:45.550  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:45.551  3707  3958 D ConnectivityService: sending new Min Network Score(100): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.551  3707  3923 D WIFI_P2P: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.551  3707  3927 D WIFI_UT : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.551  3707  4024 D Ethernet: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.551  3707  3927 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-14 13:28:45.551  3707  3927 D WIFI_UT : evalRequest
07-14 13:28:45.551  3707  3927 D WIFI_UT :   done
07-14 13:28:45.551  3707  4024 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-14 13:28:45.551  3707  4024 D Ethernet: evalRequest
07-14 13:28:45.551  3707  4024 D Ethernet:   done
07-14 13:28:45.551  3707  3927 D WIFI    : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.552  3707  3927 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-14 13:28:45.552  3707  3927 D WIFI    : evalRequest
07-14 13:28:45.552  3707  3927 D WIFI    :   releaseNetworkFor
07-14 13:28:45.552  4043  4043 D PhoneSwitcherNetworkRequstListener: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.552  4043  4043 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-14 13:28:45.552  4043  4043 D PhoneSwitcherNetworkRequstListener: evalRequest
07-14 13:28:45.552  4043  4043 D PhoneSwitcherNetworkRequstListener:   done
07-14 13:28:45.558 10070 10070 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3131/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
07-14 13:28:45.567  3707  3923 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkU,pBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-14 13:28:45.567  3707  3923 D WIFI_P2P: evalRequest
07-14 13:28:45.567  3707  3923 D WIFI_P2P:   done
07-14 13:28:45.568  3707 10014 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=-1ms what=151655 target=com.android.internal.util.StateMachine$SmHandler }
07-14 13:28:45.568  3707 10014 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: RESULT_VALID
07-14 13:28:45.568  3707 10014 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
07-14 13:28:45.569  3707  3958 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-14 13:28:45.569  3707  3958 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-14 13:28:45.570  3707  3958 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation passed
07-14 13:28:45.570 10070 10070 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3184/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
07-14 13:28:45.570  3707  3958 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-14 13:28:45.571  3707  3958 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-14 13:28:45.571  3707  3707 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
07-14 13:28:45.571  3707  3958 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-14 13:28:45.572  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.572  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.572  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.572  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.572  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.572  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:45.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:45.573  3707  3958 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-14 13:28:45.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-14 13:28:45.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-14 13:28:45.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [] ]
07-14 13:28:45.573  3707  3958 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:45.573  3707  3958 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-14 13:28:45.573  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.573  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-14 13:28:45.573  3707  3958 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [] ]
07-14 13:28:45.574  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.574  3707  3958 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.574  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.574  9845  9845 D AutoSelfUpgradeService: onCreate() 
07-14 13:28:45.574  3707  3958 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.574  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [] ]
07-14 13:28:45.575  3707  3958 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [] ]
07-14 13:28:45.575  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.576  3707  3958 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.577  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.578  3707  3958 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.579  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.579  3707  3958 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.579  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:45.579  3707  3958 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:45.580  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.580  3707  3958 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-14 13:28:45.581  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:45.581  3707  3958 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:45.583  7715  7715 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
07-14 13:28:45.583  7715  7715 E SPPClientService: [SystemStateMoniter] Current Time : 206698
07-14 13:28:45.583  3707  3958 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:45.583  3707  3958 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:28:45.584  7715  7715 E SPPClientService: [SystemStateMoniter] No Connect : false
07-14 13:28:45.585  3707  3958 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-14 13:28:45.587  9845  9845 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
07-14 13:28:45.588  9845 10093 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
07-14 13:28:45.590  4069  4348 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-14 13:28:45.591  3707  3927 D WifiConfigManager: update usableInternet : true
07-14 13:28:45.592  3707 10094 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
07-14 13:28:45.592  3707 10094 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-14 13:28:45.592  3707 10094 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-14 13:28:45.592  3707 10094 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-14 13:28:45.593  3707 10094 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-14 13:28:45.593  3707 10094 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-14 13:28:45.593  3707 10094 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-14 13:28:45.593  3707 10094 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-14 13:28:45.594  3707 10094 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-14 13:28:45.594  3707 10094 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-14 13:28:45.594  3707 10094 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-14 13:28:45.594  3707 10094 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
07-14 13:28:45.600  4069  4348 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
07-14 13:28:45.602  3707  3707 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
07-14 13:28:45.603  3707  3707 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
07-14 13:28:45.604  9845 10093 I AutoSelfUpgradeService: Not a time to rum self upgrade yet.
,07-14 13:28:45.607  3707  3707 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
07-14 13:28:45.608  9845  9845 D AutoSelfUpgradeService: onDestroy()
07-14 13:28:45.615  3707  3927 D WifiConfigStore: saveNetwork skipInternetCheck
07-14 13:28:45.621  9780 10091 I SA      : [SRS] prepareGetMyCountryZone
07-14 13:28:45.632 10070 10070 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3237/IllIlIIIIlIIlIIIllIl)] xdmdbsqlGetNotiSaveState : 0
07-14 13:28:45.635  3707  3927 D WifiConfigStore: readNetwork skipInternetCheck
07-14 13:28:45.637  3707  3707 D SLocation: PendingIntent onSendFinished id:1
07-14 13:28:45.643  9780 10091 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-14 13:28:45.643 10070 10070 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3386/llllllIllIlIlllIIlIl)] xdmdbsqlGetFumoInitType : 0
07-14 13:28:45.644  9780 10091 I SA      : [SSP] query invoked
07-14 13:28:45.645 10070 10070 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(93/onCreate)] DMApplication NOT Start !
07-14 13:28:45.649  3707  3958 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
07-14 13:28:45.651  9780 10091 I SA      : [TPMU] GetMccFromDB : null
07-14 13:28:45.652  9780 10091 I SA      : [SCU] getMccFromPreferece mcc = 260
07-14 13:28:45.652  9780 10091 I SA      : [LBE] isSupportCheckDomainRegion : true
07-14 13:28:45.653  9780 10091 I SA      : [TPM] isNoProxy(default) : true
07-14 13:28:45.656  3707 10096 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
07-14 13:28:45.656  3707 10096 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-14 13:28:45.656  9780 10091 D NetworkSecurityConfig: No Network Security Config specified, using platform default
07-14 13:28:45.657  3707 10096 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-14 13:28:45.657  3707 10096 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-14 13:28:45.657  3707 10096 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-14 13:28:45.657  3707 10096 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-14 13:28:45.658  3707 10096 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-14 13:28:45.658  3707 10096 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-14 13:28:45.658  3707 10096 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-14 13:28:45.658  3707 10096 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-14 13:28:45.658  3707 10096 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-14 13:28:45.658  3707 10096 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
,07-14 13:28:45.663  3707  3707 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-14 13:28:45.663  3707  3707 D WifiHs20Service: reason: 2
07-14 13:28:45.663  3707  3954 I WifiHs20Service: Message received 5014
07-14 13:28:45.663  3707  3954 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,07-14 13:28:45.710  3707  4312 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{77ad364: PendingIntentRecord{1ee8a42 com.google.android.gms broadcastIntent}}
,07-14 13:28:45.741  3707  4239 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / op:PendingIntent{77932f9: PendingIntentRecord{1b8c23e android broadcastIntent}}
07-14 13:28:45.744  3707  4239 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20170715T132845 - CU:1000/CP:3707
,07-14 13:28:45.772  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-14 13:28:45.773  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:45.787  3707  4312 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170714T141855 - CU:10019/CP:4576
,07-14 13:28:45.867  3707  4675 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{5aef282: PendingIntentRecord{1ee8a42 com.google.android.gms broadcastIntent}}
07-14 13:28:45.868  3707  4313 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20170714T133755 - CU:10019/CP:4576
07-14 13:28:45.868  3707  4313 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T133755, SetElapsed=756976, nowELAPSED=206984
,07-14 13:28:45.879  3707  4017 D WifiWatchdogStateMachine:  [|208] []
,07-14 13:28:45.883  3707  3783 D MountService: getExternalStorageMountMode : 1
07-14 13:28:45.883  3707  3783 D MountService: getExternalStorageMountMode : 3
07-14 13:28:45.883  3707  3783 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10112, packageName : com.google.android.talk
,07-14 13:28:45.903 10099 10099 E Zygote  : v2
07-14 13:28:45.903 10099 10099 I libpersona: KNOX_SDCARD checking this for 10112
07-14 13:28:45.903 10099 10099 I libpersona: KNOX_SDCARD not a persona
07-14 13:28:45.904  3707  3783 I ActivityManager: Start proc 10099:com.google.android.talk/u0a112 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.broadcastreceiver.GcmStateReceiver
07-14 13:28:45.905 10099 10099 E Zygote  : accessInfo : 0
,07-14 13:28:45.905 10099 10099 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:28:45.907 10099 10099 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,07-14 13:28:45.930  3707  4718 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{c3c1d0: PendingIntentRecord{6fa1b1e com.google.android.gms broadcastIntent}}
,07-14 13:28:45.932  3707  4718 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T134844, SetElapsed=1405601, nowELAPSED=207047
,07-14 13:28:45.941 10099 10099 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-14 13:28:45.942 10099 10099 D ActivityThread: Added TimaKeyStore provider
07-14 13:28:45.944  3707  4836 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20170714T133755 - CU:10019/CP:4576
07-14 13:28:45.944  3707  4836 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T133755, SetElapsed=757048, nowELAPSED=207060
,07-14 13:28:45.945  3707  3743 I ActivityManager: DSS on for com.google.android.talk and scale is 1.0
,07-14 13:28:45.970  3707  3908 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170714T141855 - CU:10019/CP:4576
,07-14 13:28:45.990 10099 10099 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-14 13:28:45.995 10099 10099 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,07-14 13:28:46.017 10099 10099 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:28:46.100  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-14 13:28:46.100  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:46.159  4576 10098 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-14 13:28:46.169  4576 10098 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-14 13:28:46.183  3707  4312 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.228  4576 10098 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-14 13:28:46.228  4576 10098 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:46.229  3295  3774 D EnterpriseController: netId is 0
07-14 13:28:46.229  3295  3774 D Netd    : getNetworkForDns: using netid 503 for uid 10019
07-14 13:28:46.229  3295  3774 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-14 13:28:46.263  9780 10091 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
,07-14 13:28:46.264  9780 10091 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-14 13:28:46.266  9780 10091 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,07-14 13:28:46.267  9780 10091 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:46.268  9780 10091 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:46.269  3295  3774 D EnterpriseController: netId is 0
07-14 13:28:46.269  3295  3774 D Netd    : getNetworkForDns: using netid 503 for uid 10041
07-14 13:28:46.270  3295  3774 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-14 13:28:46.279 10099 10099 D BabelGcmRegistration: GcmRegistration: Checking GCM registration
,07-14 13:28:46.289 10099 10099 I Babel_telephony: TeleModule.onApplicationCreate
,07-14 13:28:46.292 10099 10124 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-14 13:28:46.292 10099 10124 I Babel_SMS: MmsConfig.loadMmsSettings
07-14 13:28:46.293 10099 10124 E TelephonyManager: getCustomerPath : /system/csc/customer.xml file exist
,07-14 13:28:46.293 10099 10124 E TelephonyManager: getCustomerPath : /system/csc/customer.xml file exist
,07-14 13:28:46.294 10099 10124 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: userAgent=SAMSUNG-ANDROID-MMS/uaprof, uaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
07-14 13:28:46.294 10099 10124 I Babel_SMS: MmsConfig.loadFromDatabase
,07-14 13:28:46.298 10099 10099 I Babel_App: Startup - clean
,07-14 13:28:46.303  3707  4717 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10112
07-14 13:28:46.303  3707  3922 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10112
07-14 13:28:46.304  3707  3922 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10112
,07-14 13:28:46.305  3707  3744 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10112
,07-14 13:28:46.306 10099 10124 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-14 13:28:46.306 10099 10124 I Babel_SMS: MmsConfig.loadFromResources
,07-14 13:28:46.307 10099 10124 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-14 13:28:46.308 10099 10124 I Babel_SMS: MmsConfig.loadMmsSettings: userAgent=SAMSUNG-ANDROID-MMS/uaprof, uaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,07-14 13:28:46.308  3707  4737 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10112
,07-14 13:28:46.366  3707  4679 D CryptdConnector: SND -> {23 cryptfs getpwtype}
07-14 13:28:46.367  3098  3150 D VoldCryptCmdListener: cryptfs getpwtype
07-14 13:28:46.368  3707  3891 D CryptdConnector: RCV <- {213 23 default}
,07-14 13:28:46.398  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:46.399  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:46.546  3707  4677 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.559  3707  4679 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.573  3707  3743 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.587  3707  3922 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.599  3707  3965 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.612  3707  4718 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.626  3707  3744 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.640  3707  3987 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.653  3707  4836 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.669  3707  4312 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.697  3707  4675 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.708  3707  4716 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.717  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-14 13:28:46.717  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:46.719  3707  3937 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.734  4576 10098 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-14 13:28:46.735  4576 10098 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:46.810  4069  4348 D ViewRootImpl@c4465d0[Toast]: dispatchDetachedFromWindow
,07-14 13:28:46.815  3707  3922 D InputTransport: Input channel destroyed: fd=462
07-14 13:28:46.815  3707  3922 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3707) eventTime = 207931
,07-14 13:28:46.816  3707  3922 D PowerManagerService: [s] UserActivityState : 4 -> 1
,07-14 13:28:46.817  3707  3922 D PowerManagerService: [api] release WakeLock SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3707, ws=WorkSource{10062}) (uid=1000, pid=3707, ws=WorkSource{10062}, pkg=android, elapsedTime=1975) (0x0)
,07-14 13:28:46.818  3707  3922 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3707, ws=WorkSource{10062}) (uid=1000, pid=3707, ws=WorkSource{10062}, pkg=android, elapsedTime=1975)
,07-14 13:28:46.819  4069  4348 D InputTransport: Input channel destroyed: fd=148
,07-14 13:28:46.886  4576 10098 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-14 13:28:46.891  3707  4717 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-14 13:28:46.908  4576 10098 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-14 13:28:46.909  4576 10098 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:46.996  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:46.997  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:47.084  9780 10091 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 818
,07-14 13:28:47.144  9780 10091 I SA      : [ODM] saveOpenData( GEO_IP, EU )
,07-14 13:28:47.145  9780 10091 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,07-14 13:28:47.148  9780 10091 I SA      : [OCP]  Cursor is not null
,07-14 13:28:47.153  9780 10091 I SA      : [OCP] update openData : EU
,07-14 13:28:47.158  9780 10091 I SA      : [TPMU] getNetworkMcc : 
,07-14 13:28:47.162  9780 10091 I SA      : [SRS] prepareGetMyCountryZone
,07-14 13:28:47.170  9780 10091 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-14 13:28:47.170  9780 10091 I SA      : [SSP] query invoked
,07-14 13:28:47.177  9780 10091 I SA      : [TPMU] GetMccFromDB : null
07-14 13:28:47.177  9780 10091 I SA      : [SCU] getMccFromPreferece mcc = 260
07-14 13:28:47.177  9780 10091 I SA      : [LBE] isSupportCheckDomainRegion : true
07-14 13:28:47.177  9780 10091 I SA      : [TPM] isNoProxy(default) : true
,07-14 13:28:47.178  9780 10091 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
07-14 13:28:47.179  9780 10091 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-14 13:28:47.180  9780 10091 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,07-14 13:28:47.181  9780 10091 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:47.182  9780 10091 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:47.223  4576 10098 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-14 13:28:47.228  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:47.228  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
07-14 13:28:47.228  3707  3927 D WifiStateMachine: User moved, open or psk 24GHz, currentRssi = -45, mQnsUpperRssiThreshold = 200
07-14 13:28:47.230  3707  3927 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@7962b18
07-14 13:28:47.230  3707  3927 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
,07-14 13:28:47.235  3707  3927 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170714T132851 - CU:1000/CP:3707
07-14 13:28:47.236  3707  3927 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132851, SetElapsed=212335, nowELAPSED=208351
,07-14 13:28:47.298  3707  4679 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170714T141855 - CU:10019/CP:4576
,07-14 13:28:47.308  3707  4675 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{54d4b2c: PendingIntentRecord{1ee8a42 com.google.android.gms broadcastIntent}}
,07-14 13:28:47.323  3707  4677 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170714T141855 - CU:10019/CP:4576
,07-14 13:28:47.347  3707  3803 I WindowManager: Destroying surface Surface(name=Toast) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementInner:499 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementLoop:274 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacement:222 com.android.server.wm.WindowManagerService$H.handleMessage:9166 android.os.Handler.dispatchMessage:102 
,07-14 13:28:47.347  3113  4411 I SurfaceFlinger: id=17 Removed Uoast (5/5)
,07-14 13:28:47.348  3113  3283 I SurfaceFlinger: id=17 Removed Uoast (-2/5)
,07-14 13:28:47.374  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-14 13:28:47.375  9662 10029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:47.967  9780 10091 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 787
,07-14 13:28:47.971  9780 10091 I SA      : [ODM] saveOpenData( GEO_IP, EU )
07-14 13:28:47.972  9780 10091 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,07-14 13:28:47.978  9780 10091 I SA      : [OCP]  Cursor is not null
,07-14 13:28:47.989  9780 10091 I SA      : [OCP] update openData : EU
,07-14 13:28:47.996  9780 10091 I SA      : [TPMU] getNetworkMcc : 
,07-14 13:28:48.000  9780 10091 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 821
07-14 13:28:48.000  9780 10091 I SA_HTTPURLCONNECTION: [RC New] Execute end
07-14 13:28:48.001  9780 10091 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 1737
07-14 13:28:48.001  9780 10091 I SA_HTTPURLCONNECTION: [RC New] Execute end
07-14 13:28:48.002  9780  9780 I SA      : [OR] GetMyCountryZoneTask mcc = null
07-14 13:28:48.002  9780  9780 I SA      : [OR] GetMyCountryZoneTask Fail
,07-14 13:28:49.380  9513  9577 I io.jxcore.node.IncomingSocketThreadTest: testRun
,07-14 13:28:49.381  9513  9577 I !!      :  finally closed
,07-14 13:28:49.387  9513  9577 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,07-14 13:28:49.388  9513  9577 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-14 13:28:49.392  9513  9577 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,07-14 13:28:49.392  9513  9577 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-14 13:28:49.396  9513  9577 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,07-14 13:28:49.402  9513  9577 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
07-14 13:28:49.403  9513  9577 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@9def1ff Bundle[{}]
,07-14 13:28:49.406  9513  9577 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
07-14 13:28:49.407  9513  9577 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-14 13:28:49.408  9513  9577 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-14 13:28:49.410  9513  9577 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,07-14 13:28:49.410  9513  9577 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-14 13:28:49.412  9513  9577 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
07-14 13:28:49.412  9513  9577 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-14 13:28:49.415  9513  9577 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
07-14 13:28:49.415  9513  9577 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-14 13:28:49.417  9513  9577 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,07-14 13:28:49.418  9513  9577 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-14 13:28:49.420  9513  9577 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,07-14 13:28:49.423  9513  9577 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,07-14 13:28:49.425  9513  9577 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,07-14 13:28:49.428  9513  9577 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,07-14 13:28:49.429  9513  9577 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,07-14 13:28:49.431  9513  9577 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,07-14 13:28:49.434  9513  9577 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,07-14 13:28:49.438  9513 10138 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
07-14 13:28:49.438  9513 10138 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-14 13:28:49.688  9711 10028 I NetworkServiceClient: WiFi is connected
,07-14 13:28:49.706  3707  4313 I ActivityManager: KPU : put [com.samsung.enhanceservice] : 25932 K
07-14 13:28:49.706  3707  4313 I ActivityManager: Killing 9183:com.samsung.enhanceservice/5004 (adj 906): DHA:empty #33
,07-14 13:28:49.751  3707  4677 D ActivityManager: cleanUpApplicationRecord -- 9183
,07-14 13:28:49.753  4615  4626 D ForegroundUtils: could not check pending caller
,07-14 13:28:49.946  3295  3774 D EnterpriseController: netId is 0
07-14 13:28:49.947  3295  3774 D Netd    : getNetworkForDns: using netid 503 for uid 10033
07-14 13:28:49.947  3295  3774 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-14 13:28:49.953  9513 10140 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
07-14 13:28:49.953  9513 10140 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
07-14 13:28:49.954  9513 10140 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-14 13:28:49.954  9513 10140 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-14 13:28:49.955  9513 10140 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
07-14 13:28:49.955  9513 10138 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
07-14 13:28:49.955  9513 10142 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 229, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.955  9513 10142 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:49.955  9513 10142 D io.jxcore.node.StreamCopyingThread:  id: 77
07-14 13:28:49.955  9513 10138 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,07-14 13:28:49.956  9513 10138 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-14 13:28:49.957  9513 10143 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 230, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.957  9513 10143 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:49.957  9513 10143 D io.jxcore.node.StreamCopyingThread:  id: 77
07-14 13:28:49.959  9513 10138 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-14 13:28:49.960  9513 10144 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 231, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.960  9513 10144 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:49.960  9513 10144 D io.jxcore.node.StreamCopyingThread:  id: 78
,07-14 13:28:49.961  9513 10138 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,07-14 13:28:49.966  9513 10145 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 232, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.966  9513 10145 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:49.966  9513 10145 D io.jxcore.node.StreamCopyingThread:  id: 78
07-14 13:28:49.968  9513 10145 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 232, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.968  9513 10145 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:49.968  9513 10145 D io.jxcore.node.StreamCopyingThread:  id: 78
07-14 13:28:49.968  9513 10145 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.968  9513 10145 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:49.968  9513 10145 D io.jxcore.node.StreamCopyingThread:  id: 78
07-14 13:28:49.968  9513 10145 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-14 13:28:49.968  9513 10145 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-14 13:28:49.968  9513 10145 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-14 13:28:49.968  9513 10145 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-14 13:28:49.968  9513 10145 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-14 13:28:49.968  9513 10145 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
07-14 13:28:49.969  9513 10142 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 229, thread name: IncomingSocketThread/Sender): Connection reset
,07-14 13:28:49.969  9513 10142 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 229, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.969  9513 10142 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:49.969  9513 10142 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-14 13:28:49.969  9513 10142 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Connection reset
07-14 13:28:49.969  9513 10142 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-14 13:28:49.969  9513 10142 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 229, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.969  9513 10142 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:49.969  9513 10142 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-14 13:28:49.969  9513 10144 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 231, thread name: OutgoingSocketThread/Sender): Socket closed
07-14 13:28:49.970  9513 10144 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 231, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.970  9513 10144 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:49.970  9513 10144 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 8192
07-14 13:28:49.970  9513 10144 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-14 13:28:49.970  9513 10145 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 232, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.970  9513 10145 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:49.970  9513 10145 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-14 13:28:49.970  9513 10144 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-14 13:28:49.970  9513 10144 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 231, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.970  9513 10144 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:28:49.970  9513 10144 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 8192
07-14 13:28:49.971  9513 10143 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 230, thread name: IncomingSocketThread/Receiver): Broken pipe
07-14 13:28:49.971  9513 10143 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 230, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.971  9513 10143 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:49.971  9513 10143 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 172032 and the total number of bytes written 167936
07-14 13:28:49.971  9513 10143 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: Broken pipe", this is likely due to peer having disconnected
07-14 13:28:49.971  9513 10143 D io.jxcore.,node.StreamCopyingThread: number of bytes read = 4096
07-14 13:28:49.971  9513 10143 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 230, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:28:49.971  9513 10143 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-14 13:28:49.971  9513 10143 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 172032 and the total number of bytes written 167936
,07-14 13:28:50.262  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-14 13:28:50.263  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-14 13:28:50.301  4497  4497 D io_stats: !@   8,0 r 25253 2275604 w 4966 203852 d 654 73176 f 1975 1975 iot 11240 10683 th 470276 0 0 pt 0 inp 0 0 211.416
,07-14 13:28:50.407  3707  5610 D SSRM:f  : SIOP:: AP = 290, PST = 282 (W:10), CP = 235, CUR = 124, LCD = 119
,07-14 13:28:50.820  3707  3805 D PowerManagerService: [s] UserActivityState : 1 -> 4
07-14 13:28:50.820  3707  3805 D PowerManagerService: mDisplayReady: false
07-14 13:28:50.820  3707  3805 I PowerManagerService: [PWL] On : 0 (211936 ms ago)
07-14 13:28:50.820  3707  3805 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
07-14 13:28:50.821  3707  3805 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-14 13:28:50.821  3707  3805 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-14 13:28:50.821  3707  3805 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-14 13:28:50.821  3707  3805 D DisplayPowerController: Animating brightness: target=57, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-14 13:28:50.822  3707  3805 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-14 13:28:50.822  3707  3805 D PowerManagerService: mDisplayReady: true
,07-14 13:28:50.837  3707  4038 D lights  : lcd : 93 +
,07-14 13:28:50.845  3707  4038 D lights  : lcd : 93 -
,07-14 13:28:50.854  3707  4038 D lights  : lcd : 59 +
,07-14 13:28:50.856  3707  4038 D lights  : lcd : 59 -
,07-14 13:28:50.870  3707  3805 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-14 13:28:50.870  3707  4038 D lights  : lcd : 57 +
07-14 13:28:50.870  3707  3805 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-14 13:28:50.871  3707  3805 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-14 13:28:50.871  3707  3805 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-14 13:28:50.872  3707  4038 D lights  : lcd : 57 -
,07-14 13:28:51.220  3707  3863 D SamsungAlarmManager: Expired : 4
,07-14 13:28:51.221  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T133755, SetElapsed=757048, nowELAPSED=212336
,07-14 13:28:51.221  3707  3863 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@2c3b2df alarm=Alarm{9a0638a type 2 when 212335 android}
,07-14 13:28:51.225  3707  3927 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
,07-14 13:28:51.229  9972  9972 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-14 13:28:51.230  9972  9972 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-14 13:28:51.235  3707  3927 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170714T132859 - CU:1000/CP:3707
07-14 13:28:51.236  3707  3927 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132859, SetElapsed=220341, nowELAPSED=212351
,07-14 13:28:51.246  3707  3955 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170714T132906 - CU:1000/CP:3707
,07-14 13:28:51.249  9972  9972 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-14 13:28:51.792  4576  4576 I BeaconBle: 'L' hardware scan: scan stopped, no clients
,07-14 13:28:51.875  5059  5068 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-14 13:28:53.285  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:53.285  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-14 13:28:54.498  3707 10149 D WifiMHD::s: req(2):1, 7, 1
,07-14 13:28:54.501  3707 10149 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:54.502  3707 10149 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-14 13:28:54.506  3295  3774 D EnterpriseController: netId is 0
07-14 13:28:54.507  3295  3774 D Netd    : getNetworkForDns: using netid 503 for uid 1000
07-14 13:28:54.507  3295  3774 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-14 13:28:55.203  3295  3771 D Netd    : Iface wlan0 link up
,07-14 13:28:55.206  9972  9972 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
07-14 13:28:55.207  3707  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-14 13:28:55.207  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:28:55.207  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
,07-14 13:28:55.212  3707  3955 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@3d9ee18
,07-14 13:28:55.268  3707  3783 I ActivityManager: Waited long enough for: ServiceRecord{9c39995 u0 com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService}
,07-14 13:28:55.304  4497  4497 D io_stats: !@   8,0 r 25253 2275604 w 4970 203924 d 654 73176 f 1978 1978 iot 11240 10687 th 472344 0 0 pt 0 inp 0 0 216.419
,07-14 13:28:55.445  9513  9577 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,07-14 13:28:55.449  9513  9577 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,07-14 13:28:55.453  9513  9577 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,07-14 13:28:56.312  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:56.313  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-14 13:28:56.463  9513  9577 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,07-14 13:28:56.467  9513  9577 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,07-14 13:28:56.471  9513  9577 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,07-14 13:28:56.472  9513  9577 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 240)
,07-14 13:28:56.476  9513  9577 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,07-14 13:28:56.477  9513  9577 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
07-14 13:28:56.477  9513  9577 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 241)
,07-14 13:28:56.481  9513  9577 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,07-14 13:28:56.484  9513  9577 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,07-14 13:28:56.488  9513  9577 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,07-14 13:28:56.490  9513  9577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-14 13:28:56.491  9513  9577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@844d307 added. We now have 2 listener(s)
07-14 13:28:56.491  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@844d307 added. We now have 3 listener(s)
07-14 13:28:56.491  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-14 13:28:56.495  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:56.495  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-14 13:28:56.495  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-14 13:28:56.496  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-14 13:28:56.496  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c042c34 added. We now have 4 listener(s)
07-14 13:28:56.496  9513  9577 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-14 13:28:56.498  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-14 13:28:56.505  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:56.512  9513  9577 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,07-14 13:28:56.514  9513  9577 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,07-14 13:28:56.515  9513  9577 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
07-14 13:28:56.515  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,07-14 13:28:56.515  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-14 13:28:56.520  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
,07-14 13:28:56.521  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:56.521  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.522  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-14 13:28:56.526  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
07-14 13:28:56.526  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
,07-14 13:28:56.527  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.527  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-14 13:28:56.527  9513  9577 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-14 13:28:56.527  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-14 13:28:56.527  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-14 13:28:56.530  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-14 13:28:56.531  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-14 13:28:56.531  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-14 13:28:56.531  9513 10153 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-14 13:28:56.531  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-14 13:28:56.532  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-14 13:28:56.532  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-14 13:28:56.532  9513  9513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-14 13:28:56.532  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-14 13:28:56.532  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-14 13:28:56.536  9513 10153 D BluetoothSocket: bindListen(): myUserId = 0
07-14 13:28:56.536  9513 10153 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-14 13:28:56.542  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-14 13:28:56.543  9513  9577 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-14 13:28:56.543  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-14 13:28:56.547  9513 10153 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-14 13:28:56.547  9513 10153 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@5117fd2, port: 6, type: 1, local socket address: null, socket type: 0
,07-14 13:28:56.550  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:56.551  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:56.553  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:56.556  9513  9577 D BluetoothAdapter: isSecureModeEnabled
,07-14 13:28:56.557  9640  9812 D BtConfig.SecureMode: isSecureModeOn:false
07-14 13:28:56.558  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:56.558  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-14 13:28:56.560  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:56.561  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:56.561  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-14 13:28:56.561  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-14 13:28:56.562  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,07-14 13:28:56.565  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:56.568  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.568  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.569  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,07-14 13:28:56.569  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-14 13:28:56.569  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "9efc9363-3d2b-4b01-abd9-143186647519", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-14 13:28:56.569  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E 94 4A 3E
,07-14 13:28:56.570  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-14 13:28:56.570  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-14 13:28:56.570  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.571  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.571  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,07-14 13:28:56.572  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-14 13:28:56.572  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.573  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.573  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:56.575  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:56.577  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:56.577  9513  9577 D BluetoothAdapter: isSecureModeEnabled
,07-14 13:28:56.577  9640  9661 D BtConfig.SecureMode: isSecureModeOn:false
07-14 13:28:56.578  9513  9577 D BluetoothLeAdvertiser: start advertising
,07-14 13:28:56.579  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:56.589  9640  9651 D BtGatt.GattService: registerClient() - UUID=b13d364c-d0e2-435c-960a-f91fa6648a91
,07-14 13:28:56.695  9640  9660 D BtGatt.GattService: onClientRegistered() - UUID=b13d364c-d0e2-435c-960a-f91fa6648a91, clientIf=5, status=0
,07-14 13:28:56.698  9513  9525 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-14 13:28:56.703  9640  9661 E BtGatt.ContextMap: Context not found for ID 5
,07-14 13:28:56.705  9640  9687 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-14 13:28:56.710  9640  9676 D BtGatt.AdvertiseManager: message : 0
,07-14 13:28:56.712  9640  9676 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-14 13:28:56.713  9640  9676 D BtGatt.AdvertiseManager: size of list is =0
,07-14 13:28:56.722  9640  9676 D BtGatt.AdvertiseManager: starting advertising
,07-14 13:28:56.728  9640  9676 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-14 13:28:56.732  9640  9728 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-14 13:28:56.750  9640  9660 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-14 13:28:56.754  9640  9676 D BtGatt.AdvertiseManager: starting multi advertising
,07-14 13:28:56.767  9640  9660 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-14 13:28:56.768  9640  9676 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-14 13:28:56.768  9640  9676 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-14 13:28:56.768  9640  9676 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-14 13:28:56.769  9640  9676 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-14 13:28:56.770  9513  9524 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-14 13:28:56.772  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:56.773  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.773  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-14 13:28:56.774  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.775  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.776  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:56.777  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.778  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.779  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-14 13:28:56.783  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-14 13:28:56.785  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:56.789  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:56.790  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:56.790  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:56.791  9513  9513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-14 13:28:56.793  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-14 13:28:56.793  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-14 13:28:56.793  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-14 13:28:56.794  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-14 13:28:56.795  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-14 13:28:56.796  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-14 13:28:56.796  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:28:56.797  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-14 13:28:56.797  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,07-14 13:28:56.797  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-14 13:28:56.798  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-14 13:28:56.798  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-14 13:28:56.799  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-14 13:28:56.800  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-14 13:28:56.805  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-14 13:28:56.805  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
07-14 13:28:56.806  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,07-14 13:28:56.806  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-14 13:28:56.807  9513  9513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-14 13:28:57.296  9513  9577 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-14 13:28:57.297  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
07-14 13:28:57.297  9513  9577 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-14 13:28:57.298  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-14 13:28:57.298  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-14 13:28:57.298  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-14 13:28:57.299  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-14 13:28:57.299  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-14 13:28:57.299  9513 10153 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-14 13:28:57.299  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,07-14 13:28:57.299  9513 10153 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-14 13:28:57.299  9513 10153 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-14 13:28:57.300  9513  9513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-14 13:28:57.300  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-14 13:28:57.301  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-14 13:28:57.302  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:57.302  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-14 13:28:57.302  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-14 13:28:57.303  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:57.305  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:57.306  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:57.307  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:57.311  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:57.314  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:57.315  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-14 13:28:57.318  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:57.322  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:57.322  9513  9577 D BluetoothLeScanner: could not find callback wrapper
07-14 13:28:57.322  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-14 13:28:57.323  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:57.324  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:57.325  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:57.326  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-14 13:28:57.326  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:57.330  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:28:57.333  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:28:57.333  9513  9577 D BluetoothLeAdvertiser: stop advertising
,07-14 13:28:57.336  9640  9651 E BtGatt.ContextMap: Context not found for ID 5
,07-14 13:28:57.338  9640  9687 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-14 13:28:57.338  9640  9676 D BtGatt.AdvertiseManager: message : 1
,07-14 13:28:57.340  9640  9676 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-14 13:28:57.341  9640  9676 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-14 13:28:57.344  9640  9676 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-14 13:28:57.356  9640  9660 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-14 13:28:57.356  9640  9660 D BtGatt.GattService: Client app is not null!
,07-14 13:28:57.358  9513  9525 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-14 13:28:57.360  9640  9661 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-14 13:28:57.363  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-14 13:28:57.364  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:57.365  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-14 13:28:57.366  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:57.367  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:57.368  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:57.368  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-14 13:28:57.369  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-14 13:28:57.371  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-14 13:28:57.372  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:28:57.378  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:57.378  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-14 13:28:57.379  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:57.379  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:28:57.380  9513  9513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-14 13:28:57.380  9513  9513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
07-14 13:28:57.380  9513  9513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-14 13:28:57.381  9513  9513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-14 13:28:57.381  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-14 13:28:57.381  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-14 13:28:57.382  9513  9513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,07-14 13:28:57.382  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-14 13:28:57.383  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:28:57.383  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-14 13:28:57.383  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,07-14 13:28:57.384  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-14 13:28:57.384  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-14 13:28:57.385  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-14 13:28:57.385  9513  9513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-14 13:28:57.887  9513  9513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-14 13:28:59.225  3707  3863 D SamsungAlarmManager: Expired : 4
,07-14 13:28:59.226  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T133755, SetElapsed=757048, nowELAPSED=220342
07-14 13:28:59.227  3707  3863 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@e5a9dfb alarm=Alarm{8a712ad type 2 when 220341 android}
,07-14 13:28:59.230  3707  3927 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 16000: mInRange : true
,07-14 13:28:59.233  9972  9972 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-14 13:28:59.234  9972  9972 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-14 13:28:59.241  3707  3927 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170714T132915 - CU:1000/CP:3707
07-14 13:28:59.242  3707  3927 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132915, SetElapsed=236346, nowELAPSED=220358
,07-14 13:28:59.249  9972  9972 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-14 13:28:59.250  3707  3955 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170714T132914 - CU:1000/CP:3707
,07-14 13:28:59.333  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:28:59.334  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-14 13:29:00.001  3707  3863 D SamsungAlarmManager: Expired : 8
07-14 13:29:00.002  3707  3863 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{5546830 type 3 when 221116 android}
,07-14 13:29:00.012  3707  3707 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170714T133000 - CU:1000/CP:3707
,07-14 13:29:00.016  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-14 13:29:00.017  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-14 13:29:00.019  4069  4069 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-14 13:29:00.023  3707  3707 I ActivityManager: KPU : put [com.samsung.dcmservice] : 25816 K
,07-14 13:29:00.023  3707  3707 I ActivityManager: Killing 9196:com.samsung.dcmservice/5004 (adj 906): DHA:empty #33
,07-14 13:29:00.047  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#end
07-14 13:29:00.047  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-14 13:29:00.050  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-14 13:29:00.064  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
07-14 13:29:00.066  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-14 13:29:00.070  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
07-14 13:29:00.077  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
07-14 13:29:00.084  3707  4737 D ActivityManager: cleanUpApplicationRecord -- 9196
07-14 13:29:00.086  4615  4626 D ForegroundUtils: could not check pending caller
,07-14 13:29:00.095  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
07-14 13:29:00.097  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-14 13:29:00.099  4069  4069 V hong    : mid yDiff = 438
07-14 13:29:00.099  4069  4069 V hong    : mid yDiff = 438
07-14 13:29:00.100  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-14 13:29:00.100  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-14 13:29:00.103  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-14 13:29:00.106  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-14 13:29:00.115  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-14 13:29:00.118  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-14 13:29:00.126  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-14 13:29:00.127  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-14 13:29:00.132  5231  5231 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-14 13:29:00.133  5231  5231 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-14 13:29:00.136  5231  5231 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-14 13:29:00.141  5231  5231 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-14 13:29:00.142  5231  5231 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
07-14 13:29:00.143  5231  5231 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-14 13:29:00.144  5231  5231 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,07-14 13:29:00.145  5231  5231 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-14 13:29:00.150  5231  5231 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-14 13:29:00.151  5231  5231 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CADA8AA8229277DB92295A1F293CFD0CE76AF0730E90FD5AA617233BDF436C33E406396202CDD07CC2107F97C50140175]}
07-14 13:29:00.152  5231  5231 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-14 13:29:00.309  4497  4497 D io_stats: !@   8,0 r 25253 2275604 w 4988 204088 d 655 73180 f 1980 1980 iot 11250 10691 th 473084 0 0 pt 0 inp 0 0 221.423
,07-14 13:29:00.388  9513  9577 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
07-14 13:29:00.389  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-14 13:29:00.390  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-14 13:29:00.390  9513  9577 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-14 13:29:00.391  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-14 13:29:00.391  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-14 13:29:00.391  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-14 13:29:00.405  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-14 13:29:00.406  9513  9577 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-14 13:29:00.406  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-14 13:29:00.414  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:00.417  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:00.421  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:00.429  9513  9577 D BluetoothAdapter: isSecureModeEnabled
,07-14 13:29:00.430  9640  9652 D BtConfig.SecureMode: isSecureModeOn:false
,07-14 13:29:00.432  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:00.433  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-14 13:29:00.436  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:29:00.436  3707  5610 D SSRM:f  : SIOP:: AP = 280, PST = 282 (W:10), CP = 232, CUR = 136, LCD = 57
,07-14 13:29:00.439  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:29:00.440  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-14 13:29:00.440  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-14 13:29:00.440  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,07-14 13:29:00.447  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:00.450  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:00.457  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:00.460  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:00.463  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:00.463  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-14 13:29:00.463  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-14 13:29:00.463  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 64496
,07-14 13:29:00.465  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=64496, mManufacturerData=null, mManufacturerDataMask=null]
,07-14 13:29:00.466  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:00.466  9513  9577 D BluetoothLeScanner: Start Scan
,07-14 13:29:00.469  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:00.471  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:00.475  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:00.477  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:00.483  9640  9651 D BtGatt.GattService: registerClient() - UUID=eed97ed7-b878-4fa5-8ef0-70f7583debd5
,07-14 13:29:00.587  9640  9660 D BtGatt.GattService: onClientRegistered() - UUID=eed97ed7-b878-4fa5-8ef0-70f7583debd5, clientIf=5, status=0
,07-14 13:29:00.589  9513  9525 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
,07-14 13:29:00.592  9640  9661 D BtGatt.GattService: start scan with filters
,07-14 13:29:00.599  9640  9661 D BtGatt.GattService: getScanSettings
,07-14 13:29:00.611  9640  9661 D BtGatt.GattService: Is it foreground application = true
07-14 13:29:00.611  9640  9661 D BtGatt.GattService: not a background application
,07-14 13:29:00.625  9640  9687 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
07-14 13:29:00.626  9640  9687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:29:00.626  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
07-14 13:29:00.627  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:00.627  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-14 13:29:00.628  9640  9677 D BtGatt.ScanManager: handling starting scan
07-14 13:29:00.628  9640  9677 D BtGatt.ScanManager: isFilteringSupported
07-14 13:29:00.628  9640  9677 D BluetoothAdapter: enableStandAloneBleMode=
07-14 13:29:00.629  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:00.630  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-14 13:29:00.630  9640  9677 D BluetoothAdapter: STATE_ON
07-14 13:29:00.631  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-14 13:29:00.631  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:29:00.631  9640  9677 D BluetoothAdapter: STATE_ON
07-14 13:29:00.632  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
07-14 13:29:00.632  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-14 13:29:00.633  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-14 13:29:00.634  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
07-14 13:29:00.635  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-14 13:29:00.635  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-14 13:29:00.636  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:00.636  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
07-14 13:29:00.636  9640  9677 D BluetoothAdapter: STATE_ON
07-14 13:29:00.638  9640  9677 D BluetoothAdapter: STATE_ON
07-14 13:29:00.642  9640  9677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
,07-14 13:29:00.646  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:00.646  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-14 13:29:00.647  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:00.648  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:00.649  3707  3783 I ActivityManager: KPU : put [com.samsung.android.coreapps] : 29796 K
07-14 13:29:00.649  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
07-14 13:29:00.649  3707  3783 I ActivityManager: Killing 9112:com.samsung.android.coreapps/5011 (adj 906): DHA:empty #33
,07-14 13:29:00.654  9640  9660 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-14 13:29:00.654  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:00.655  9640  9677 D BtGatt.ScanManager: set filter index= 3 for clientIf= 5
,07-14 13:29:00.656  9640  9677 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-14 13:29:00.656  9640  9677 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-14 13:29:00.656  9640  9677 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
07-14 13:29:00.659  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-14 13:29:00.660  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-14 13:29:00.660  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-14 13:29:00.661  9513  9513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-14 13:29:00.670  9640  9660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
07-14 13:29:00.670  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:00.671  9640  9677 D BtGatt.ScanManager: Starting BLE batch scan
07-14 13:29:00.671  9640  9677 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-14 13:29:00.686  9640  9660 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-14 13:29:00.686  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-14 13:29:00.691  9640  9660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-14 13:29:00.691  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:00.692  3707  4313 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{1cfd75c: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
,07-14 13:29:00.703  3707  3987 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170714T132901 - CU:1002/CP:9640
07-14 13:29:00.703  3707  3987 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132901, SetElapsed=222812, nowELAPSED=221819
,07-14 13:29:00.706  3707  3922 D ActivityManager: cleanUpApplicationRecord -- 9112
,07-14 13:29:00.708  4615  4626 D ForegroundUtils: could not check pending caller
,07-14 13:29:01.161  9513  9513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,07-14 13:29:01.162  9513  9513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-14 13:29:01.162  9513  9513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-14 13:29:01.440  3707  4717 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10112
,07-14 13:29:01.470 10099 10099 I Babel_ConcService: Binding ConcurrentService
,07-14 13:29:01.535 10099 10160 I Babel_ConcService: Scheduling delay with GcmNetworkManager of 244832 s for task fstaccount_reg_renewal_25803_3 and tag network_connectivity_wakeup:persisted
,07-14 13:29:01.564 10099 10160 I Babel_ConcService: Scheduling delay with GcmNetworkManager of 3599 s for task fvzDB_CLEANUP_222530_1 and tag timed_wakeup
,07-14 13:29:01.570 10099 10163 I Babel_ConcService: Acquired partial wake lock to keep ConcurrentService alive
,07-14 13:29:01.573 10099 10162 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-14 13:29:01.574 10099 10162 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-14 13:29:01.577  3295  3774 D EnterpriseController: netId is 0
07-14 13:29:01.577  3295  3774 D Netd    : getNetworkForDns: using netid 503 for uid 10112
07-14 13:29:01.577  3295  3774 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-14 13:29:01.577 10099 10163 I Babel_ConcService: Released partial wake lock as ConcurrentService became idle
,07-14 13:29:01.580 10099 10161 I Babel_ConcService: Acquired partial wake lock to keep ConcurrentService alive
07-14 13:29:01.583 10099 10161 I Babel_ConcService: Released partial wake lock as ConcurrentService became idle
,07-14 13:29:01.601  3707  4836 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{fe5cf8c: PendingIntentRecord{1ee8a42 com.google.android.gms broadcastIntent}}
,07-14 13:29:01.602  3707  4836 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132901, SetElapsed=222311, nowELAPSED=222718
07-14 13:29:01.602  3707  3863 D SamsungAlarmManager: Expired : 4
,07-14 13:29:01.603  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132915, SetElapsed=236346, nowELAPSED=222719
07-14 13:29:01.603  3707  3863 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{c5e36d5 type 2 when 222311 com.android.bluetooth}
,07-14 13:29:01.606  9640  9640 D BtGatt.ScanManager: awakened up at time 222722
,07-14 13:29:01.608  9640  9677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-14 13:29:01.613  9640  9660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-14 13:29:01.613  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-14 13:29:01.613  3707  4836 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{6906eea: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
,07-14 13:29:01.620  3707  4737 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170714T132902 - CU:1002/CP:9640
,07-14 13:29:01.620  3707  4737 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132902, SetElapsed=223730, nowELAPSED=222735
,07-14 13:29:01.625  3707  3743 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170714T141855 - CU:10019/CP:4576
,07-14 13:29:01.633  3707  4677 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4576 / op:PendingIntent{46b5db: PendingIntentRecord{1ee8a42 com.google.android.gms broadcastIntent}}
,07-14 13:29:01.634  3707  4677 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132902, SetElapsed=223229, nowELAPSED=222750
,07-14 13:29:01.650  3707  3987 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170714T141855 - CU:10019/CP:4576
,07-14 13:29:01.853 10099 10162 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,07-14 13:29:01.901 10099 10162 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 242 native methods...
,07-14 13:29:01.926 10099 10162 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,07-14 13:29:01.929 10099 10162 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-14 13:29:02.113  3707  3863 D SamsungAlarmManager: Expired : 4
07-14 13:29:02.114  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132915, SetElapsed=236346, nowELAPSED=223229
,07-14 13:29:02.114  3707  3863 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{be65878 type 2 when 223229 com.android.bluetooth}
,07-14 13:29:02.117  9640  9640 D BtGatt.ScanManager: awakened up at time 223232
,07-14 13:29:02.118  9640  9677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-14 13:29:02.126  9640  9660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-14 13:29:02.127  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-14 13:29:02.127  3707  3987 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{4d86b51: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
,07-14 13:29:02.133  3707  4312 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170714T132902 - CU:1002/CP:9640
07-14 13:29:02.134  3707  4312 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132903, SetElapsed=224244, nowELAPSED=223249
,07-14 13:29:02.367  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:29:02.367  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-14 13:29:02.404 10099 10162 I Babel   : connection state changed from UNKNOWN to CONNECTED
,07-14 13:29:02.433  3707  3707 D UsbMonitorService: readUsbState++
,07-14 13:29:02.434  3707  3707 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-14 13:29:02.435  3707  3707 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-14 13:29:02.435  3707  3707 D UsbMonitorService: Posting Message again
,07-14 13:29:02.475  3707  3744 I ActivityManager: KPU : put [com.samsung.android.SettingsReceiver] : 25852 K
07-14 13:29:02.475  3707  3744 I ActivityManager: Killing 8798:com.samsung.android.SettingsReceiver/1000 (adj 906): DHA:empty #33
,07-14 13:29:02.497  3707  4716 D ActivityManager: cleanUpApplicationRecord -- 8798
,07-14 13:29:02.498  4615  4626 D ForegroundUtils: could not check pending caller
,07-14 13:29:03.022  3707  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-14 13:29:03.129  3707  3863 D SamsungAlarmManager: Expired : 4
,07-14 13:29:03.130  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132915, SetElapsed=236346, nowELAPSED=224245
07-14 13:29:03.130  3707  3863 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{27e8fb6 type 2 when 223743 com.android.bluetooth}
,07-14 13:29:03.137  9640  9640 D BtGatt.ScanManager: awakened up at time 224252
,07-14 13:29:03.139  9640  9677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-14 13:29:03.153  9640  9660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-14 13:29:03.153  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-14 13:29:03.155  3707  4718 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{c70d4b7: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
,07-14 13:29:03.173  3707  4836 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170714T132903 - CU:1002/CP:9640
07-14 13:29:03.174  3707  4836 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132904, SetElapsed=225273, nowELAPSED=224289
,07-14 13:29:03.247  3707  4226 E Watchdog: !@Sync 7 [14_lip_13_29_03.247]
,07-14 13:29:03.341  3295  3771 D Netd    : Iface wlan0 link up
,07-14 13:29:03.344  9972  9972 I wpa_supplicant: nl80211: Received scan results (24 BSSes)
,07-14 13:29:03.344  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:29:03.345  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
,07-14 13:29:03.350  3707  3955 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@d18d173
07-14 13:29:03.353  3707  3955 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132903, SetElapsed=224772, nowELAPSED=224468
,07-14 13:29:03.418  3707  4716 I ActivityManager: KPU : put [com.samsung.android.app.memo] : 26916 K
07-14 13:29:03.419  3707  4716 I ActivityManager: Killing 9308:com.samsung.android.app.memo/u0a145 (adj 906): DHA:empty #33
,07-14 13:29:03.450  3707  3937 D ActivityManager: cleanUpApplicationRecord -- 9308
,07-14 13:29:03.452  4615  4626 D ForegroundUtils: could not check pending caller
,07-14 13:29:03.653  9513  9577 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,07-14 13:29:03.654  9513  9577 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
07-14 13:29:03.655  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
07-14 13:29:03.655  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-14 13:29:03.658  3707  3863 D SamsungAlarmManager: Expired : 4
,07-14 13:29:03.659  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132915, SetElapsed=236346, nowELAPSED=224775
07-14 13:29:03.660  3707  3863 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{9648424 type 2 when 224772 com.android.bluetooth}
,07-14 13:29:03.666  9640  9640 D BtGatt.ScanManager: awakened up at time 224781
,07-14 13:29:03.666  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-14 13:29:03.666  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
,07-14 13:29:03.667  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.668  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-14 13:29:03.669  9640  9677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-14 13:29:03.674  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
,07-14 13:29:03.674  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-14 13:29:03.674  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.675  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
07-14 13:29:03.675  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 64496
07-14 13:29:03.675  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
07-14 13:29:03.675  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
07-14 13:29:03.675  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
07-14 13:29:03.675  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
07-14 13:29:03.675  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
07-14 13:29:03.675  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
07-14 13:29:03.675  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
07-14 13:29:03.675  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.675  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
,07-14 13:29:03.676  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.677  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.677  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-14 13:29:03.677  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-14 13:29:03.678  9640  9660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-14 13:29:03.678  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:03.678  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.679  3707  3744 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{7e76b8d: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
07-14 13:29:03.679  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.680  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:03.682  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:03.687  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:03.688  9640  9661 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
07-14 13:29:03.689  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-14 13:29:03.691  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:29:03.691  3707  4718 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170714T132904 - CU:1002/CP:9640
07-14 13:29:03.691  3707  4718 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132904, SetElapsed=225796, nowELAPSED=224807
,07-14 13:29:03.692  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:29:03.692  9513  9577 D BluetoothLeScanner: Stop Scan
07-14 13:29:03.693  9640  9677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-14 13:29:03.694  9640  9813 D BtGatt.GattService: stopScan() - queue size =1
,07-14 13:29:03.695  9640  9813 D BtGatt.GattService: stopScan() - queue size =1
07-14 13:29:03.695  9640  9687 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
,07-14 13:29:03.698  9640  9651 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-14 13:29:03.699  9640  9660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-14 13:29:03.699  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:03.699  9640  9660 E BtGatt.ContextMap: Context not found for ID 5
07-14 13:29:03.700  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-14 13:29:03.700  3707  4675 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{c5bf142: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
07-14 13:29:03.701  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.701  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-14 13:29:03.702  3707  4675 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132915, SetElapsed=236346, nowELAPSED=224817
07-14 13:29:03.702  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.702  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-14 13:29:03.702  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:03.703  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.703  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-14 13:29:03.703  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-14 13:29:03.703  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 64496
07-14 13:29:03.703  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=64496, mManufacturerData=null, mManufacturerDataMask=null]
,07-14 13:29:03.704  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.704  9513  9577 D BluetoothLeScanner: Start Scan
,07-14 13:29:03.706  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:03.708  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:03.710  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:03.711  3707  4312 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170714T132904 - CU:1002/CP:9640
07-14 13:29:03.712  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:03.712  3707  4312 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132904, SetElapsed=225818, nowELAPSED=224827
,07-14 13:29:03.713  9640  9677 D BtGatt.ScanManager: filter size is 1
07-14 13:29:03.714  9640  9677 D BtGatt.ScanManager: delete FilterIndex - 3
07-14 13:29:03.715  9640  9812 D BtGatt.GattService: registerClient() - UUID=9d2c4c3b-d507-4faa-b27b-e04bc33836f8
,07-14 13:29:03.720  9640  9660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
07-14 13:29:03.720  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:03.720  9640  9677 D BtGatt.ScanManager: stopping BLe Batch
,07-14 13:29:03.726  9640  9660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-14 13:29:03.726  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-14 13:29:03.726  9640  9677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-14 13:29:03.732  9640  9660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-14 13:29:03.732  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-14 13:29:03.732  3707  3987 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{1b40553: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
,07-14 13:29:03.734  3707  3987 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132915, SetElapsed=236346, nowELAPSED=224849
,07-14 13:29:03.735  3707  4679 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{477be90: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
,07-14 13:29:03.819  9640  9660 D BtGatt.GattService: onClientRegistered() - UUID=9d2c4c3b-d507-4faa-b27b-e04bc33836f8, clientIf=5, status=0
07-14 13:29:03.820  9513  9524 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
,07-14 13:29:03.822  9640  9652 D BtGatt.GattService: start scan with filters
,07-14 13:29:03.825  9640  9652 D BtGatt.GattService: getScanSettings
,07-14 13:29:03.828  9640  9652 D BtGatt.GattService: Is it foreground application = true
07-14 13:29:03.828  9640  9652 D BtGatt.GattService: not a background application
,07-14 13:29:03.841  9640  9687 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
,07-14 13:29:03.842  9640  9687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@238f8b8
07-14 13:29:03.842  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,07-14 13:29:03.842  9640  9677 D BtGatt.ScanManager: handling starting scan
,07-14 13:29:03.843  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.843  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-14 13:29:03.844  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.845  9640  9677 D BluetoothAdapter: STATE_ON
,07-14 13:29:03.845  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:03.846  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-14 13:29:03.846  9513  9577 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-14 13:29:03.847  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,07-14 13:29:03.847  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-14 13:29:03.847  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-14 13:29:03.848  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:29:03.848  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
07-14 13:29:03.849  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
07-14 13:29:03.849  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-14 13:29:03.850  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-14 13:29:03.852  9640  9677 D BluetoothAdapter: STATE_ON
07-14 13:29:03.853  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-14 13:29:03.855  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-14 13:29:03.855  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-14 13:29:03.855  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-14 13:29:03.856  9513  9513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-14 13:29:03.856  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-14 13:29:03.857  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
07-14 13:29:03.857  9513 10168 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-14 13:29:03.863  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-14 13:29:03.864  9513  9577 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-14 13:29:03.867  9640  9660 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-14 13:29:03.868  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:03.869  9640  9677 D BtGatt.ScanManager: set filter index= 4 for clientIf= 5
07-14 13:29:03.869  9640  9677 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-14 13:29:03.869  9640  9677 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-14 13:29:03.869  9640  9677 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
07-14 13:29:03.877  9513 10168 D BluetoothSocket: bindListen(): myUserId = 0
07-14 13:29:03.877  9513 10168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-14 13:29:03.878  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:29:03.882  9640  9660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
07-14 13:29:03.882  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:03.883  9640  9677 D BtGatt.ScanManager: Starting BLE batch scan
07-14 13:29:03.883  9640  9677 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-14 13:29:03.885  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:29:03.890  9513 10168 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-14 13:29:03.890  9513 10168 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@10ccdcc, port: 6, type: 1, local socket address: null, socket type: 0
,07-14 13:29:03.893  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:03.898  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:03.907  9640  9660 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-14 13:29:03.908  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-14 13:29:03.910  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:03.914  9640  9660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-14 13:29:03.914  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-14 13:29:03.915  3707  4718 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{66c3389: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
,07-14 13:29:03.915  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.916  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:03.916  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.916  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-14 13:29:03.916  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-14 13:29:03.917  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "9efc9363-3d2b-4b01-abd9-143186647519", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-14 13:29:03.917  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E 94 4A 3E
07-14 13:29:03.917  9513  9577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-14 13:29:03.918  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-14 13:29:03.918  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.919  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.919  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-14 13:29:03.919  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-14 13:29:03.920  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:03.920  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:03.921  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[9efc9363-3d2b-4b01-abd9-143186647519], mManufacturerSpecificData={}, mServiceData={9efc9363-3d2b-4b01-abd9-143186647519=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:03.923  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:03.924  3707  4313 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170714T132904 - CU:1002/CP:9640
,07-14 13:29:03.924  3707  4313 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132904, SetElapsed=226032, nowELAPSED=225040
07-14 13:29:03.925  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:29:03.925  9513  9577 D BluetoothAdapter: isSecureModeEnabled
07-14 13:29:03.926  9640  9812 D BtConfig.SecureMode: isSecureModeOn:false
,07-14 13:29:03.926  9513  9577 D BluetoothLeAdvertiser: start advertising
,07-14 13:29:03.927  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:03.932  9640  9652 D BtGatt.GattService: registerClient() - UUID=c3683a25-b735-496e-9f9e-2845d54b5a03
,07-14 13:29:04.034  9640  9660 D BtGatt.GattService: onClientRegistered() - UUID=c3683a25-b735-496e-9f9e-2845d54b5a03, clientIf=6, status=0
,07-14 13:29:04.035  9513  9525 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,07-14 13:29:04.037  9640  9812 E BtGatt.ContextMap: Context not found for ID 6
07-14 13:29:04.038  9640  9676 D BtGatt.AdvertiseManager: message : 0
07-14 13:29:04.038  9640  9687 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-14 13:29:04.039  9640  9676 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-14 13:29:04.039  9640  9676 D BtGatt.AdvertiseManager: size of list is =0
,07-14 13:29:04.043  9640  9676 D BtGatt.AdvertiseManager: starting advertising
,07-14 13:29:04.046  9640  9676 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-14 13:29:04.049  9640  9728 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-14 13:29:04.059  9640  9660 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,07-14 13:29:04.061  9640  9676 D BtGatt.AdvertiseManager: starting multi advertising
,07-14 13:29:04.066  9640  9660 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
07-14 13:29:04.066  9640  9676 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,07-14 13:29:04.067  9640  9676 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-14 13:29:04.067  9640  9676 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
07-14 13:29:04.067  9640  9676 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
07-14 13:29:04.067  9513  9524 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-14 13:29:04.068  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:04.069  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:04.069  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-14 13:29:04.069  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:04.070  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:04.070  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:04.071  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:04.071  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:04.072  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:04.072  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:04.073  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:04.073  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,07-14 13:29:04.073  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
07-14 13:29:04.073  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-14 13:29:04.076  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-14 13:29:04.076  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:04.081  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:04.082  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:04.082  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:04.083  9513  9513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,07-14 13:29:04.084  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-14 13:29:04.084  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-14 13:29:04.084  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-14 13:29:04.085  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-14 13:29:04.085  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-14 13:29:04.086  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-14 13:29:04.086  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:29:04.086  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
07-14 13:29:04.086  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
07-14 13:29:04.086  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-14 13:29:04.087  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
07-14 13:29:04.087  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-14 13:29:04.087  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-14 13:29:04.087  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-14 13:29:04.092  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-14 13:29:04.092  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,07-14 13:29:04.093  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-14 13:29:04.093  9513  9513 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,07-14 13:29:04.094  9513  9513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,07-14 13:29:04.595  9513  9513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,07-14 13:29:04.599  9513  9513 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-14 13:29:04.600  9513  9513 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-14 13:29:04.916  3707  3863 D SamsungAlarmManager: Expired : 4
,07-14 13:29:04.918  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132915, SetElapsed=236346, nowELAPSED=226033
07-14 13:29:04.918  3707  3863 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{8bbdf8e type 2 when 225531 com.android.bluetooth}
,07-14 13:29:04.924  9640  9640 D BtGatt.ScanManager: awakened up at time 226040
,07-14 13:29:04.927  9640  9677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-14 13:29:04.941  9640  9660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-14 13:29:04.941  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-14 13:29:04.943  3707  3743 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{befa3af: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
,07-14 13:29:04.961  3707  3965 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170714T132905 - CU:1002/CP:9640
07-14 13:29:04.961  3707  3965 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132905, SetElapsed=227061, nowELAPSED=226077
,07-14 13:29:05.265  3707  4679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-14 13:29:05.314  4497  4497 D io_stats: !@   8,0 r 25253 2275604 w 5045 204800 d 664 73216 f 1999 1999 iot 11280 10729 th 475824 0 0 pt 0 inp 0 0 226.428
,07-14 13:29:05.398  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:29:05.398  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-14 13:29:05.946  3707  3863 D SamsungAlarmManager: Expired : 4
,07-14 13:29:05.947  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132915, SetElapsed=236346, nowELAPSED=227062
07-14 13:29:05.947  3707  3863 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{14233bc type 2 when 226559 com.android.bluetooth}
,07-14 13:29:05.953  9640  9640 D BtGatt.ScanManager: awakened up at time 227069
,07-14 13:29:05.955  9640  9677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-14 13:29:05.964  3707  3908 I ActivityManager: KPU : put [com.samsung.android.bluelightfilter] : 25736 K
07-14 13:29:05.965  3707  3908 I ActivityManager: Killing 9325:com.samsung.android.bluelightfilter/u0a184 (adj 906): DHA:empty #33
,07-14 13:29:05.973  9640  9660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-14 13:29:05.973  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-14 13:29:05.975  3707  3987 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{45b7f45: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
,07-14 13:29:05.987  3707  4737 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170714T132906 - CU:1002/CP:9640
,07-14 13:29:05.988  3707  4737 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132906, SetElapsed=228093, nowELAPSED=227103
,07-14 13:29:06.003  3707  4312 D ActivityManager: cleanUpApplicationRecord -- 9325
,07-14 13:29:06.004  4615  4627 D ForegroundUtils: could not check pending caller
,07-14 13:29:06.977  3707  3863 D SamsungAlarmManager: Expired : 4
,07-14 13:29:06.978  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132915, SetElapsed=236346, nowELAPSED=228093
07-14 13:29:06.978  3707  3863 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{b9ccbcb type 2 when 227592 com.android.bluetooth}
,07-14 13:29:06.983  9640  9640 D BtGatt.ScanManager: awakened up at time 228098
,07-14 13:29:06.984  9640  9677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-14 13:29:06.997  9640  9660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-14 13:29:06.997  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:06.998  3707  3987 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{1dccfa8: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
,07-14 13:29:07.007  3707  4737 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170714T132907 - CU:1002/CP:9640
07-14 13:29:07.007  3707  4737 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132908, SetElapsed=229115, nowELAPSED=228123
,07-14 13:29:07.086  9513  9577 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,07-14 13:29:07.087  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-14 13:29:07.087  9513  9577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-14 13:29:07.087  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-14 13:29:07.087  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-14 13:29:07.087  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-14 13:29:07.087  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-14 13:29:07.087  9513  9577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-14 13:29:07.087  9513 10168 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-14 13:29:07.088  9513 10168 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-14 13:29:07.088  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-14 13:29:07.088  9513  9513 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-14 13:29:07.088  9513  9577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@844d307 removed from the list
07-14 13:29:07.088  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@844d307 removed from the list
07-14 13:29:07.088  9513 10168 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-14 13:29:07.088  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-14 13:29:07.088  9513  9577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-14 13:29:07.088  9513  9513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-14 13:29:07.088  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.088  9513  9513 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-14 13:29:07.088  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-14 13:29:07.088  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-14 13:29:07.089  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.089  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:07.090  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.090  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-14 13:29:07.090  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:07.092  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:29:07.093  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:07.094  9640  9661 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
07-14 13:29:07.094  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-14 13:29:07.095  9640  9677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-14 13:29:07.097  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:07.100  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:29:07.100  9513  9577 D BluetoothLeScanner: Stop Scan
,07-14 13:29:07.101  9640  9660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-14 13:29:07.101  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:07.101  9640  9813 D BtGatt.GattService: stopScan() - queue size =1
07-14 13:29:07.101  9640  9813 D BtGatt.GattService: stopScan() - queue size =1
,07-14 13:29:07.102  9640  9687 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
07-14 13:29:07.102  3707  3965 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{639cac1: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
07-14 13:29:07.103  9640  9661 D BtGatt.GattService: unregisterClient() - clientIf=5
07-14 13:29:07.104  3707  3965 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132915, SetElapsed=236346, nowELAPSED=228219
,07-14 13:29:07.104  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-14 13:29:07.105  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.105  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-14 13:29:07.105  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.106  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.106  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.106  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,07-14 13:29:07.107  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-14 13:29:07.109  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:07.110  9513  9577 D BluetoothAdapter: STATE_ON
07-14 13:29:07.110  9513  9577 D BluetoothLeAdvertiser: stop advertising
,07-14 13:29:07.111  9640  9651 E BtGatt.ContextMap: Context not found for ID 6
,07-14 13:29:07.112  9640  9687 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,07-14 13:29:07.112  9640  9676 D BtGatt.AdvertiseManager: message : 1
07-14 13:29:07.113  9640  9676 D BtGatt.AdvertiseManager: stop advertise for client =  6
07-14 13:29:07.113  9640  9676 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
07-14 13:29:07.113  3707  4717 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170714T132907 - CU:1002/CP:9640
07-14 13:29:07.113  3707  4717 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132908, SetElapsed=229221, nowELAPSED=228229
,07-14 13:29:07.115  9640  9677 D BtGatt.ScanManager: filter size is 1
07-14 13:29:07.115  9640  9677 D BtGatt.ScanManager: delete FilterIndex - 4
07-14 13:29:07.116  9640  9676 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-14 13:29:07.120  9640  9660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
07-14 13:29:07.120  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:07.120  9640  9677 D BtGatt.ScanManager: stopping BLe Batch
,07-14 13:29:07.124  9640  9660 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
07-14 13:29:07.124  9640  9660 D BtGatt.GattService: Client app is not null!
,07-14 13:29:07.125  9513  9525 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-14 13:29:07.126  9640  9813 D BtGatt.GattService: unregisterClient() - clientIf=6
,07-14 13:29:07.128  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-14 13:29:07.129  9640  9660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-14 13:29:07.129  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:07.129  9640  9677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-14 13:29:07.129  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.129  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-14 13:29:07.130  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.130  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.131  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.131  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-14 13:29:07.131  9513  9577 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-14 13:29:07.132  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-14 13:29:07.132  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.134  9640  9660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-14 13:29:07.135  9640  9660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-14 13:29:07.135  3707  4737 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{4a85266: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
07-14 13:29:07.136  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.136  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-14 13:29:07.136  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.137  3707  4737 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132915, SetElapsed=236346, nowELAPSED=228252
07-14 13:29:07.137  9513  9577 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-14 13:29:07.137  9513  9577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c042c34 removed from the list
07-14 13:29:07.137  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-14 13:29:07.137  9513  9577 D io.jxcore.node.ConnectivityMonitor: stop
07-14 13:29:07.137  9513  9577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-14 13:29:07.137  9513  9513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-14 13:29:07.137  9513  9577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-14 13:29:07.138  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-14 13:29:07.138  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:29:07.138  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-14 13:29:07.138  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
07-14 13:29:07.139  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-14 13:29:07.139  9513  9577 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
07-14 13:29:07.139  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-14 13:29:07.139  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-14 13:29:07.139  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-14 13:29:07.139  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePe,erDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-14 13:29:07.140  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-14 13:29:07.140  9513  9513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-14 13:29:07.140  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-14 13:29:07.140  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-14 13:29:07.140  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-14 13:29:07.140  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-14 13:29:07.141  9513  9577 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-14 13:29:07.141  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-14 13:29:07.141  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-14 13:29:07.141  9513  9513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-14 13:29:07.142  9513  9513 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-14 13:29:07.142  9513  9577 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
07-14 13:29:07.142  3707  4716 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9640 / op:PendingIntent{5aa59a7: PendingIntentRecord{bad0935 com.android.bluetooth broadcastIntent}}
07-14 13:29:07.144  9513  9577 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
07-14 13:29:07.145  9513  9577 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
07-14 13:29:07.147  9513  9577 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,07-14 13:29:07.148  9513  9577 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,07-14 13:29:07.150  9513  9577 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,07-14 13:29:07.152  9513  9577 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,07-14 13:29:07.153  9513  9577 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,07-14 13:29:07.643  9513  9513 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-14 13:29:08.429  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:29:08.429  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-14 13:29:08.968  3707  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-14 13:29:08.980  3707  3783 I ActivityManager: KPU : put [com.samsung.android.lool] : 26680 K
07-14 13:29:08.980  3707  3783 I ActivityManager: Killing 9372:com.samsung.android.lool/1000 (adj 906): DHA:empty #33
,07-14 13:29:09.024  3707  4717 D ActivityManager: cleanUpApplicationRecord -- 9372
,07-14 13:29:09.026  4615  4627 D ForegroundUtils: could not check pending caller
,07-14 13:29:09.160  9513  9577 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,07-14 13:29:09.298  9513 10172 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 254, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:09.298  9513 10172 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:09.298  9513 10172 D io.jxcore.node.StreamCopyingThread:  id: 83
,07-14 13:29:09.415  9513  9518 I art     : Do partial code cache collection, code=19KB, data=31KB
07-14 13:29:09.416  9513  9518 I art     : After code cache collection, code=17KB, data=30KB
07-14 13:29:09.416  9513  9518 I art     : Increasing code cache capacity to 128KB
,07-14 13:29:10.071  9513 10172 W !!      : call onHalfStreamCopied
07-14 13:29:10.071  9513 10172 I testCopyDataAndClose: closing input stream
,07-14 13:29:10.319  4497  4497 D io_stats: !@   8,0 r 25253 2275604 w 5059 204932 d 666 73224 f 2001 2001 iot 11280 10732 th 467428 0 0 pt 0 inp 0 0 231.433
,07-14 13:29:10.452  3707  5610 D SSRM:f  : SIOP:: AP = 280, PST = 282 (W:10), CP = 230, CUR = 115, LCD = 57
,07-14 13:29:10.542  3707  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 254, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread:  id: 83
,07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread:  id: 83
07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 254, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:10.749  9513 10172 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,07-14 13:29:11.457  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:29:11.457  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-14 13:29:12.358  9513  9577 I StreamCopyingThreadTest: Starting test: testCopyBigData
,07-14 13:29:12.392  9513 10173 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 257, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:12.392  9513 10173 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:12.392  9513 10173 D io.jxcore.node.StreamCopyingThread:  id: 85
,07-14 13:29:12.829  3707  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-14 13:29:12.835  3707  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-14 13:29:12.850  3707  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-14 13:29:12.859  3707  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-14 13:29:12.865  3707  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-14 13:29:12.879  3707  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-14 13:29:13.368  3707  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 257, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread:  id: 85
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread:  id: 85
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 257, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:13.872  9513 10173 D io.jxcore.node.StreamCopyingThread:  id: 85 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,07-14 13:29:14.482  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:29:14.483  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-14 13:29:15.147  4738  4812 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 2ms lastUpdatedAfter : 31863 ms mFlush_time_threasold : 2000 mCurrentSize : 229
,07-14 13:29:15.174  5059 10175 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-14 13:29:15.199  5059  6570 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-14 13:29:15.208  9513  9577 I StreamCopyingThreadTest: Starting test: testRunNotify
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 259, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread:  id: 86
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 259, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread:  id: 86
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread:  id: 86
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 259, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:15.209  9513 10176 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
07-14 13:29:15.209  9513  9577 I StreamCopyingThreadTest: Starting test: testSetBufferSize
07-14 13:29:15.209  9513  9577 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-14 13:29:15.210  9513  9577 I StreamCopyingThreadTest: Starting test: testRunWithException
07-14 13:29:15.210  9513 10177 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 263, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:15.210  9513 10177 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:15.210  9513 10177 D io.jxcore.node.StreamCopyingThread:  id: 89
07-14 13:29:15.210  9513 10177 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 263, thread name: My test thread name): Test exception.
07-14 13:29:15.210  9513 10177 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 263, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:15.210  9513 10177 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:15.210  9513 10177 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
07-14 13:29:15.210  9513 10177 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
07-14 13:29:15.210  9513 10177 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 263, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-14 13:29:15.210  9513 10177 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-14 13:29:15.210  9513 10177 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: testIsBluetoothEnabled(io.jxcore.node.ConnectivityMonitorTest)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: BT should be enabled
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner:      but: was <false>
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: BT should be enabled
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner:      but: was <false>
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testIsBluetoothEnabled(ConnectivityMonitorTest.java:328)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRu,nner.java:78)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRu,nner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:73)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:751)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:154)
07-14 13:29:15.211  9513  9577 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
07-14 13:29:15.212  9513  9577 I jxcore-log: 2017-07-14 11:29:15 - DEBUG UnitTest_app: 'Running unit tests'
07-14 13:29:15.212  9513  9577 I jxcore-log: 
07-14 13:29:15.212  9513  9577 I jxcore-log: *Native tests were executed*
07-14 13:29:15.212  9513  9577 I jxcore-log: 
07-14 13:29:15.212  9513  9577 I jxcore-log: Total number of executed tests:  78
07-14 13:29:15.212  9513  9577 I jxcore-log: 
07-14 13:29:15.212  9513  9577 I jxcore-log: Number of passed tests:  75
07-14 13:29:15.212  9513  9577 I jxcore-log: 
07-14 13:29:15.212  9513  9577 I jxcore-log: Number of failed tests:  1
07-14 13:29:15.212  9513  9577 I jxcore-log: 
07-14 13:29:15.212  9513  9577 I jxcore-log: Number of ignored tests:  2
07-14 13:29:15.212  9513  9577 I jxcore-log: 
07-14 13:29:15.212  9513  9577 I jxcore-log: Total duration:  50209
07-14 13:29:15.212  9513  9577 I jxcore-log: 
07-14 13:29:15.213  9513  9577 I jxcore-log: Failed to execute UT.
07-14 13:29:15.213  9513  9577 I jxcore-log: 
07-14 13:29:15.213  9513  9577 I jxcore-log: 2017-07-14 11:29:15 - DEBUG UnitTest_app: 'Failed to execute UT.'
07-14 13:29:15.213  9513  9577 I jxcore-log: 
07-14 13:29:15.213  9513  9577 I jxcore-log: 2017-07-14 11:29:15 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G930F''
07-14 13:29:15.213  9513  9577 I jxcore-log: 
07-14 13:29:15.214  9513  9577 I jxcore-log: 2017-07-14 11:29:15 - WARN testUtils: 'myNameCallback not set!'
07-14 13:29:15.214  9513  9577 I jxcore-log: 
07-14 13:29:15.215  5059  6570 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-14 13:29:15.230  3707  3863 D SamsungAlarmManager: Expired : 4
,07-14 13:29:15.230  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T133755, SetElapsed=757048, nowELAPSED=236346
07-14 13:29:15.231  3707  3863 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170714T133000, SetElapsed=281116, nowELAPSED=236346
07-14 13:29:15.231  3707  3863 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@5a1d9e2 alarm=Alarm{7a9aa4a type 2 when 236346 android}
,07-14 13:29:15.233  3707  3927 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 32000: mInRange : true
,07-14 13:29:15.235  9972  9972 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-14 13:29:15.235  9972  9972 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-14 13:29:15.242  3707  3927 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170714T132947 - CU:1000/CP:3707
07-14 13:29:15.242  3707  3927 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132947, SetElapsed=268349, nowELAPSED=236358
,07-14 13:29:15.245  3707  3955 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170714T132930 - CU:1000/CP:3707
07-14 13:29:15.245  3707  3955 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132930, SetElapsed=251357, nowELAPSED=236361
,07-14 13:29:15.249  9972  9972 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-14 13:29:15.260  5059  5499 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-14 13:29:15.298  5059  6570 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-14 13:29:15.301  3707  3908 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-14 13:29:15.301  3707  3908 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4220, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-14 13:29:15.301  3707  3908 D BatteryService: online:4, current avg:-10, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:-846
07-14 13:29:15.301  3707  3707 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-14 13:29:15.307  3707  3707 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-14 13:29:15.307  3707  3707 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
07-14 13:29:15.308  3707  3707 D GameManagerService: new battery level: 100
07-14 13:29:15.308  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-14 13:29:15.309  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-14 13:29:15.312  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-14 13:29:15.316  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,07-14 13:29:15.316  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,07-14 13:29:15.321  4497  4497 D io_stats: !@   8,0 r 25253 2275604 w 5086 205216 d 668 73232 f 2011 2011 iot 11300 10742 th 471184 0 0 pt 0 inp 0 0 236.436
,07-14 13:29:15.321  9640  9640 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-14 13:29:15.322  9640  9765 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-14 13:29:15.339  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-14 13:29:15.355  5059  5499 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-14 13:29:15.390  5059  5499 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-14 13:29:15.426  5059  6570 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-14 13:29:16.288  3707  3965 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gSCM@ADE
,07-14 13:29:16.289  3707  3965 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gSCM@ADE
,07-14 13:29:16.298  3707  3965 I Telecom : com.android.server.telecom.PhoneAccountRegistrar: SimCallManager queried, returning: null: TSI.gSCM@ADE
,07-14 13:29:16.311 10099 10099 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-14 13:29:16.337 10099 10099 W Babel   : BAM#gBA: invalid account id: -1
,07-14 13:29:16.338 10099 10099 W Babel   : BAM#gBA: invalid account id: -1
07-14 13:29:16.338 10099 10099 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-14 13:29:16.351  3707  4675 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gSCM@ADM
07-14 13:29:16.352  3707  4675 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gSCM@ADM
,07-14 13:29:16.356  3707  4675 I Telecom : com.android.server.telecom.PhoneAccountRegistrar: SimCallManager queried, returning: null: TSI.gSCM@ADM
,07-14 13:29:16.650  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
07-14 13:29:16.650  9513  9577 I jxcore-log: 
,07-14 13:29:16.654  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
07-14 13:29:16.654  9513  9577 I jxcore-log: 
,07-14 13:29:16.663  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
07-14 13:29:16.663  9513  9577 I jxcore-log: 
,07-14 13:29:16.820  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
07-14 13:29:16.820  9513  9577 I jxcore-log: 
,07-14 13:29:16.849  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
07-14 13:29:16.849  9513  9577 I jxcore-log: 
,07-14 13:29:16.857  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testTests.js'
07-14 13:29:16.857  9513  9577 I jxcore-log: 
,07-14 13:29:16.890  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testUsn.js'
07-14 13:29:16.890  9513  9577 I jxcore-log: 
,07-14 13:29:16.908  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
07-14 13:29:16.908  9513  9577 I jxcore-log: 
,07-14 13:29:16.912  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
07-14 13:29:16.912  9513  9577 I jxcore-log: 
,07-14 13:29:16.957  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
07-14 13:29:16.957  9513  9577 I jxcore-log: 
,07-14 13:29:16.960  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
07-14 13:29:16.960  9513  9577 I jxcore-log: 
,07-14 13:29:16.963  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
07-14 13:29:16.963  9513  9577 I jxcore-log: 
,07-14 13:29:16.967  9513  9577 I jxcore-log: 2017-07-14 11:29:16 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
07-14 13:29:16.967  9513  9577 I jxcore-log: 
,07-14 13:29:17.283  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
07-14 13:29:17.283  9513  9577 I jxcore-log: 
,07-14 13:29:17.289  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
07-14 13:29:17.289  9513  9577 I jxcore-log: 
,07-14 13:29:17.353  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testHttp.js'
07-14 13:29:17.353  9513  9577 I jxcore-log: 
,07-14 13:29:17.356  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
07-14 13:29:17.356  9513  9577 I jxcore-log: 
,07-14 13:29:17.374  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
07-14 13:29:17.374  9513  9577 I jxcore-log: 
,07-14 13:29:17.378  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
07-14 13:29:17.378  9513  9577 I jxcore-log: 
,07-14 13:29:17.409  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
07-14 13:29:17.409  9513  9577 I jxcore-log: 
,07-14 13:29:17.450  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
07-14 13:29:17.450  9513  9577 I jxcore-log: 
,07-14 13:29:17.482  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
07-14 13:29:17.482  9513  9577 I jxcore-log: 
,07-14 13:29:17.497  3707  3927 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-14 13:29:17.498  3707  3927 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-14 13:29:17.512  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
07-14 13:29:17.512  9513  9577 I jxcore-log: 
,07-14 13:29:17.520  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
07-14 13:29:17.520  9513  9577 I jxcore-log: 
,07-14 13:29:17.566  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
07-14 13:29:17.566  9513  9577 I jxcore-log: 
,07-14 13:29:17.596  9513  9577 I jxcore-log: 2017-07-14 11:29:17 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
07-14 13:29:17.596  9513  9577 I jxcore-log: 
,07-14 13:29:18.216  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
07-14 13:29:18.216  9513  9577 I jxcore-log: 
,07-14 13:29:18.242  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
07-14 13:29:18.242  9513  9577 I jxcore-log: 
,07-14 13:29:18.247  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
07-14 13:29:18.247  9513  9577 I jxcore-log: 
,07-14 13:29:18.251  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
07-14 13:29:18.251  9513  9577 I jxcore-log: 
,07-14 13:29:18.270  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
07-14 13:29:18.270  9513  9577 I jxcore-log: 
,07-14 13:29:18.289  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
07-14 13:29:18.289  9513  9577 I jxcore-log: 
,07-14 13:29:18.303  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
07-14 13:29:18.303  9513  9577 I jxcore-log: 
,07-14 13:29:18.311  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
07-14 13:29:18.311  9513  9577 I jxcore-log: 
,07-14 13:29:18.318  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
07-14 13:29:18.318  9513  9577 I jxcore-log: 
,07-14 13:29:18.327  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
07-14 13:29:18.327  9513  9577 I jxcore-log: 
,07-14 13:29:18.344  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
07-14 13:29:18.344  9513  9577 I jxcore-log: 
,07-14 13:29:18.357  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
07-14 13:29:18.357  9513  9577 I jxcore-log: 
,07-14 13:29:18.363  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
07-14 13:29:18.363  9513  9577 I jxcore-log: 
,07-14 13:29:18.528  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
07-14 13:29:18.528  9513  9577 I jxcore-log: 
,07-14 13:29:18.602  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
07-14 13:29:18.602  9513  9577 I jxcore-log: 
,07-14 13:29:18.616  9513  9577 D BluetoothAdapter: STATE_ON
,07-14 13:29:18.623  9513  9577 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-14 13:29:18.623  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO testUtils: 'BLE multiple advertisement supported'
07-14 13:29:18.623  9513  9577 I jxcore-log: 
07-14 13:29:18.625  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - DEBUG UnitTest_app: 'Unit Test app is loaded'
07-14 13:29:18.625  9513  9577 I jxcore-log: 
,07-14 13:29:18.632  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-14 13:29:18.632  9513  9577 I jxcore-log: 
07-14 13:29:18.633  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-14 13:29:18.633  9513  9577 I jxcore-log: 
,07-14 13:29:18.633  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-14 13:29:18.633  9513  9577 I jxcore-log: 
07-14 13:29:18.633  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-14 13:29:18.633  9513  9577 I jxcore-log: 
07-14 13:29:18.634  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-14 13:29:18.634  9513  9577 I jxcore-log: 
,07-14 13:29:18.634  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-14 13:29:18.634  9513  9577 I jxcore-log: 
07-14 13:29:18.634  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-14 13:29:18.634  9513  9577 I jxcore-log: 
07-14 13:29:18.634  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-14 13:29:18.634  9513  9577 I jxcore-log: 
07-14 13:29:18.635  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-14 13:29:18.635  9513  9577 I jxcore-log: 
07-14 13:29:18.635  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-14 13:29:18.635  9513  9577 I jxcore-log: 
07-14 13:29:18.635  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-14 13:29:18.635  9513  9577 I jxcore-log: 
07-14 13:29:18.635  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-14 13:29:18.635  9513  9577 I jxcore-log: 
07-14 13:29:18.635  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-14 13:29:18.635  9513  9577 I jxcore-log: 
07-14 13:29:18.635  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-14 13:29:18.635  9513  9577 I jxcore-log: 
,07-14 13:29:18.644  9513  9513 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,07-14 13:29:18.644  9513  9513 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,07-14 13:29:18.666  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
07-14 13:29:18.666  9513  9577 I jxcore-log: 
,07-14 13:29:18.746  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - DEBUG CoordinatedClient: 'connected to the test server'
07-14 13:29:18.746  9513  9577 I jxcore-log: 
,07-14 13:29:18.949  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
07-14 13:29:18.949  9513  9577 I jxcore-log: 
,07-14 13:29:18.951  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - DEBUG CoordinatedClient: 'test client failed'
07-14 13:29:18.951  9513  9577 I jxcore-log: 
,07-14 13:29:18.957  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - DEBUG CoordinatedClient: 'device disconnected from the test server'
07-14 13:29:18.957  9513  9577 I jxcore-log: 
,07-14 13:29:18.962  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.thaliproject.thalitest/files/www/jxcore/lib/CoordinatedClient.js:253:22
07-14 13:29:18.962  9513  9577 I jxcore-log: tryCatcher@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
07-14 13:29:18.962  9513  9577 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
07-14 13:29:18.962  9513  9577 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
07-14 13:29:18.962  9513  9577 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
07-14 13:29:18.962  9513  9577 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
07-14 13:29:18.962  9513  9577 I jxcore-log: 
,07-14 13:29:18.963  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
07-14 13:29:18.963  9513  9577 I jxcore-log: 
,07-14 13:29:18.975  9513  9577 I jxcore-log: 2017-07-14 11:29:18 - ERROR runTests: 'Test client failed: Native unit tests failed
07-14 13:29:18.975  9513  9577 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.thaliproject.thalitest/files/www/jxcore/lib/CoordinatedClient.js:253:22
07-14 13:29:18.975  9513  9577 I jxcore-log: tryCatcher@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
07-14 13:29:18.975  9513  9577 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
07-14 13:29:18.975  9513  9577 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
07-14 13:29:18.975  9513  9577 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
07-14 13:29:18.975  9513  9577 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
07-14 13:29:18.975  9513  9577 I jxcore-log: 
,07-14 13:29:19.169  4738  4812 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 4ms lastUpdatedAfter : 4021 ms mFlush_time_threasold : 2000 mCurrentSize : 232
,07-14 13:29:19.258  3295  3771 D Netd    : Iface wlan0 link up
,07-14 13:29:19.260  9972  9972 I wpa_supplicant: nl80211: Received scan results (25 BSSes)
,07-14 13:29:19.261  3707  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-14 13:29:19.261  3707  3801 D Tethering: interfaceStatusChanged wlan0, true
07-14 13:29:19.266  3707  3955 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3707 / listener:android.app.AlarmManager$ListenerWrapper@fb772d8
,07-14 13:29:19.268  3707  3955 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170714T132947, SetElapsed=268349, nowELAPSED=240384
,07-14 13:29:19.470 10189 10189 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 10189 | app_process
07-14 13:29:19.470 10189 10189 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
,07-14 13:29:19.476 10189 10189 E appproc : Enhanced Zygote ASLR: ro.knox.enhance.zygote.aslr != 1. Enhanced Zygote ASLR is DISABLED!
07-14 13:29:19.476 10189 10189 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,07-14 13:29:19.478 10189 10189 D AndroidRuntime: CheckJNI is OFF
07-14 13:29:19.478 10189 10189 D AndroidRuntime: addProductProperty: start
,07-14 13:29:19.516 10189 10189 I [saiv 1.1]: saiv_OnLoadJNI.cpp(38): _init: Version 1.1 Build # 3532
07-14 13:29:19.516 10189 10189 I [saiv 1.1]: saiv_OnLoadJNI.cpp(43): _init: _init() was called
,07-14 13:29:19.531 10189 10189 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-14 13:29:19.531 10189 10189 I MLDAP   :            libMLDAP/MLDAP.c:  53:  MLDAP_LIB v1.1.15
07-14 13:29:19.531 10189 10189 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
,07-14 13:29:19.575 10189 10189 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl
,07-14 13:29:19.593 10189 10189 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,07-14 13:29:19.608 10189 10189 I Enhanced Zygote ASLR: DISABLED!
07-14 13:29:19.609 10189 10189 I Radio-JNI: register_android_hardware_Radio DONE
,07-14 13:29:19.611 10189 10189 D ReflectionHelper: loadKlass() : caller=android.app.Activity.<clinit>:7525 <bottom of call stack> 
07-14 13:29:19.612 10189 10189 D ReflectionHelper: Reflecting method.....  class <onScreenChanged>
,07-14 13:29:19.612 10189 10189 E SemAffinityControl: SemAffinityControl: registerfunction enter
,07-14 13:29:19.621 10189 10189 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-14 13:29:19.634  3707  4313 D PackageManager: START PACKAGE DELETE: observer{109425773}
07-14 13:29:19.634  3707  4313 D PackageManager: pkg{com.thaliproject.thalitest}
07-14 13:29:19.634  3707  4313 D PackageManager: user{0}
07-14 13:29:19.634  3707  4313 D PackageManager: caller{2000}
07-14 13:29:19.634  3707  4313 D PackageManager: flags{2}
,07-14 13:29:19.634  3707  4313 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-14 13:29:19.634  3707  4313 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-14 13:29:19.635  3707  4313 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-14 13:29:19.635  3707  4313 D PackageManager: deletePackageAsUser- pkg:com.thaliproject.thalitest, userId:0, flag2
07-14 13:29:19.635  3707  4313 D PackageManager: deletePackageAsUser- pkg:com.thaliproject.thalitest, userId:0, flag2
07-14 13:29:19.636  3707  3823 D ApplicationPolicy: getApplicationUninstallationEnabled
,07-14 13:29:19.639  3707  3823 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-14 13:29:19.640  3707  3823 D DevicePolicyManagerService: PfW getPlayForWorkProxy() 0
,07-14 13:29:19.646  3707  3823 D DevicePolicyManagerService: PfW getPlayForWorkProxy() flags & FLAG_ALLOW_PROXY_FOR_PFW 0
,07-14 13:29:19.646  3707  3823 D DevicePolicyManagerService: PfW getPlayForWorkProxy() flag 0 does not allow PfW
07-14 13:29:19.647  3707  3783 I ActivityManager: Force stopping com.thaliproject.thalitest appid=10033 user=-1: deletePackageX
,07-14 13:29:19.649  3707  3783 I ActivityManager: Killing 9513:com.thaliproject.thalitest/u0a33 (adj 0): stop com.thaliproject.thalitest
,07-14 13:29:19.652  3707  3783 D ActivityManager: cleanUpApplicationRecord -- 9513
,07-14 13:29:19.655  3707  3783 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=null next=ActivityRecord{785c0d0 u0 com.thaliproject.thalitest/.MainActivity t5} mFocusedStack=ActivityStack{c202c12d0 stackId=1, 2 tasks}
07-14 13:29:19.658  3707  3783 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3707  pkgName : AMS_RESUME@CPU_MIN@7
,07-14 13:29:19.661  3707  3783 D ActivityManager: mActivityResumeBooster.acquire()
,07-14 13:29:19.663  3707  3823 D PackageManager.SDP: Start removing package directory
,07-14 13:29:19.665  3707  3823 E SdpManagerService: onPackageRemoved :: Removed package detected... UserId : 0, Pkg : com.thaliproject.thalitest
07-14 13:29:19.665  3707  3783 E ActivityManager: Failure starting process com.thaliproject.thalitest
07-14 13:29:19.665  3707  3783 E ActivityManager: java.lang.SecurityException: Package com.thaliproject.thalitest is currently frozen!
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.pm.PackageManagerService.checkPackageStartable(PackageManagerService.java:4465)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:4656)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:4570)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:4428)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1783)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3132)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityUncheckedLocked(ActivityStack.java:2574)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeFocusedStackTopActivityLocked(ActivityStackSupervisor.java:2265)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeFocusedStackTopActivityLocked(ActivityStackSupervisor.java:2255)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6638)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:8145)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:7782)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:7914)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2309)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at android.os.Looper.loop(Looper.java:154)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-14 13:29:19.665  3707  3783 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-14 13:29:19.665  3707  3783 I ActivityManager: Force stopping com.thaliproject.thalitest appid=10033 user=0: start failure
,07-14 13:29:19.666  3707  3896 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
,07-14 13:29:19.666  3707  3783 I ActivityManager:   Force finishing activity ActivityRecord{785c0d0 u0 com.thaliproject.thalitest/.MainActivity t5}
07-14 13:29:19.666  3707  3783 W MultiScreenManagerService: moveTaskBackToDisplayIfNeeded(): root activity or app is null
07-14 13:29:19.667  3098  3126 D epmd    : Partition obj created
07-14 13:29:19.667  3098  3126 D epmd    : Partition::dump============== 0
07-14 13:29:19.667  3098  3126 D epmd    : Partition::mType > INTERNAL-SDCARD mSrcPath > /data/knox/secure_fs/enc_user mMntPath > /data/enc_user
07-14 13:29:19.667  3098  3126 D epmd    : Partition::SDP > not supported
07-14 13:29:19.668  3098  3126 D epmd    : Input srcpath - src: /data/enc_user/0/com.thaliproject.thalitest
07-14 13:29:19.668  3098  3126 D epmd    : Resolved srcpath - srcPath: /data/enc_user/0/com.thaliproject.thalitest
07-14 13:29:19.668  3098  3126 D epmd    : real path - rtStr: (null)
07-14 13:29:19.668  3098  3126 D epmd    : /data/enc_user/0/com.thaliproject.thalitest is absolute path Skipped..
07-14 13:29:19.668  3098  3126 E epmd    : Only canonical path can be handled..
07-14 13:29:19.668  3098  3126 E epmd    : removeEncPkgDir ERROR
07-14 13:29:19.668  3098  3126 D epmd    : deleting Partition object.
,07-14 13:29:19.669  3707  3825 D EnterprisePartitionManager: RCV <-
07-14 13:29:19.669  3707  3823 D AASAinstall: there is not AASApackages.xml file
07-14 13:29:19.670  3707  3896 D EnterprisePartitionManager: RMV <-
07-14 13:29:19.670  3707  3896 D EnterprisePartitionManager: event : 281 3 remove_enc_dir failed
,07-14 13:29:19.672  3098  3126 W FrameworkListener: Handler 'secure_fs' error (No such file or directory)
,07-14 13:29:19.674  3707  3896 E SdpManagerService: Can't find engine info [android_0]
07-14 13:29:19.674  3707  3783 I WindowManager: Failed to capture screenshot of Token{74a2f9 ActivityRecord{785c0d0 u0 com.thaliproject.thalitest/.MainActivity t5 f}} appWin=Window{4beb67cd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} drawState=4
,07-14 13:29:19.680  3707  3783 I ActivityManager:   Force finishing activity ActivityRecord{785c0d0 u0 com.thaliproject.thalitest/.MainActivity t5 f}
07-14 13:29:19.680  3707  3783 W ActivityManager: Duplicate finish request for ActivityRecord{785c0d0 u0 com.thaliproject.thalitest/.MainActivity t5 f}
,07-14 13:29:19.680  3707  3783 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=null next=ActivityRecord{f0c6fe3d0 u0 com.samsung.android.MtpApplication/.USBConnection t4} mFocusedStack=ActivityStack{c202c12d0 stackId=1, 2 tasks}
,07-14 13:29:19.683  3707  3743 V WindowManager: Relayout Window{3b39f10d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=4 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
,07-14 13:29:19.743  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-14 13:29:19.747  3707  3987 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ], android.os.BinderProxy@4cfbda1)
,07-14 13:29:19.747  3707  3937 D GraphicsStats: Buffer count: 5
07-14 13:29:19.747  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-14 13:29:19.747  3707  4718 I WindowManager: WIN DEATH: Window{4beb67cd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}
07-14 13:29:19.747  3707  3965 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ], android.os.BinderProxy@3c0fbc6)
07-14 13:29:19.748  3707  3958 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:29:19.748  3707  4718 I WindowManager: Destroying surface Surface(name=com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.removeLocked:1776 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:2876 com.android.server.wm.WindowManagerService.removeWindowLocked:2826 com.android.server.wm.WindowState$DeathRecipient.binderDied:2196 android.os.BinderProxy.sendDeathNotice:701 <bottom of call stack> 
07-14 13:29:19.748  3707  3799 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
07-14 13:29:19.748  3113  3120 I SurfaceFlinger: id=16 Removed NainActivit (3/4)
07-14 13:29:19.748  3707  3803 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.thaliproject.thalitest
07-14 13:29:19.748  3707  3803 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfoAsUser(ApplicationPackageManager.java:452)
07-14 13:29:19.748  3707  3803 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:434)
07-14 13:29:19.748  3707  3803 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:2974)
07-14 13:29:19.749  3707  3803 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2160)
07-14 13:29:19.749  3707  3803 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:3214)
07-14 13:29:19.749  3707  3803 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:9213)
07-14 13:29:19.749  3707  3803 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-14 13:29:19.749  3707  3803 W System.err: 	at android.os.Looper.loop(Looper.java:154)
07-14 13:29:19.749  3707  3803 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-14 13:29:19.749  3707  3803 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-14 13:29:19.749  3113  4411 I SurfaceFlinger: id=16 Removed NainActivit (-2/4)
07-14 13:29:19.749  3707  3958 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:29:19.750  3113  3283 I SurfaceFlinger: id=16 Removed NainActivit (-2/4)
07-14 13:29:19.750  3707  4718 D InputTransport: Input channel destroyed: fd=455
07-14 13:29:19.750  3707  3958 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:29:19.750  3707  3958 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-14 13:29:19.751  3707  4717 V WindowManager: Relayout Window{103c697d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=4 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
07-14 13:29:19.751  3707  3958 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:29:19.751  3707  3958 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-14 13:29:19.752  3707  3803 D WindowManager: addWindow: android.view.ViewRootImpl$W@70992dd displayId=0
,07-14 13:29:19.752  4818  4818 D Launcher: onRestart, Launcher: 43359398
07-14 13:29:19.753  3290  3290 W keystore: ENTER clear_uid from uid 1000 for 10033
07-14 13:29:19.753  3707  3803 D InputTransport: Input channel constructed: fd=455
07-14 13:29:19.753  3707  3803 D InputTransport: Input channel constructed: fd=465
07-14 13:29:19.753  3707  3823 I art     : Starting a blocking GC Explicit
,07-14 13:29:19.758  3707  3803 D ViewRootImpl@4c476b4[thalitest]: setView = DecorView@2fc4523[thalitest] touchMode=true
,07-14 13:29:19.760  3707  3783 D ActivityTrigger: ActivityTrigger activityPauseTrigger 
,07-14 13:29:19.760  3707  3783 D GameManagerService: sem_perfomance_mode: 0
07-14 13:29:19.761  3707  3783 D GameManagerService: sem_perfomance_mode: 0
07-14 13:29:19.761  3707  3707 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
07-14 13:29:19.761  3707  3707 D GameManagerService: unexpected mPrevNotiType: -1
,07-14 13:29:19.766  3707  3783 D InputTransport: Input channel destroyed: fd=455
,07-14 13:29:19.766  3707  3783 D InputDispatcher: Focused application released
07-14 13:29:19.766  3707  3783 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=null next=ActivityRecord{f0c6fe3d0 u0 com.samsung.android.MtpApplication/.USBConnection t4} mFocusedStack=ActivityStack{c202c12d0 stackId=1, 1 tasks}
07-14 13:29:19.766  3707  3783 I ActivityManager: Exiting empty application process 0:com.thaliproject.thalitest/u0a33 (null)
,07-14 13:29:19.766  3707  3783 D ActivityManager: cleanUpApplicationRecord -- 0
,07-14 13:29:19.772  4818  4818 D Launcher: onStart, Launcher: 43359398
07-14 13:29:19.772  4818  4818 D Launcher.HomeView: onStart
07-14 13:29:19.772  4818  4818 D MenuAppsGridFragment: onStart:true
,07-14 13:29:19.773  4615  4626 D ForegroundUtils: could not check pending caller
07-14 13:29:19.774  4615  4627 D ForegroundUtils: could not check pending caller
07-14 13:29:19.774  3707  5610 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
07-14 13:29:19.774  4615  4627 D ForegroundUtils: could not check pending caller
07-14 13:29:19.774  4615  4627 D ForegroundUtils: could not check pending caller
,07-14 13:29:19.775  4818  4818 D Launcher.MenuAppsGrid: ChangeMobileKeyboard:false mCurrentOrientation:1 mRequestedOrientation:1 newConfig.orientation:1 isShown:false
07-14 13:29:19.775  4818  4818 D Launcher.Workspace: changeOrientationIfRequired MobileKeyboardChanged : false   DisplayHeight : 1920  Density : 3.0   newConfig.orientation : 1
07-14 13:29:19.775  3707  3922 V WindowManager: Relayout Window{9cb5ca4d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=0 req=1015x1572 WM.LayoutParams{(0,0)(wrapxwrap) gr=#11 sim=#120 ty=2 fl=#1820002 fmt=-3 wanim=0x103038b surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
07-14 13:29:19.775  4818  4818 D Launcher.Workspace: ChangeMobileKeyboard:false mCurrentOrientation:1 mRequestedOrientation:1 newConfig.orientation:1 isShown:trueQuickViewWorkspace isOpened: false
07-14 13:29:19.780  4818  4818 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1029 330 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
07-14 13:29:19.780  4818  4818 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1029 x 330
07-14 13:29:19.780  4818  4818 D LauncherAppWidgetHostView: setResizeScaleResult() 1029/ 330 scaleToResize = 1.0(widget id = 3)
,07-14 13:29:19.781  5838  9149 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1027x1584]-format:1
,07-14 13:29:19.781  3707  3803 W WindowManager: Failed looking up window
07-14 13:29:19.781  3707  3803 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@70992dd does not exist
07-14 13:29:19.781  3707  3803 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:10302)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:10293)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at com.android.server.wm.WindowManagerService.relayoutWindow(WindowManagerService.java:3201)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at com.android.server.wm.Session.relayoutEx(Session.java:244)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at android.view.ViewRootImpl.relayoutWindow(ViewRootImpl.java:6384)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:2017)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1509)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:7051)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:927)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at android.view.Choreographer.doCallbacks(Choreographer.java:702)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at android.view.Choreographer.doFrame(Choreographer.java:638)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:913)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at android.os.Handler.handleCallback(Handler.java:751)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at android.os.Looper.loop(Looper.java:154)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-14 13:29:19.781  3707  3803 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-14 13:29:19.782  3707  4737 V WindowManager: Relayout Window{3b39f10d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=0 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
07-14 13:29:19.782  4818  4818 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 513 330 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
07-14 13:29:19.782  4818  4818 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 513 x 330
07-14 13:29:19.782  4818  4818 D LauncherAppWidgetHostView: setResizeScaleResult() 513/ 330 scaleToResize = 1.0(widget id = 2)
07-14 13:29:19.784  4818  4818 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1029 330 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
07-14 13:29:19.784  4818  4818 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1029 x 330
07-14 13:29:19.784  4818  4818 D LauncherAppWidgetHostView: setResizeScaleResult() 1029/ 330 scaleToResize = 1.0(widget id = 4)
,07-14 13:29:19.788  3707  4312 V WindowManager: Relayout Window{103c697d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=0 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
07-14 13:29:19.788  3707  3803 D ViewRootImpl@4c476b4[thalitest]: dispatchDetachedFromWindow
07-14 13:29:19.788  3113  3113 I SurfaceFlinger: id=18 createSurf (1080x1920),1 flag=4, MauncherAct
07-14 13:29:19.789  5838  9149 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1218x288]-format:1
,07-14 13:29:19.789  3707  4718 D ActivityManager: post active user change for 0 fullscreen false isHomeActivity() false
,07-14 13:29:19.794  3707  3803 W WindowManager: Failed looking up window
07-14 13:29:19.794  3707  3803 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@70992dd does not exist
07-14 13:29:19.794  3707  3803 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:10302)
07-14 13:29:19.794  3707  3803 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:10293)
07-14 13:29:19.794  3707  3803 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2632)
07-14 13:29:19.794  3707  3803 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:208)
07-14 13:29:19.794  3707  3803 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3676)
07-14 13:29:19.794  3707  3803 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:6583)
07-14 13:29:19.794  3707  3803 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:4082)
07-14 13:29:19.794  3707  3803 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-14 13:29:19.794  3707  3803 W WindowManager: 	at android.os.Looper.loop(Looper.java:154)
07-14 13:29:19.794  3707  3803 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-14 13:29:19.794  3707  3803 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,07-14 13:29:19.794  3707  5610 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
07-14 13:29:19.794  3707  3803 D InputTransport: Input channel destroyed: fd=465
07-14 13:29:19.794  3707  4718 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-14 13:29:19.794  3707  3707 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-14 13:29:19.795  3707  3803 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
07-14 13:29:19.795  3707  3707 I KnoxTimeoutHandler: Shared devices show user statefalse
07-14 13:29:19.795  3707  3707 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
07-14 13:29:19.795  3707  3707 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
07-14 13:29:19.795  3707  3783 D ActivityTrigger: ActivityTrigger activityStopTrigger 
,07-14 13:29:19.796  3707  3707 I KnoxTimeoutHandler: SD activityfalse
07-14 13:29:19.797  3707  5610 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,07-14 13:29:19.804  4818  5139 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1080x1920]-format:1
,07-14 13:29:19.806  4818  4818 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1029 330 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
07-14 13:29:19.806  4818  4818 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1029 x 330
,07-14 13:29:19.806  4818  4818 D LauncherAppWidgetHostView: setResizeScaleResult() 1029/ 330 scaleToResize = 1.0(widget id = 3)
07-14 13:29:19.807  4818  4818 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 513 330 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
,07-14 13:29:19.807  4818  4818 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 513 x 330
07-14 13:29:19.807  4818  4818 D LauncherAppWidgetHostView: setResizeScaleResult() 513/ 330 scaleToResize = 1.0(widget id = 2)
07-14 13:29:19.807  4818  4818 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1029 330 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
,07-14 13:29:19.808  4818  4818 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1029 x 330
07-14 13:29:19.808  4818  4818 D LauncherAppWidgetHostView: setResizeScaleResult() 1029/ 330 scaleToResize = 1.0(widget id = 4)
,07-14 13:29:19.809  3707  4716 D WindowManager: finishDrawingWindow: Window{9cb5ca4d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} mDrawState=HAS_DRAWN
,07-14 13:29:19.813  3707  3744 D WindowManager: finishDrawingWindow: Window{3b39f10d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} mDrawState=HAS_DRAWN
,07-14 13:29:19.831  3707  3937 D WindowManager: finishDrawingWindow: Window{103c697d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity} mDrawState=DRAW_PENDING
,07-14 13:29:19.837  3707  3803 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-14 13:29:19.837  3707  3707 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
,07-14 13:29:19.838  3707  3707 I KnoxTimeoutHandler: SD activityfalse
07-14 13:29:19.838  3707  3707 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
,07-14 13:29:19.839  3707  3783 D ActivityManager: mActivityResumeBoosterTail.acquire()
,07-14 13:29:19.839  3707  3803 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3707  tag : AMS_RESUME@CPU_MIN@7
07-14 13:29:19.839  3707  3803 D ActivityManager: mActivityResumeBooster.release()
,07-14 13:29:19.841  3707  3783 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3707  pkgName : AMS_RESUME_TAIL@CPU_MIN@13
,07-14 13:29:19.844  4818  4818 D MenuAppsGridFragment: onStop
07-14 13:29:19.844  4818  4818 D Launcher.HomeView: onStop
07-14 13:29:19.844  4818  4818 D capture : ----destroy
,07-14 13:29:19.889  3707  3823 I art     : Explicit concurrent mark sweep GC freed 217544(11MB) AllocSpace objects, 42(888KB) LOS objects, 28% free, 41MB/57MB, paused 1.333ms total 135.571ms
,07-14 13:29:19.898  4069  4069 E RecentsTaskLoader: Unexpected null component name or activity info: ComponentInfo{com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}, null
07-14 13:29:19.898  4069  4069 E RecentsTaskLoader: Unexpected null component name or activity info: ComponentInfo{com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}, null
,07-14 13:29:19.899  3707  3823 D AASAuninstall: userId = 0, info.removedAppID = 10033, info.uid = 10033, packageName = com.thaliproject.thalitest
07-14 13:29:19.899  4069  4069 E RecentsTaskLoader: Unexpected null component name or activity info: ComponentInfo{com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}, null
07-14 13:29:19.899  3707  3823 D AASAinstall: there is not AASApackages.xml file
,07-14 13:29:19.903  3707  3823 D PackageManager: result of delete: 1{109425773}
07-14 13:29:19.903  3707  3990 D MdnieScenarioControlService:  packageName : com.samsung.android.MtpApplication    className : com.samsung.android.MtpApplication.USBConnection
,07-14 13:29:19.904 10189 10189 I art     : System.exit called, status: 0
07-14 13:29:19.905 10189 10189 I AndroidRuntime: VM exiting with result code 0.
,07-14 13:29:19.905 10189 10197 W MessageQueue: Handler (android.os.Handler) {be84bb5} sending message to a Handler on a dead thread
07-14 13:29:19.905 10189 10197 W MessageQueue: java.lang.IllegalStateException: Handler (android.os.Handler) {be84bb5} sending message to a Handler on a dead thread
07-14 13:29:19.905 10189 10197 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-14 13:29:19.905 10189 10197 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:643)
07-14 13:29:19.905 10189 10197 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:612)
07-14 13:29:19.905 10189 10197 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:582)
07-14 13:29:19.905 10189 10197 W MessageQueue: 	at android.os.Handler.post(Handler.java:338)
07-14 13:29:19.905 10189 10197 W MessageQueue: 	at android.os.ResultReceiver$MyResultReceiver.send(ResultReceiver.java:57)
07-14 13:29:19.905 10189 10197 W MessageQueue: 	at com.android.internal.os.IResultReceiver$Stub.onTransact(IResultReceiver.java:58)
07-14 13:29:19.905 10189 10197 W MessageQueue: 	at android.os.Binder.execTransact(Binder.java:573)
07-14 13:29:19.905 10189 10189 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter
07-14 13:29:19.905 10189 10189 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter2
07-14 13:29:19.905 10189 10189 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - mSource2
07-14 13:29:19.905 10189 10189 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Exit
07-14 13:29:19.906  3707  3823 D MountService: getExternalStorageMountMode : 1
07-14 13:29:19.906  3707  3823 D MountService: getExternalStorageMountMode : 3
07-14 13:29:19.906  3707  3823 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10008, packageName : com.android.defcontainer
,07-14 13:29:19.919 10205 10205 E Zygote  : v2
07-14 13:29:19.919 10205 10205 I libpersona: KNOX_SDCARD checking this for 10008
07-14 13:29:19.919 10205 10205 I libpersona: KNOX_SDCARD not a persona
,07-14 13:29:19.919 10205 10205 E libpersona: scanKnoxPersonas
07-14 13:29:19.919  3707  3823 I ActivityManager: Start proc 10205:com.android.defcontainer/u0a8 for service com.android.defcontainer/.DefaultContainerService
07-14 13:29:19.919 10205 10205 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
07-14 13:29:19.920  3707  3823 I ActivityManager: Force stopping com.thaliproject.thalitest appid=10033 user=0: pkg removed
07-14 13:29:19.920 10205 10205 E Zygote  : accessInfo : 0
07-14 13:29:19.920 10205 10205 E libpersona: scanKnoxPersonas
07-14 13:29:19.920 10205 10205 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
07-14 13:29:19.920 10205 10205 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:29:19.921 10205 10205 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.defcontainer 
07-14 13:29:19.921  3707  3823 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=null next=ActivityRecord{f0c6fe3d0 u0 com.samsung.android.MtpApplication/.USBConnection t4} mFocusedStack=ActivityStack{c202c12d0 stackId=1, 1 tasks}
,07-14 13:29:19.929  3707  3707 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,07-14 13:29:19.940 10205 10205 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:29:19.940 10205 10205 D ActivityThread: Added TimaKeyStore provider
,07-14 13:29:19.955  3707  3883 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-14 13:29:19.955  4069  4069 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
07-14 13:29:19.956  4069  4069 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.thaliproject.thalitest
07-14 13:29:19.956  3707  3918 V NetworkPolicy: ACTION_PACKAGE_REMOVED for uid=10033
07-14 13:29:19.957  3707  3782 D AccessibilityManagerService: readMagniferWindowEnabledSettingLocked() magniferWindowEnabled = false/ userState.mIsMagniferWindowEnabled = false
07-14 13:29:19.960  4878  4878 V OMA_SmartcardService: TerminalStateChanged.
07-14 13:29:19.961  4878  4878 V OMA_SmartcardService: TerminalStateChanged/action:android.intent.action.PACKAGE_REMOVED, pkgName:com.thaliproject.thalitest
07-14 13:29:19.961  4878  4878 V OMA_SmartcardService: updateTerminals/action:android.intent.action.PACKAGE_REMOVED, pkgName:com.thaliproject.thalitest
07-14 13:29:19.962  4576  5053 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-14 13:29:19.971  3707  3917 V NetworkStats: removeUidsLocked() for UIDs [10033]
07-14 13:29:19.972  3707  3917 V NetworkStats: performPollLocked(flags=0x3)
07-14 13:29:19.972  3707  3917 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:29:19.977  3707  3783 D MountService: getExternalStorageMountMode : 1
07-14 13:29:19.977  3707  3783 D MountService: getExternalStorageMountMode : 3
07-14 13:29:19.977  3707  3783 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.bbc.bbcagent
,07-14 13:29:19.979  3707  3917 V NetworkStats: performPollLocked() took 7ms
07-14 13:29:19.979  3707  3917 D NtpTrustedTime: currentTimeMillis() cache hit
,07-14 13:29:19.982  4043  4043 D CarrierSvcBindHelper: No carrier app for: 0
,07-14 13:29:19.986  3707  3707 D SamsungAlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.thaliproject.thalitest
,07-14 13:29:19.989  3707  3707 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
,07-14 13:29:19.989  3707  3707 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED : replacingApp -false
07-14 13:29:19.989  3707  3707 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
07-14 13:29:19.989  3707  3707 D UcmService: Package update in userId-0 and uid-10033
07-14 13:29:19.990  3707  3707 D EnterpriseSCEPPolicy: Package actually removal
07-14 13:29:19.990  3707  3880 D UcmService: *****refreshAgentList userId-0 is called***
07-14 13:29:19.990  3707  3880 D UcmService: resolveAllowedAgents for user 0
07-14 13:29:19.990  3707  3880 D UcmService: found com.samsung.ucs.agent.boot
07-14 13:29:19.990  3707  3880 D UcmService: found com.samsung.ucs.agent.ese
07-14 13:29:19.990  3707  3880 D UcmService: resolveAllowedAgentsLegacy for user 0
07-14 13:29:19.990  3707  3880 D UcmService: found com.sec.smartcard.manager
07-14 13:29:19.990  3707  3707 D EnterpriseSCEPPolicy: mPriority = 0
07-14 13:29:19.990  3707  3880 D UcmService: mPersistentServices size is 0
07-14 13:29:19.990  3707  3880 D UcmService: -------Processing started for agentPackageName----- -com.samsung.ucs.agent.boot
07-14 13:29:19.990  3707  3880 D UcmService:   agentPackageName -com.samsung.ucs.agent.boot is an active plugin
07-14 13:29:19.990  3707  3880 D UcmService:   Check if caller has UCS Plugin permission...
07-14 13:29:19.990  3707  3880 D UcmService: enforcePermission : com.samsung.ucs.agent.boot
07-14 13:29:19.990  3707  3880 D UcmService: KNOX_UCM_PLUGIN_PERMISSION is granted
07-14 13:29:19.990  3707  3880 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
07-14 13:29:19.990  3707  3880 D UcmService:   agentPackageName com.samsung.ucs.agent.boot is system storage. Checking system signature
07-14 13:29:19.990  3707  3707 D EnterpriseSCEPPolicy: Package actually removal
07-14 13:29:19.990  3707  3707 D EnterpriseSCEPPolicy: mPriority = 0
07-14 13:29:19.990  3707  3707 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-14 13:29:19.991  3707  3880 D UcmService:   Signature match
07-14 13:29:19.991  3707  3880 D UcmService:   Valid system storage found is com.samsung.ucs.agent.boot
07-14 13:29:19.991  3707  3880 D UcmService: UCM ODE is not enabled
07-14 13:29:19.991  3707  3880 D UcmService: getKeyguardStorageForCurrentUser : 0
07-14 13:29:19.991  3707  3880 D UcmService: isFileExist : false
07-14 13:29:19.991  3707  3880 D UcmService: Do not need to bind boot plugin service
07-14 13:29:19.991  3707  3880 D UcmService: -------Processing started for agentPackageName----- -com.samsung.ucs.agent.ese
07-14 13:29:19.991  3707  3880 D UcmService:   agentPackageName -com.samsung.ucs.agent.ese is an active plugin
07-14 13:29:19.991  3707  3880 D UcmService:   Check if caller has UCS Plugin permission...
07-14 13:29:19.991  3707  3880 D UcmService: enforcePermission : com.samsung.ucs.agent.ese
07-14 13:29:19.991  3707  3783 I ActivityManager: Start proc 10220:com.samsung.android.bbc.bbcagent/1000 for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,07-14 13:29:19.992  3707  3880 D UcmService: KNOX_UCM_PLUGIN_PERMISSION is granted
07-14 13:29:19.992  3707  3880 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
07-14 13:29:19.992  3707  3880 D UcmService:   agentPackageName com.samsung.ucs.agent.ese is system storage. Checking system signature
07-14 13:29:19.993  3707  3707 D EnterpriseSSOPolicyService: inside mBReciever onReceive : android.intent.action.PACKAGE_REMOVED
07-14 13:29:19.993  3707  3707 D EnterpriseUserSpaceSSOPolicy: inside mBReciever onReceive : android.intent.action.PACKAGE_REMOVED
07-14 13:29:19.993  3707  3707 E SDAgentPackageStateReceiver: Not going to handle 'com.thaliproject.thalitest'!
07-14 13:29:19.993  3707  3707 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-14 13:29:19.993  3707  3707 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.thaliproject.thalitest uid = 10033 container id = 0
07-14 13:29:19.993 10220 10220 E Zygote  : v2
07-14 13:29:19.994 10220 10220 I libpersona: KNOX_SDCARD checking this for 1000
,07-14 13:29:19.994 10220 10220 I libpersona: KNOX_SDCARD not a persona
,07-14 13:29:19.993  3707  3880 D UcmService:   Signature match
07-14 13:29:19.994  3707  3880 D UcmService:   Valid system storage found is com.samsung.ucs.agent.ese
07-14 13:29:19.994  3707  3880 D UcmService: Do not need to bind eSE Service
07-14 13:29:19.994  3707  3880 D UcmService: mPersistentServices size is 0
07-14 13:29:19.994  3707  3880 D UcmService: -------Processing started for agentPackageName----- -com.sec.smartcard.manager
07-14 13:29:19.994  3707  3880 D UcmService:   agentPackageName -com.sec.smartcard.manager is an active plugin
07-14 13:29:19.994  3707  3880 D UcmService:   Check if caller has UCS Plugin permission...
07-14 13:29:19.994  3707  3880 D UcmService: enforcePermission : com.sec.smartcard.manager
07-14 13:29:19.994  3707  3880 D UcmService: KNOX_UCM_PLUGIN_PERMISSION_LEGACY is granted
07-14 13:29:19.994  3707  3880 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
07-14 13:29:19.994  3707  3880 D UcmService: PCSC Service doesn't exist. Ignore binidng to old Bai plugin...
07-14 13:29:19.994 10220 10220 E Zygote  : accessInfo : 0
07-14 13:29:19.995  3707  4675 I ActivityManager: DSS on for com.android.defcontainer and scale is 1.0
07-14 13:29:19.995 10220 10220 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
07-14 13:29:19.995  3707  3707 I OTPFW   : ProvisionData::getAllEntries Enter
07-14 13:29:19.996 10220 10220 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.bbc.bbcagent 
07-14 13:29:19.996  3707  3707 E OTPFW   : ProvisionData::getAllEntries Table is empty
07-14 13:29:19.996  3707  3707 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.intent.action.PACKAGE_REMOVED
07-14 13:29:19.996  3707  3707 D KnoxVpnEngineService: Vpn Receiver : android.intent.action.PACKAGE_REMOVED
07-14 13:29:19.996  3707  3707 D AudioService: com.thaliproject.thalitest(10033) is removed
,07-14 13:29:19.997  3707  3880 D UcmService: readPersistentServicesLocked is called...
07-14 13:29:19.997  3274  3459 D APM_AudioPolicyManager: soundkitchen_setvolume, uid:10033, volume:100
07-14 13:29:19.998  3707  3915 I KnoxVpnEngineService: vpn handle : Message received
07-14 13:29:19.998  3707  3915 D KnoxVpnEngineService: handleActionPackageRemoved
07-14 13:29:19.998  3274  3459 D APM::SoundKitchen: -----------------showForSoundKitchen start-----------------
07-14 13:29:19.998  3274  3459 D APM::SoundKitchen: -----------------showForSoundKitchen end------------------
07-14 13:29:19.998  3707  3915 D KnoxVpnEngineService: handleActionPackageRemoved : packageName = 0_com.thaliproject.thalitest : replacing = false
07-14 13:29:19.998  3274  3361 D AudioFlinger: setAppVolume() uid 10033, volume -1.000000
,07-14 13:29:20.001  3707  3914 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
07-14 13:29:20.001  3707  3914 D EnterprisePremiumVpnPolicyServiceV2: Package removal intent is reached
07-14 13:29:20.001  3707  3914 D EnterprisePremiumVpnPolicyServiceV2: handleActionPackageRemoved : packageName = com.thaliproject.thalitest : replacing = false
07-14 13:29:20.002  3707  3782 I AccessibilityManagerService: semIsAccessibilityServiceEnabled()
,07-14 13:29:20.002  3707  3782 I AccessibilityManagerService: accesibilityService is null
07-14 13:29:20.002  3707  4737 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4958, uid=10124 that is not exported from uid 10122
07-14 13:29:20.002  4615  4615 D RegisteredServicesCache: invalidateCache
07-14 13:29:20.003  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:29:20.003  3707  3918 D NtpTrustedTime: currentTimeMillis() cache hit
07-14 13:29:20.003  3707  3707 D GameManager.DatabaseHelper: removeGame(), packageName: com.thaliproject.thalitest, ret: 0
07-14 13:29:20.003  3707  3707 D GamePkgDataHelper: removeGamePkgData(). com.thaliproject.thalitest
,07-14 13:29:20.005  3707  3782 D EnterpriseDeviceManagerService: Package has changed for user 0
07-14 13:29:20.005  3707  3782 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-14 13:29:20.011 10220 10220 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:29:20.011 10220 10220 D ActivityThread: Added TimaKeyStore provider
07-14 13:29:20.011  3707  3707 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-14 13:29:20.011  3707  3707 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.thaliproject.thalitest flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-14 13:29:20.011  3707  3707 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.thaliproject.thalitest flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) } DATA= package:com.thaliproject.thalitest UID 1000 userId 0
07-14 13:29:20.011  3707  3707 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.thaliproject.thalitest
07-14 13:29:20.011  3707  4031 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_REMOVED
07-14 13:29:20.011  3707  4031 V EnterpriseBillingPolicyInternal: uID is 10033
07-14 13:29:20.011  3707  4031 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
07-14 13:29:20.011  3707  4031 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-14 13:29:20.011  3707  3707 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
07-14 13:29:20.012  3098  3126 D epmd    : Partition obj created
07-14 13:29:20.012  3098  3126 D epmd    : Partition::dump============== 0
07-14 13:29:20.012  3098  3126 D epmd    : Partition::mType > INTERNAL-SDCARD mSrcPath > /data/knox/secure_fs/enc_user mMntPath > /data/enc_user
07-14 13:29:20.012  3098  3126 D epmd    : Partition::SDP > not supported
07-14 13:29:20.012  3098  3126 D epmd    : Input srcpath - src: /data/enc_user/0/com.thaliproject.thalitest
07-14 13:29:20.012  3098  3126 D epmd    : Resolved srcpath - srcPath: /data/enc_user/0/com.thaliproject.thalitest
07-14 13:29:20.012  3707  4718 I ActivityManager: DSS on for com.samsung.android.bbc.bbcagent and scale is 1.0
07-14 13:29:20.012  3098  3126 D epmd    : real path - rtStr: (null)
07-14 13:29:20.012  3098  3126 D epmd    : /data/enc_user/0/com.thaliproject.thalitest is absolute path Skipped..
07-14 13:29:20.012  3098  3126 E epmd    : Only canonical path can be handled..
07-14 13:29:20.012  3098  3126 E epmd    : removeEncPkgDir ERROR
07-14 13:29:20.012  3707  4031 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-14 13:29:20.012  3098  3126 D epmd    : deleting Partition object.
07-14 13:29:20.012  3707  4031 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
07-14 13:29:20.012  3098  3126 W FrameworkListener: Handler 'secure_fs' error (No such file or directory)
07-14 13:29:20.013  3707  3825 D EnterprisePartitionManager: RCV <-
07-14 13:29:20.013  3707  3707 D EnterprisePartitionManager: RMV <-
07-14 13:29:20.013  3707  3707 D EnterprisePartitionManager: event : 281 4 remove_enc_dir failed
07-14 13:29:20.013  4615  4615 D ApduServiceInfo: seId: 0
07-14 13:29:20.014  3707  3707 E SdpManagerService: Can't find engine info [android_0]
07-14 13:29:20.015  4615  4615 D ApduServiceInfo: seId: 0
07-14 13:29:20.016  4615  4615 D RegisteredOthersCache: start invalidate
07-14 13:29:20.016  4615  4615 D RegisteredOthersCache: update valid otherService: ComponentInfo{com.google.android.apps.walletnfcrel/com.google.commerce.tapandpay.android.hce.service.ValuableApduService} AIDs: [4F53452E5641532E3031, A000000476D0000101, A000000476D0000111]
07-14 13:29:20.016  4615  4615 D RegisteredOthersCache: Existed other serivcee
07-14 13:29:20.016  4615  4615 D RegisteredPoliciesCache: invalidate
07-14 13:29:20.016  4615  4615 D RegisteredAidCache: onServicePolicyUpdated
07-14 13:29:20.016  4615  4615 D RegisteredAidCache: generateAidPolicyMapLocked
07-14 13:29:20.016  4615  4615 D AidPolicyManager: print policy
07-14 13:29:20.016  4615  4615 D AidPolicyManager: table size : 0
07-14 13:29:20.017  3707  3707 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.thaliproject.thalitest flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-14 13:29:20.017  3707  3707 V BackupManagerService: removePackageParticipantsLocked: uid=10033 #1
07-14 13:29:20.017  3707  3707 D EnterpriseSCEPPolicy: Package actually removal
07-14 13:29:20.017  3707  3707 D Ent,erpriseSCEPPolicy: mPriority = 0
07-14 13:29:20.018  3707  3707 D EnterpriseSCEPPolicy: Package actually removal
07-14 13:29:20.018  3707  3707 D EnterpriseSCEPPolicy: mPriority = 0
07-14 13:29:20.018  3707  3707 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-14 13:29:20.019  3707  3707 V AlarmManagerEXT: com.thaliproject.thalitest(10033) is removed.
07-14 13:29:20.019  3707  3707 D UniversalCredentialManagerService: ****MSG_CLEAN_INFO block started****
07-14 13:29:20.019  3707  3707 D UniversalCredentialManagerService: uid - 10033, userId-0
07-14 13:29:20.019  3707  3707 D UniversalCredentialManagerService: notifyChangeToPlugin is called for package uninstalled...
07-14 13:29:20.019  3707  3707 D UcmService: notifyChangeToPlugin event 12
07-14 13:29:20.019  3707  3707 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-14 13:29:20.019  3707  3707 D UniversalCredentialManagerService: ****MSG_CLEAN_INFO block ended****
07-14 13:29:20.019  3707  4031 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_FULLY_REMOVED
07-14 13:29:20.019  3707  4031 V EnterpriseBillingPolicyInternal: uID is 10033
07-14 13:29:20.019  3707  4031 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
07-14 13:29:20.019  3707  4031 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-14 13:29:20.020  3707  3800 D MountService: getExternalStorageMountMode : 1
07-14 13:29:20.021  3707  3800 D MountService: getExternalStorageMountMode : 3
07-14 13:29:20.021  3707  4031 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-14 13:29:20.021  3707  3800 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.lool
07-14 13:29:20.021  3707  4031 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
07-14 13:29:20.025 10205 10205 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-14 13:29:20.025  3707  3707 D AccessibilityManagerService: checkUniversalSwitchState start:
07-14 13:29:20.025  3707  3707 D AccessibilityManagerService: checkUniversalSwitchState universalSwitchEnabled:false
07-14 13:29:20.025  3707  3707 D AccessibilityManagerService: updateInputFilter universalSwitchState:false
07-14 13:29:20.025  3707  3707 D AccessibilityManagerService: updateInputFilter userState.mIsUniversalSwitchEnabled:false
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.026  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.027  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.027  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.027  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.027  4615  4615 D AidPolicyManager: There are not service policy for this aid
07-14 13:29:20.027  4615  4615 D AidRoutingManager: Override power table is not changed
07-14 13:29:20.034 10238 10238 E Zygote  : v2
07-14 13:29:20.034 10238 10238 I libpersona: KNOX_SDCARD checking this for 1000
07-14 13:29:20.034 10238 10238 I libpersona: KNOX_SDCARD not a persona
07-14 13:29:20.035 10238 10238 E Zygote  : accessInfo : 0
07-14 13:29:20.035 10238 10238 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
07-14 13:29:20.036 10238 10238 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.sm.provider 
07-14 13:29:20.036  3707  3800 I ActivityManager: Start proc 10238:com.samsung.android.sm.provider/1000 for content provider com.samsung.android.lool/com.samsung.android.sm.database.SmProvider
07-14 13:29:20.037  4615  4615 D RegisteredNfcFServicesCache: Service unchanged, not updating
07-14 13:29:20.040  4615  4615 D RegisteredComponentCache: Collect Tech packages for Knox
07-14 13:29:20.044 10220 10220 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm64
07-14 13:29:20.052 10238 10238 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:29:20.052 10238 10238 D ActivityThread: Added TimaKeyStore provider
07-14 13:29:20.053  3707  3908 I ActivityManager: DSS on for com.samsung.android.lool and scale is 1.0
,07-14 13:29:20.116 10220 10220 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:29:20.121 10220 10220 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.PackageEventReceiver.sendIntentToDDC:205 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.PackageEventReceiver.onReceive:57 
,07-14 13:29:20.122  3707  4677 I ActivityManager: KPU : put [com.samsung.android.scloud] : 21920 K
07-14 13:29:20.122  3707  4677 I ActivityManager: Killing 8826:com.samsung.android.scloud/5009 (adj 906): DHA:empty #33
,07-14 13:29:20.131  3707  4313 D MountService: getExternalStorageMountMode : 1
07-14 13:29:20.131  3707  4313 D MountService: getExternalStorageMountMode : 3
07-14 13:29:20.131  3707  4313 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.android.keychain
,07-14 13:29:20.135 10238 10238 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:29:20.136  3707  4716 W SELinuxMMAC: isContainerCreatedbyCaller returning false
,07-14 13:29:20.142  3707  3707 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3707  tag : AMS_RESUME_TAIL@CPU_MIN@13
,07-14 13:29:20.144 10253 10253 E Zygote  : v2
,07-14 13:29:20.145 10253 10253 I libpersona: KNOX_SDCARD checking this for 1000
07-14 13:29:20.145 10253 10253 I libpersona: KNOX_SDCARD not a persona
,07-14 13:29:20.145  3707  4313 I ActivityManager: Start proc 10253:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
07-14 13:29:20.145 10253 10253 E Zygote  : accessInfo : 0
07-14 13:29:20.145 10253 10253 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
07-14 13:29:20.146  3707  4679 D ActivityManager: cleanUpApplicationRecord -- 8826
07-14 13:29:20.146 10253 10253 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.android.keychain 
,07-14 13:29:20.149  4615  4627 D ForegroundUtils: could not check pending caller
,07-14 13:29:20.156  3707  4313 I ActivityManager: KPU : put [com.sec.android.app.clockpackage] : 21532 K
,07-14 13:29:20.156  3707  4313 I ActivityManager: Killing 9236:com.sec.android.app.clockpackage/u0a88 (adj 906): DHA:empty #33
,07-14 13:29:20.159 10253 10253 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:29:20.160 10253 10253 D ActivityThread: Added TimaKeyStore provider
,07-14 13:29:20.161  3707  4716 I ActivityManager: DSS on for com.android.keychain and scale is 1.0
,07-14 13:29:20.167  3707  3800 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer
07-14 13:29:20.167  3707  3800 V MARsDBManager: getManagedPackagesFromDB!
,07-14 13:29:20.175 10253 10253 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm64
07-14 13:29:20.175  3707  3800 V MARsPolicyManager: getPkgInfoFromSMToMARs size = 5
,07-14 13:29:20.184 10253 10253 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:29:20.187 10253 10253 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3306 
,07-14 13:29:20.192  3707  4716 D ActivityManager: cleanUpApplicationRecord -- 9236
,07-14 13:29:20.199  4615  4626 D ForegroundUtils: could not check pending caller
,07-14 13:29:20.199  4043  4043 D VvmPackageInstallReceiver: onReceive intent : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.thaliproject.thalitest flg=0x4000010 cmp=com.android.phone/.vvm.omtp.VvmPackageInstallReceiver launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-14 13:29:20.199  4043  4043 D VvmPackageInstallReceiver: intent getAction : android.intent.action.PACKAGE_REMOVED
07-14 13:29:20.199  4043  4043 D PhoneMultiSimUtils: getPhone: phoneId =0
07-14 13:29:20.199  4043  4043 D OmtpVvmCarrierConfigHelper: getCarrierConfig mSubId : -2
07-14 13:29:20.199  4043  4043 D OmtpVvmCarrierConfigHelper: getCarrierConfig SubscriptionManager.isValidSubscriptionId(mSubId) : false
07-14 13:29:20.200  4043  4043 W OmtpVvmCarrierConfigHelper: Invalid subscriptionId or subscriptionId not provided in intent.
07-14 13:29:20.200  4043  4043 D OmtpVvmCarrierConfigHelper: mCarrierConfig = null, mVvmType = null
,07-14 13:29:20.204  3707  3782 W SearchableInfo: Invalid searchable metadata for com.samsung.android.themestore/.activity.WTSearchActivity: Search label must be a resource reference.
,07-14 13:29:20.212  3707  3782 D UsbSettingsManager: clearDefaults: com.thaliproject.thalitest
07-14 13:29:20.213  3707  3782 I PrintManagerService: onPackageRemoved com.thaliproject.thalitest
,07-14 13:29:20.224 10238 10238 D SamsungAnalytics:1.8.22: cf feature is supported
,07-14 13:29:20.226  3707  4717 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gDDP@ADU
,07-14 13:29:20.226  3707  4718 I ActivityManager: KPU : put [com.sec.android.app.shealth] : 25908 K
07-14 13:29:20.226  3707  4718 I ActivityManager: Killing 7393:com.sec.android.app.shealth/u0a36 (adj 906): DHA:empty #33
07-14 13:29:20.226  3707  4717 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gDDP@ADU
07-14 13:29:20.228  3707  3782 I RemotePrintSpooler: pruneApprovedPrintServices
07-14 13:29:20.228  3707  3782 I RemotePrintSpooler: [user: 0] bindLocked() 
,07-14 13:29:20.228  3707  3782 I RemotePrintSpooler: bindLocked binding service java.lang.Object@80e8d6e
,07-14 13:29:20.229  3707  3782 D MountService: getExternalStorageMountMode : 1
07-14 13:29:20.229  3707  3782 D MountService: getExternalStorageMountMode : 3
07-14 13:29:20.229  3707  3782 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10138, packageName : com.android.printspooler
07-14 13:29:20.231  3707  4312 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gSDP@ADY
07-14 13:29:20.232  3707  4312 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gSDP@ADY
,07-14 13:29:20.239  3707  4675 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gDDP@ADc
,07-14 13:29:20.239  3707  4675 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gDDP@ADc
,07-14 13:29:20.245  3707  3744 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gSDP@ADg
07-14 13:29:20.245  3707  3744 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gSDP@ADg
,07-14 13:29:20.250 10272 10272 E Zygote  : v2
07-14 13:29:20.250 10272 10272 I libpersona: KNOX_SDCARD checking this for 10138
,07-14 13:29:20.250 10272 10272 I libpersona: KNOX_SDCARD not a persona
07-14 13:29:20.250 10272 10272 E Zygote  : accessInfo : 0
07-14 13:29:20.250 10272 10272 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
,07-14 13:29:20.251 10272 10272 I SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.printspooler 
07-14 13:29:20.254  3707  3782 I ActivityManager: Start proc 10272:com.android.printspooler/u0a138 for service com.android.printspooler/.model.PrintSpoolerService
,07-14 13:29:20.254  3707  3782 I RemotePrintSpooler: bindLocked waiting. remainingMillis: 8000
07-14 13:29:20.256  3707  4716 D ActivityManager: cleanUpApplicationRecord -- 7393
07-14 13:29:20.258 10238 10238 D SamsungAnalytics:1.8.22: [Tracker] Tracker start:1.8.22
07-14 13:29:20.260  3707  4718 D MountService: getExternalStorageMountMode : 3
07-14 13:29:20.260  3707  4718 D MountService: getExternalStorageMountMode : 3
07-14 13:29:20.260  3707  4718 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 10032, packageName : com.android.vending
,07-14 13:29:20.265  3707  4737 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gDDP@ADk
,07-14 13:29:20.265 10272 10272 D TimaKeyStoreProvider: TimaSignature is unavailable
07-14 13:29:20.265  3707  4737 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gDDP@ADk
07-14 13:29:20.265 10272 10272 D ActivityThread: Added TimaKeyStore provider
07-14 13:29:20.267  3707  3743 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gSDP@ADo
07-14 13:29:20.267  3707  3743 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gSDP@ADo
,07-14 13:29:20.272  3707  4717 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gDDP@ADs
,07-14 13:29:20.272  3707  4717 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gDDP@ADs
,07-14 13:29:20.274  3707  3987 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gSDP@ADw
,07-14 13:29:20.274  3707  3987 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gSDP@ADw
,07-14 13:29:20.277 10285 10285 E Zygote  : v2
07-14 13:29:20.277 10285 10285 I libpersona: KNOX_SDCARD checking this for 10032
07-14 13:29:20.277 10285 10285 I libpersona: KNOX_SDCARD not a persona
,07-14 13:29:20.277 10285 10285 E Zygote  : accessInfo : 0
,07-14 13:29:20.277 10285 10285 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[2],  Con:u:r:zygote:s0 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 -1 -1 0 1]
07-14 13:29:20.278  3707  4718 I ActivityManager: Start proc 10285:com.android.vending/u0a32 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
07-14 13:29:20.278 10285 10285 I SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.android.vending 
07-14 13:29:20.278  3707  3908 I ActivityManager: DSS on for com.android.printspooler and scale is 1.0
07-14 13:29:20.278  4615  4627 D ForegroundUtils: could not check pending caller
,07-14 13:29:20.292 10285 10285 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-14 13:29:20.292 10285 10285 D ActivityThread: Added TimaKeyStore provider
,07-14 13:29:20.294  3707  4313 I ActivityManager: DSS on for com.android.vending and scale is 1.0
,07-14 13:29:20.300 10272 10272 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-14 13:29:20.305 10272 10272 D PrintSpoolerService: No existing print spooler state.
,07-14 13:29:20.307  3707  3707 I RemotePrintSpooler: onServiceConnected
,07-14 13:29:20.307  3707  3782 I RemotePrintSpooler: [user: 0] pruneApprovedPrintServices()
,07-14 13:29:20.309  3707  3782 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,07-14 13:29:20.310  3707  3782 E PackageManager: Failed to write settings, restoring backup
07-14 13:29:20.310  3707  3782 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
07-14 13:29:20.310  3707  3782 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:135)
07-14 13:29:20.310  3707  3782 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
07-14 13:29:20.310  3707  3782 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:5491)
07-14 13:29:20.310  3707  3782 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
07-14 13:29:20.310  3707  3782 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:5825)
07-14 13:29:20.310  3707  3782 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-14 13:29:20.310  3707  3782 E PackageManager: 	at android.os.Looper.loop(Looper.java:154)
07-14 13:29:20.310  3707  3782 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: Can't write: system_server_wtf
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop20.tmp (Read-only file system)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at java.io.FileOutputStream.open(Native Method)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:221)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:169)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:248)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService$2.add(DropBoxManagerService.java:129)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:282)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$26.run(ActivityManagerService.java:17268)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:17275)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:17065)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:17037)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:751)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:154)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-14 13:29:20.312  3707  3783 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-14 13:29:20.312  4818  4818 D Launcher.Model: onPackageRemoved:com.thaliproject.thalitest user:UserHandle{0}
07-14 13:29:20.312  4818  4818 D Launcher.Model: isValidStateInKnoxMode:false user:UserHandle{0}
07-14 13:29:20.312  4818  4818 E Launcher.Model: onPackageRemoved :com.thaliproject.thalitest
07-14 13:29:20.313  4818  4933 D LauncherProvider: updateAppItems:1
07-14 13:29:20.313 10285 10285 I art     : Starting a blocking GC AddRemoveAppImageSpace
07-14 13:29:20.313  4818  4933 D LauncherProvider: appOrder delete item: 51
,07-14 13:29:20.314 10285 10285 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm64
07-14 13:29:20.314  4818  4933 E SQLiteLog: (10) unixWrite() /data/user/0/com.sec.android.app.launcher/databases/launcher.db fd (50) errno (30)
,--------- beginning of crash
07-14 13:29:20.317  4818  4933 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-14 13:29:20.317  4818  4933 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 4818
07-14 13:29:20.317  4818  4933 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: #################################################################
07-14 13:29:20.317  4818  4933 E AndroidRuntime: Error Code : 778 (SQLITE_IOERR_WRITE)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: Caused By : Disk I/O error occurred during 'write' operation.
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	(disk I/O error (code 778))
07-14 13:29:20.317  4818  4933 E AndroidRuntime: #################################################################
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:626)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:646)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at com.android.launcher2.LauncherProvider.updateAppItems(LauncherProvider.java:543)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$6.run(LauncherModel.java:887)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at com.android.launcher2.LauncherModel.updateAppItems(LauncherModel.java:891)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at com.android.launcher2.MenuAppLoader.removePackage(MenuAppLoader.java:927)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:4239)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:751)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:154)
07-14 13:29:20.317  4818  4933 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-14 13:29:20.320  3707  4679 D Debug   : !@DumpState : SHIP
07-14 13:29:20.320  3707  4679 D Debug   : !@DumpState : debug level:0x4f4c
,07-14 13:29:20.323  4497  4497 D io_stats: !@   8,0 r 25319 2278240 w 5257 207864 d 707 91944 f 2086 2085 iot 11440 10836 th 506548 0 0 pt 0 inp 9 0 241.438
,07-14 13:29:20.323  3707 10300 E DropBoxManagerService: Can't write: system_app_crash
07-14 13:29:20.323  3707 10300 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop279.tmp (Read-only file system)
07-14 13:29:20.323  3707 10300 E DropBoxManagerService: 	at java.io.FileOutputStream.open(Native Method)
07-14 13:29:20.323  3707 10300 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:221)
07-14 13:29:20.323  3707 10300 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:169)
07-14 13:29:20.323  3707 10300 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:248)
07-14 13:29:20.323  3707 10300 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService$2.add(DropBoxManagerService.java:129)
07-14 13:29:20.323  3707 10300 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:282)
07-14 13:29:20.323  3707 10300 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$26.run(ActivityManagerService.java:17268)
,07-14 13:29:20.344 10285 10285 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 

```
