#### Test 1322832571374948_thali04_samsung-SM-G930F Logs


```
--------- beginning of system
,07-26 17:26:58.042  3714  4938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-26 17:26:58.043  3714  4938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-26 17:26:58.043  3714  4938 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-26 17:26:58.043  3714  3714 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-26 17:26:58.048  3714  3714 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-26 17:26:58.048  3714  3714 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
07-26 17:26:58.050  3714  3714 D GameManagerService: new battery level: 100
--------- beginning of main
07-26 17:26:58.052  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-26 17:26:58.052  4068  4068 D KeyguardUpdateMonitor: handleBatteryUpdate
07-26 17:26:58.055  4068  4068 D PowerUI : priorPlugType = 2 mPlugType =  2
07-26 17:26:58.059  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
07-26 17:26:58.060  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
07-26 17:26:58.063  4056  4056 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-26 17:26:58.063  4056  4708 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-26 17:26:58.075  4068  4068 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
07-26 17:26:58.616  9878  9878 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 9878 | app_process
07-26 17:26:58.616  9878  9878 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
07-26 17:26:58.621  9878  9878 E appproc : Enhanced Zygote ASLR: ro.knox.enhance.zygote.aslr != 1. Enhanced Zygote ASLR is DISABLED!
07-26 17:26:58.621  9878  9878 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-26 17:26:58.624  9878  9878 D AndroidRuntime: CheckJNI is OFF
07-26 17:26:58.624  9878  9878 D AndroidRuntime: addProductProperty: start
07-26 17:26:58.663  9878  9878 I [saiv 1.1]: saiv_OnLoadJNI.cpp(38): _init: Version 1.1 Build # 3532
07-26 17:26:58.663  9878  9878 I [saiv 1.1]: saiv_OnLoadJNI.cpp(43): _init: _init() was called
07-26 17:26:58.678  9878  9878 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-26 17:26:58.678  9878  9878 I MLDAP   :            libMLDAP/MLDAP.c:  53:  MLDAP_LIB v1.1.15
07-26 17:26:58.678  9878  9878 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-26 17:26:58.722  9878  9878 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl
07-26 17:26:58.747  9878  9878 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-26 17:26:58.771  9878  9878 I Enhanced Zygote ASLR: DISABLED!
07-26 17:26:58.772  9878  9878 I Radio-JNI: register_android_hardware_Radio DONE
07-26 17:26:58.775  9878  9878 D ReflectionHelper: loadKlass() : caller=android.app.Activity.<clinit>:7525 <bottom of call stack> 
07-26 17:26:58.775  9878  9878 D ReflectionHelper: Reflecting method.....  class <onScreenChanged>
07-26 17:26:58.776  9878  9878 E SemAffinityControl: SemAffinityControl: registerfunction enter
07-26 17:26:58.784  9878  9878 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-26 17:26:58.802  3714  3918 I ActivityManager: START u0 {act=null typ=null flg=0x10000000 cmp=ComponentInfo{com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}} from uid 2000 on display 0
07-26 17:26:58.840  3714  3918 D ActivityManager: ActivityRecord() Constructor : multiScreenAttrs=MultiScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
07-26 17:26:58.842  3714  3918 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3714  pkgName : AMS_RESUME@CPU_MIN@7
07-26 17:26:58.845  3714  3918 D ActivityManager: mActivityResumeBooster.acquire()
07-26 17:26:58.847  3714  3918 I MultiWindowManagerService: setTaskDimensions: Task=TaskRecord{b912315d0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} minWidth=-1 minHeight=-1 maxWidth=-1 maxHeight=-1
07-26 17:26:58.847  3714  3918 D ActivityManager: moveToFront() : reason=startedActivity setFocusedActivity isAttached=true TaskRecord{b912315d0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1}
07-26 17:26:58.848  3714  3918 D InputDispatcher: Focused application set to: xxxx
07-26 17:26:58.848  3714  3918 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=TaskRecord{b912315d0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} next=ActivityRecord{a203a59d0 u0 com.thaliproject.thalitest/.MainActivity t5} mFocusedStack=ActivityStack{23fdc9bd0 stackId=1, 2 tasks}
07-26 17:26:58.849  3714  3918 D MountService: getExternalStorageMountMode : 1
07-26 17:26:58.849  3714  3918 D MountService: getExternalStorageMountMode : 3
07-26 17:26:58.849  3714  3918 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10033, packageName : com.thaliproject.thalitest
07-26 17:26:58.856  3714  3797 D WindowManager: addWindow: android.view.ViewRootImpl$W@c839fcd displayId=0
07-26 17:26:58.857  3714  3797 D InputTransport: Input channel constructed: fd=455
07-26 17:26:58.857  3714  3797 D InputTransport: Input channel constructed: fd=456
07-26 17:26:58.858  3714  3797 D ViewRootImpl@13be164[thalitest]: setView = DecorView@db3f393[thalitest] touchMode=true
07-26 17:26:58.865  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:26:58.865  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
07-26 17:26:58.868  3714  3797 V WindowManager: Relayout Window{449b082d0 u0 Starting com.thaliproject.thalitest}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
07-26 17:26:58.869  3113  3113 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, uhalitest
07-26 17:26:58.872  3714  3918 I ActivityManager: Start proc 9888:com.thaliproject.thalitest/u0a33 for activity com.thaliproject.thalitest/.MainActivity
07-26 17:26:58.872  9888  9888 E Zygote  : v2
07-26 17:26:58.872  9888  9888 I libpersona: KNOX_SDCARD checking this for 10033
07-26 17:26:58.872  9888  9888 I libpersona: KNOX_SDCARD not a persona
07-26 17:26:58.873  9888  9888 E Zygote  : accessInfo : 0
07-26 17:26:58.879  9888  9888 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-26 17:26:58.880  9888  9888 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
07-26 17:26:58.888  3714  3797 D WindowManager: finishDrawingWindow: Window{449b082d0 u0 Starting com.thaliproject.thalitest} mDrawState=DRAW_PENDING
07-26 17:26:58.888  9878  9878 D AndroidRuntime: Shutting down VM
07-26 17:26:58.900  9888  9888 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:26:58.901  9888  9888 D ActivityThread: Added TimaKeyStore provider
07-26 17:26:58.903  3714  3797 V WindowManager: Now policy hidden: Window{449b082d0 u0 Starting com.thaliproject.thalitest}
07-26 17:26:58.903  3714  4857 I ActivityManager: DSS on for com.thaliproject.thalitest and scale is 1.0
07-26 17:26:58.906  3714  4857 I WindowManager: Failed to capture screenshot of Token{ad8d011 ActivityRecord{54a5838d0 u0 com.samsung.android.MtpApplication/.USBConnection t4}} appWin=Window{67cdf81d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
07-26 17:26:58.914  9878  9878 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter
07-26 17:26:58.914  9878  9878 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter2
07-26 17:26:58.914  9878  9878 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - mSource2
07-26 17:26:58.914  9878  9878 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Exit
07-26 17:26:58.916  3714  4857 D GameManagerService: sem_perfomance_mode: 0
07-26 17:26:58.916  3714  3714 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-26 17:26:58.916  3714  3714 D GameManagerService: unexpected mPrevNotiType: -1
07-26 17:26:58.925  3714  4936 V WindowManager: Relayout Window{67cdf81d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=4 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
07-26 17:26:58.925  3714  4857 D ActivityTrigger: ActivityTrigger activityPauseTrigger 
07-26 17:26:58.925  3714  4857 D GameManagerService: sem_perfomance_mode: 0
07-26 17:26:58.927  4844  4856 D ForegroundUtils: could not check pending caller
07-26 17:26:58.927  4844  4856 D ForegroundUtils: could not check pending caller
07-26 17:26:58.928  4844  4856 D ForegroundUtils: could not check pending caller
07-26 17:26:58.928  3714  3738 V WindowManager: Relayout Window{ce6a2f4d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=4 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
07-26 17:26:58.929  3714  3738 I WindowManager: Destroying surface Surface(name=com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowManagerService.tryStartExitingAnimation:3504 com.android.server.wm.WindowManagerService.relayoutWindow:3360 com.android.server.wm.Session.relayoutEx:244 android.view.IWindowSession$Stub.onTransact:407 com.android.server.wm.Session.onTransact:151 
07-26 17:26:58.929  3113  4622 I SurfaceFlinger: id=12 Removed MauncherAct (1/5)
07-26 17:26:58.930  3113  3121 I SurfaceFlinger: id=12 Removed MauncherAct (-2/5)
07-26 17:26:58.933  5003  5003 D Launcher: onTrimMemory. Level: 20
,07-26 17:26:58.934  3714  5765 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
07-26 17:26:58.934  3714  5765 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-26 17:26:58.939  3714  4900 V WindowManager: Relayout Window{ce6a2f4d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=8 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
07-26 17:26:58.941  3714  3909 V WindowManager: Relayout Window{34ee05ad0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1015x1572 WM.LayoutParams{(0,0)(wrapxwrap) gr=#11 sim=#120 ty=2 fl=#1820002 fmt=-3 wanim=0x103038b surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
,07-26 17:26:58.942  3714  3797 D ViewRootImpl@13be164[thalitest]: MSG_RESIZED: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,07-26 17:26:58.943  3714  3794 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-26 17:26:58.946  3714  3739 V WindowManager: Relayout Window{67cdf81d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
,07-26 17:26:58.949  3714  3797 V WindowManager: Relayout Window{449b082d0 u0 Starting com.thaliproject.thalitest}: viewVisibility=0 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,07-26 17:26:58.954  3714  5765 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-26 17:26:58.956  3714  5765 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-26 17:26:58.958  3714  3797 D WindowManager: finishDrawingWindow: Window{449b082d0 u0 Starting com.thaliproject.thalitest} mDrawState=HAS_DRAWN
,07-26 17:26:58.976  9888  9888 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:26:59.000  9888  9888 I CordovaLog: Changing log level to DEBUG(3)
07-26 17:26:59.000  9888  9888 I CordovaActivity: Apache Cordova native platform version 6.1.2 is starting
07-26 17:26:59.001  9888  9888 D CordovaActivity: CordovaActivity.onCreate()
,07-26 17:26:59.013  9888  9888 W System  : ClassLoader referenced unknown path: /system/app/Chrome/lib/arm
,07-26 17:26:59.017  9888  9888 I WebViewFactory: Loading com.android.chrome version 56.0.2924.87 (code 292408752)
,07-26 17:26:59.066  3714  3991 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,07-26 17:26:59.069  9888  9888 I cr_LibraryLoader: Time to load native libraries: 16 ms (timestamps 7337-7353)
07-26 17:26:59.069  9888  9888 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-26 17:26:59.089  9888  9888 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-26 17:26:59.096  9888  9888 I chromium: [INFO:library_loader_hooks.cc(163)] Chromium logging enabled: level = 0, default verbosity = 0
,07-26 17:26:59.115  4649  4649 D io_stats: !@   8,0 r 25598 2234428 w 4852 201544 d 605 73548 f 1993 1993 iot 11470 10671 th 501828 0 0 pt 0 inp 0 0 267.399
07-26 17:26:59.117  9888  9888 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-26 17:26:59.256  3714  3909 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10033
,07-26 17:26:59.257  3714  3909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:921 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:26544 com.android.server.am.ActivityManagerService.registerReceiver:21403 android.app.ActivityManagerNative.onTransact:466 com.android.server.am.ActivityManagerService.onTransact:3573 
,07-26 17:26:59.260  3714  3714 D KnoxVpnEngineService: Vpn Receiver : com.samsung.android.knox.intent.action.VPN_PROXY_BROADCAST_INTERNAL
,07-26 17:26:59.260  3714  3916 I KnoxVpnEngineService: vpn handle : Message received
,07-26 17:26:59.291  9888  9888 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 9888
,07-26 17:26:59.293  3714  4541 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/9888 for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-26 17:26:59.294  3714  3959 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-26 17:26:59.294  3714  3959 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-26 17:26:59.294  3714  3959 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-26 17:26:59.294  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-26 17:26:59.294  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.294  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.294  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.294  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-26 17:26:59.294  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.294  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.295  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.295  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-26 17:26:59.295  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:26:59.295  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.295  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-26 17:26:59.338  9888  9888 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-26 17:26:59.347  9888  9888 D PluginManager: init()
,07-26 17:26:59.351  9888  9888 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,07-26 17:26:59.368  9888  9888 I cr_Ime  : ImeThread is enabled.
,07-26 17:26:59.381  9888  9888 D CordovaActivity: Started the activity.
,07-26 17:26:59.384  9888  9888 D CordovaActivity: Resumed the activity.
,07-26 17:26:59.406  3714  4857 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@db7502e displayId=0
,07-26 17:26:59.406  3714  4857 D InputTransport: Input channel constructed: fd=457
07-26 17:26:59.406  3714  4857 D InputTransport: Input channel constructed: fd=458
,07-26 17:26:59.408  3714  4857 D InputTransport: Input channel destroyed: fd=458
07-26 17:26:59.408  9888  9888 D InputTransport: Input channel constructed: fd=98
07-26 17:26:59.408  9888  9888 D ViewRootImpl@70889c2[MainActivity]: setView = DecorView@6a7f3d3[MainActivity] touchMode=true
,07-26 17:26:59.409  3714  4901 D ActivityManager: post active user change for 0 fullscreen true isHomeActivity() false
07-26 17:26:59.410  3714  4901 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
,07-26 17:26:59.410  3714  3714 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-26 17:26:59.411  3714  3714 I KnoxTimeoutHandler: Shared devices show user statefalse
07-26 17:26:59.411  9888  9888 D CordovaActivity: Paused the activity.
,07-26 17:26:59.414  3714  3763 D ActivityTrigger: ActivityTrigger activityStopTrigger 
,07-26 17:26:59.420  9888  9888 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 9888
,07-26 17:26:59.421  3714  4939 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/9888 for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-26 17:26:59.423  3714  3959 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-26 17:26:59.423  3714  3959 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-26 17:26:59.423  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.423  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.423  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.423  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-26 17:26:59.423  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.423  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:26:59.423  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.423  3714  3959 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-26 17:26:59.423  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-26 17:26:59.423  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 17:26:59.423  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:26:59.423  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:26:59.423  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:26:59.424  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:26:59.436  3714  4546 V WindowManager: Relayout Window{363a55cd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#110 ty=1 fl=#81810900 pfl=0x20000 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
07-26 17:26:59.437  3113  3113 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
07-26 17:26:59.459  9888  9935 I OpenGLRenderer: Initialized EGL, version 1.4
07-26 17:26:59.459  9888  9935 D OpenGLRenderer: Swap behavior 1
07-26 17:26:59.462  9888  9935 D libGLESv1: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,07-26 17:26:59.465  9888  9935 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1080x1920]-format:1
,07-26 17:26:59.465  9888  9888 D CordovaActivity: Stopped the activity.
,07-26 17:26:59.473  3714  3797 V WindowManager: Now policy hidden: Window{363a55cd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}
,07-26 17:26:59.476  9888  9940 E libEGL  : validate_display:99 error 3008 (EGL_BAD_DISPLAY)
,07-26 17:26:59.490  9888  9940 W AudioCapabilities: Unsupported mime audio/mpeg-L1
07-26 17:26:59.491  9888  9940 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-26 17:26:59.492  9888  9940 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-26 17:26:59.492  9888  9940 W AudioCapabilities: Unsupported mime audio/x-ima
,07-26 17:26:59.494  9888  9940 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-26 17:26:59.494  9888  9940 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-26 17:26:59.494  9888  9940 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.497  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.499  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 17:26:59.506  9888  9940 W VideoCapabilities: Unsupported mime video/wvc1
07-26 17:26:59.507  9888  9940 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-26 17:26:59.512  9888  9940 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-26 17:26:59.512  9888  9940 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-26 17:26:59.512  9888  9940 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-26 17:26:59.514  9888  9940 W VideoCapabilities: Unsupported mime video/wvc1
07-26 17:26:59.515  9888  9940 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-26 17:26:59.517  9888  9940 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
07-26 17:26:59.517  3714  4901 D WindowManager: finishDrawingWindow: Window{363a55cd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=DRAW_PENDING
07-26 17:26:59.518  9888  9888 D ViewRootImpl@70889c2[MainActivity]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-26 17:26:59.520  9888  9940 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
07-26 17:26:59.523  9888  9940 W VideoCapabilities: Unsupported mime video/mp43
07-26 17:26:59.523  3714  4939 D WindowManager: finishDrawingWindow: Window{363a55cd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=HAS_DRAWN
07-26 17:26:59.524  9888  9888 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
07-26 17:26:59.524  3714  3797 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
07-26 17:26:59.524  3714  3714 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
07-26 17:26:59.525  3714  3797 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +599ms (total +676ms)
07-26 17:26:59.525  3714  3714 I KnoxTimeoutHandler: SD activityfalse
07-26 17:26:59.525  3714  3714 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
07-26 17:26:59.525  3714  3763 D ActivityManager: mActivityResumeBoosterTail.acquire()
07-26 17:26:59.526  3714  3797 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3714  tag : AMS_RESUME@CPU_MIN@7
07-26 17:26:59.526  3714  3797 D ActivityManager: mActivityResumeBooster.release()
07-26 17:26:59.528  3714  3797 D ViewRootImpl@13be164[thalitest]: dispatchDetachedFromWindow
07-26 17:26:59.529  3714  3797 I WindowManager: Destroying surface Surface(name=Starting com.thaliproject.thalitest) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.removeLocked:1776 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:2876 com.android.server.wm.WindowManagerService.removeWindowLocked:2826 com.android.server.wm.WindowManagerService.removeWindowLocked:2641 com.android.server.wm.WindowManagerService.removeWindow:2636 com.android.server.wm.Session.remove:208 
07-26 17:26:59.529  3113  4622 I SurfaceFlinger: id=15 Removed uhalitest (3/5)
07-26 17:26:59.529  3113  3121 I SurfaceFlinger: id=15 Removed uhalitest (-2/5)
07-26 17:26:59.530  3714  3763 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3714  pkgName : AMS_RESUME_TAIL@CPU_MIN@13
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  9888  9940 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 17:26:59.532  3714  3797 D InputTransport: Input channel destroyed: fd=455
07-26 17:26:59.533  3714  3797 D InputTransport: Input channel destroyed: fd=456
,07-26 17:26:59.535  9888  9940 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-26 17:26:59.536  9888  9940 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-26 17:26:59.536  9888  9940 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-26 17:26:59.550  9888  9940 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-26 17:26:59.562  9888  9940 W VideoCapabilities: Unsupported mime video/sorenson
,07-26 17:26:59.578  9888  9940 D libGLESv2: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,07-26 17:26:59.599  9888  9888 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9888
,07-26 17:26:59.734  9888  9888 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,07-26 17:26:59.746  9888  9888 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,07-26 17:26:59.785  9888  9948 D jxcore_app_log: JniHelper::setJavaVM(0xee234000), pthread_self() = -948963040
,07-26 17:26:59.788  9888  9948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-26 17:26:59.788  9888  9948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-26 17:26:59.788  9888  9948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-26 17:26:59.788  9888  9948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-26 17:26:59.788  9888  9948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-26 17:26:59.788  9888  9948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cec9c7d added. We now have 1 listener(s)
,07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cec9c7d added. We now have 1 listener(s)
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-26 17:26:59.789  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-26 17:26:59.794  9888  9948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
07-26 17:26:59.794  9888  9948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
07-26 17:26:59.795  9888  9948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 17:26:59.795  9888  9948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
07-26 17:26:59.796  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 17:26:59.796  9888  9948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6439840 added. We now have 2 listener(s)
07-26 17:26:59.796  9888  9948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 17:26:59.801  9888  9948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 17:26:59.801  9888  9948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 64731
,07-26 17:26:59.802  9888  9948 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 120
07-26 17:26:59.802  9888  9948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
07-26 17:26:59.802  9888  9948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
07-26 17:26:59.802  9888  9948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
07-26 17:26:59.802  9888  9948 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 120
,07-26 17:26:59.805  9888  9948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 17:26:59.805  9888  9948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,07-26 17:26:59.809  9888  9948 D BluetoothAdapter: STATE_ON
,07-26 17:26:59.810  9888  9948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,07-26 17:26:59.810  9888  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 17:26:59.810  9888  9948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:26:59.810  9888  9948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:26:59.810  9888  9948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:26:59.810  9888  9948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:26:59.810  9888  9948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-26 17:26:59.810  9888  9948 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-26 17:26:59.810  9888  9948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 17:26:59.810  9888  9948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 17:26:59.810  9888  9948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-26 17:26:59.810  9888  9948 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 17:26:59.810  9888  9948 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-26 17:26:59.813  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:26:59.817  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:26:59.820  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:26:59.820  9888  9888 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
07-26 17:26:59.821  9888  9888 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,07-26 17:26:59.832  3714  3714 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3714  tag : AMS_RESUME_TAIL@CPU_MIN@13
,07-26 17:26:59.999  3714  3864 D SamsungAlarmManager: Expired : 8
,07-26 17:27:00.000  3714  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{1446819 type 3 when 268284 android}
,07-26 17:27:00.007  3714  3714 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170726T172800 - CU:1000/CP:3714
,07-26 17:27:00.010  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-26 17:27:00.010  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-26 17:27:00.010  4068  4068 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-26 17:27:00.017  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#end
,07-26 17:27:00.030  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-26 17:27:00.032  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-26 17:27:00.044  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-26 17:27:00.045  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:27:00.047  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-26 17:27:00.049  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:27:00.065  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-26 17:27:00.066  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:27:00.067  4068  4068 V hong    : mid yDiff = 438
,07-26 17:27:00.067  4068  4068 V hong    : mid yDiff = 438
07-26 17:27:00.068  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-26 17:27:00.068  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-26 17:27:00.071  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-26 17:27:00.073  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:27:00.081  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-26 17:27:00.082  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:27:00.097  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-26 17:27:00.100  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-26 17:27:00.105  5128  5128 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
07-26 17:27:00.107  5128  5128 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
07-26 17:27:00.109  5128  5128 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-26 17:27:00.116  5128  5128 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-26 17:27:00.117  5128  5128 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-26 17:27:00.118  5128  5128 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-26 17:27:00.119  5128  5128 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
07-26 17:27:00.120  5128  5128 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
07-26 17:27:00.123  5128  5128 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-26 17:27:00.124  5128  5128 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C5B5B7C29AF99E6CE15828BE2E6B309417ABACD1A222E15429C769D443D0956CEA16EAD06E076301B8F3A346EA27BBE75]}
,07-26 17:27:00.125  5128  5128 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-26 17:27:00.447  9888  9951 W jxcore-log: Initializing JXcore engine
07-26 17:27:00.447  9888  9951 W jxcore-log: JXcore engine is ready
,07-26 17:27:00.466  3244  3244 E audit   : type=1400 audit(1501082820.445:534): avc:  denied  { ioctl } for  pid=9951 comm="Thread-9" path="socket:[65062]" dev="sockfs" ino=65062 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0 SEPF_SECMOBILE_7.0_0006
,07-26 17:27:00.466  3714  3793 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / /system/bin/sh /system/bin/install-recovery.sh
07-26 17:27:00.466  3244  3244 E audit   : type=1300 audit(1501082820.445:534): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3 a1=5451 a2=dc823982 a3=21 items=0 ppid=3272 pid=9951 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-26 17:27:00.466  3714  3793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,07-26 17:27:00.469  3714  3793 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
07-26 17:27:00.469  3244  3244 E audit   : type=1327 audit(1501082820.445:534): proctitle="com.thaliproject.thalitest"
07-26 17:27:00.469  3244  3244 E audit   : type=1320 audit(1501082820.445:534): 
07-26 17:27:00.469  3714  3763 D MountService: getExternalStorageMountMode : 1
07-26 17:27:00.469  3714  3763 D MountService: getExternalStorageMountMode : 3
07-26 17:27:00.469  3714  3763 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.securitylogagent
07-26 17:27:00.469  3244  3244 E audit   : type=1400 audit(1501082820.445:535): avc:  denied  { ioctl } for  pid=9951 comm="Thread-9" path="/dev/pmsg0" dev="tmpfs" ino=2874 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0 SEPF_SECMOBILE_7.0_0006
07-26 17:27:00.470  3244  3244 E audit   : type=1300 audit(1501082820.445:535): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=4 a1=5451 a2=dc823982 a3=21 items=0 ppid=3272 pid=9951 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
,07-26 17:27:00.471  3244  3244 E audit   : type=1327 audit(1501082820.445:535): proctitle="com.thaliproject.thalitest"
,07-26 17:27:00.471  3244  3244 E audit   : type=1320 audit(1501082820.445:535): 
07-26 17:27:00.471  3714  3793 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / "com.thaliproject.thalitest"
,07-26 17:27:00.472  3244  3244 E audit   : type=1400 audit(1501082820.445:536): avc:  denied  { ioctl } for  pid=9951 comm="Thread-9" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3106 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs_trace_marker:s0 tclass=file permissive=0 SEPF_SECMOBILE_7.0_0006
07-26 17:27:00.472  9888  9951 W jxcore-log: Starting JXcore engine
07-26 17:27:00.472  3244  3244 E audit   : type=1300 audit(1501082820.445:536): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=5 a1=5451 a2=dc823982 a3=21 items=0 ppid=3272 pid=9951 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-26 17:27:00.472  3714  3793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-26 17:27:00.473  3244  3244 E audit   : type=1327 audit(1501082820.445:536): proctitle="com.thaliproject.thalitest"
07-26 17:27:00.473  3244  3244 E audit   : type=1320 audit(1501082820.445:536): 
07-26 17:27:00.474  3244  3244 E audit   : type=1400 audit(1501082820.445:537): avc:  denied  { ioctl } for  pid=9951 comm="Thread-9" path="socket:[65098]" dev="sockfs" ino=65098 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0 SEPF_SECMOBILE_7.0_0006
07-26 17:27:00.474  3244  3244 E audit   : type=1300 audit(1501082820.445:537): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=54 a1=5451 a2=dc823982 a3=21 items=0 ppid=3272 pid=9951 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-26 17:27:00.475  3244  3244 E audit   : type=1327 audit(1501082820.445:537): proctitle="com.thaliproject.thalitest"
07-26 17:27:00.475  3244  3244 E audit   : type=1320 audit(1501082820.445:537): 
,07-26 17:27:00.486  9953  9953 E Zygote  : v2
07-26 17:27:00.486  9953  9953 I libpersona: KNOX_SDCARD checking this for 1000
07-26 17:27:00.486  9953  9953 I libpersona: KNOX_SDCARD not a persona
07-26 17:27:00.487  9953  9953 E Zygote  : accessInfo : 0
,07-26 17:27:00.490  9953  9953 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:00.491  9953  9953 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.securitylogagent 
,07-26 17:27:00.496  3714  3763 I ActivityManager: Start proc 9953:com.samsung.android.securitylogagent/1000 for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,07-26 17:27:00.497  3714  3793 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-26 17:27:00.505  9953  9953 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:00.505  9953  9953 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:00.507  3714  4541 I ActivityManager: DSS on for com.samsung.android.securitylogagent and scale is 1.0
07-26 17:27:00.509  9888  9951 W jxcore-log: Platform android
07-26 17:27:00.509  9888  9951 W jxcore-log: 
,07-26 17:27:00.509  9888  9951 W jxcore-log: Process ARCH arm
07-26 17:27:00.509  9888  9951 W jxcore-log: 
,07-26 17:27:00.522  9953  9953 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,07-26 17:27:00.531  9953  9953 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:00.534  9953  9953 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-26 17:27:00.539  9953  9953 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-26 17:27:00.636  9888  9951 I jxcore-log: JXcore Cordova bridge is ready!
07-26 17:27:00.636  9888  9951 I jxcore-log: 
07-26 17:27:00.636  9888  9951 W jxcore-log: JXcore engine is started
,07-26 17:27:00.644  9888  9948 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-26 17:27:00.652  9888  9888 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
07-26 17:27:00.652  9888  9888 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-26 17:27:01.886  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:01.886  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:27:04.119  4649  4649 D io_stats: !@   8,0 r 25929 2277584 w 4903 202280 d 612 73576 f 2006 2006 iot 11640 10826 th 472800 0 0 pt 0 inp 0 0 272.402
,07-26 17:27:04.855  3714  5765 D SSRM:f  : SIOP:: AP = 340, PST = 287 (W:6), CP = 248, CUR = -111, LCD = 57
,07-26 17:27:04.911  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:04.911  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:27:04.934  3714  5765 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-26 17:27:07.774  9888  9951 I jxcore-log: 2017-07-26 15:27:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
07-26 17:27:07.774  9888  9951 I jxcore-log: 
,07-26 17:27:07.776  9888  9951 I jxcore-log: 2017-07-26 15:27:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
07-26 17:27:07.776  9888  9951 I jxcore-log: 
07-26 17:27:07.776  9888  9951 I jxcore-log: 2017-07-26 15:27:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
07-26 17:27:07.776  9888  9951 I jxcore-log: 
,07-26 17:27:07.786  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:07.791  9888  9951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 17:27:07.791  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:07.791  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:07.791  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:27:07.791  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:27:07.791  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-26 17:27:07.791  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-26 17:27:07.791  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 17:27:07.791  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 17:27:07.794  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:07.798  9888  9951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-26 17:27:07.799  9888  9951 I jxcore-log: 2017-07-26 15:27:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
07-26 17:27:07.799  9888  9951 I jxcore-log: 
07-26 17:27:07.800  9888  9951 I jxcore-log: 2017-07-26 15:27:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
07-26 17:27:07.800  9888  9951 I jxcore-log: 
,07-26 17:27:07.800  9888  9951 I jxcore-log: 2017-07-26 15:27:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
07-26 17:27:07.800  9888  9951 I jxcore-log: 
,07-26 17:27:07.934  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:07.934  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:27:08.073  9888  9951 D ExecuteNativeTests: Running unit tests
07-26 17:27:08.073  9888  9951 D BluetoothAdapter: enable()
,07-26 17:27:08.079  4056  4069 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-26 17:27:08.080  4056  4069 D AdapterProvider: query
,07-26 17:27:08.097  4056  4069 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@ca163c9
,07-26 17:27:08.099  4056  4069 D BluetoothAdapterService: updateEvent - already set, update
,07-26 17:27:08.100  4056  4069 W BluetoothAdapterService: updateEvent - alreadySet is true
07-26 17:27:08.100  4056  4069 D AdapterProvider: update
,07-26 17:27:08.108  4056  4069 E BluetoothAdapterService: updateEvent - update success 1
,07-26 17:27:08.113  9888  9951 D BluetoothAdapter: enable(): BT is already enabled..!
,07-26 17:27:08.126  3714  4901 D WifiService: setWifiEnabled: true pid=9888, uid=10033
07-26 17:27:08.127  3714  4901 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-26 17:27:08.128  3714  4901 D WifiControlHistoryProvider: query
,07-26 17:27:08.159  3714  4901 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-26 17:27:08.161  3714  4901 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:08.163  3714  4901 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-26 17:27:08.171  3714  4901 I WifiService: Wi-Fi Sharing settings has not been accessed
07-26 17:27:08.172  3714  4901 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-26 17:27:08.902  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-26 17:27:08.929  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-26 17:27:08.929  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-26 17:27:09.124  4649  4649 D io_stats: !@   8,0 r 25939 2278024 w 4931 202592 d 612 73576 f 2009 2009 iot 11660 10838 th 471656 0 0 pt 0 inp 0 0 277.407
,07-26 17:27:10.968  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:10.968  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:27:14.002  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:14.002  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:27:14.879  3714  5765 D SSRM:f  : SIOP:: AP = 320, PST = 296 (W:14), CP = 259, CUR = -87, LCD = 57
,07-26 17:27:15.402  3714  3714 D UsbMonitorService: readUsbState++
,07-26 17:27:15.403  3714  3714 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-26 17:27:15.405  3714  3714 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-26 17:27:15.406  3714  3714 D UsbMonitorService: Posting Message again
,07-26 17:27:17.029  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:17.029  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:27:17.487  3714  4446 E Watchdog: !@Sync 9 [26_lip_17_27_17.487]
,07-26 17:27:18.180  9888  9951 I com.test.thalitest.ThaliTestRunner: Running UT
,07-26 17:27:18.307  9888  9951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 17:27:18.307  9888  9951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3daa211 added. We now have 2 listener(s)
07-26 17:27:18.307  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3daa211 added. We now have 3 listener(s)
07-26 17:27:18.307  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 17:27:18.308  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
07-26 17:27:18.308  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 17:27:18.308  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
07-26 17:27:18.309  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 17:27:18.309  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9e5f76 added. We now have 4 listener(s)
07-26 17:27:18.309  9888  9951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 17:27:18.310  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 17:27:18.320  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:18.328  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
07-26 17:27:18.328  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 17:27:18.328  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 17:27:18.329  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-26 17:27:18.329  9888  9951 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
07-26 17:27:18.329  9888  9951 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-26 17:27:18.329  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 17:27:18.330  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 17:27:18.330  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 17:27:18.330  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,07-26 17:27:18.331  9888  9951 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-26 17:27:18.332  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,07-26 17:27:18.334  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
07-26 17:27:18.335  9888  9951 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,07-26 17:27:18.339  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 17:27:18.355  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:18.362  9888  9951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 17:27:18.362  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:18.362  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:18.362  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:27:18.362  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:27:18.362  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-26 17:27:18.362  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-26 17:27:18.362  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 17:27:18.362  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 17:27:18.362  9888  9951 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 17:27:18.362  9888  9951 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
07-26 17:27:18.362  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
07-26 17:27:18.362  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-26 17:27:18.364  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:18.364  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:18.364  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:18.364  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-26 17:27:18.365  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:18.365  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:18.366  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:18.366  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-26 17:27:18.366  9888  9951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-26 17:27:18.366  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-26 17:27:18.366  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 17:27:18.371  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-26 17:27:18.372  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-26 17:27:18.372  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-26 17:27:18.372  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-26 17:27:18.373  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-26 17:27:18.373  9888  9968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-26 17:27:18.373  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-26 17:27:18.373  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 17:27:18.373  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 17:27:18.375  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 17:27:18.381  9888  9968 D BluetoothSocket: bindListen(): myUserId = 0
07-26 17:27:18.381  9888  9968 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 17:27:18.387  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:18.390  9888  9968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,07-26 17:27:18.393  9888  9968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@8b64e4d, port: 6, type: 1, local socket address: null, socket type: 0
,07-26 17:27:18.394  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-26 17:27:18.394  9888  9951 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 17:27:18.394  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 17:27:18.395  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 17:27:18.395  9888  9888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-26 17:27:18.400  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:18.401  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:18.402  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:18.405  9888  9951 D BluetoothAdapter: isSecureModeEnabled
07-26 17:27:18.405  4056  4067 D BtConfig.SecureMode: isSecureModeOn:false
07-26 17:27:18.407  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:18.407  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 17:27:18.410  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:18.411  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:18.412  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 17:27:18.412  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 17:27:18.412  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,07-26 17:27:18.415  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:18.419  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:18.420  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:18.420  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-26 17:27:18.420  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,07-26 17:27:18.421  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "35d3e8aa-16e9-4ee5-85be-d6766e758699", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-26 17:27:18.421  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 4A 3E
,07-26 17:27:18.423  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:18.423  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-26 17:27:18.424  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:18.425  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:18.425  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,07-26 17:27:18.426  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:18.426  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:18.427  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:18.428  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:18.429  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:18.431  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:18.431  9888  9951 D BluetoothAdapter: isSecureModeEnabled
07-26 17:27:18.431  4056  4709 D BtConfig.SecureMode: isSecureModeOn:false
,07-26 17:27:18.432  9888  9951 D BluetoothLeAdvertiser: start advertising
,07-26 17:27:18.433  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:18.444  4056  4067 D BtGatt.GattService: registerClient() - UUID=a8f54cee-8ca2-4034-bc59-e2a98a0370cc
,07-26 17:27:18.548  4056  4174 D BtGatt.GattService: onClientRegistered() - UUID=a8f54cee-8ca2-4034-bc59-e2a98a0370cc, clientIf=5, status=0
,07-26 17:27:18.550  9888  9899 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-26 17:27:18.555  4056  4710 E BtGatt.ContextMap: Context not found for ID 5
,07-26 17:27:18.556  4056  4585 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-26 17:27:18.557  4056  4571 D BtGatt.AdvertiseManager: message : 0
,07-26 17:27:18.559  4056  4571 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-26 17:27:18.559  4056  4571 D BtGatt.AdvertiseManager: size of list is =0
,07-26 17:27:18.568  4056  4571 D BtGatt.AdvertiseManager: starting advertising
,07-26 17:27:18.574  4056  4571 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-26 17:27:18.579  4056  4638 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-26 17:27:18.597  4056  4174 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-26 17:27:18.602  4056  4571 D BtGatt.AdvertiseManager: starting multi advertising
,07-26 17:27:18.613  4056  4174 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
07-26 17:27:18.614  4056  4571 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,07-26 17:27:18.614  4056  4571 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-26 17:27:18.614  4056  4571 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
,07-26 17:27:18.615  4056  4571 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
07-26 17:27:18.617  9888  9900 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-26 17:27:18.619  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:18.620  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:18.620  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-26 17:27:18.622  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:18.624  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:18.625  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:18.626  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:18.628  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:18.628  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-26 17:27:18.632  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-26 17:27:18.633  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:18.639  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:18.640  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:18.641  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:18.642  9888  9951 I io.jxcore.node.ConnectionHelper: start: OK
07-26 17:27:18.643  9888  9888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-26 17:27:18.645  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-26 17:27:18.646  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:18.647  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-26 17:27:18.649  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,07-26 17:27:18.651  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-26 17:27:18.652  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-26 17:27:18.654  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:18.654  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-26 17:27:18.655  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,07-26 17:27:18.656  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-26 17:27:18.657  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-26 17:27:18.659  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-26 17:27:18.661  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-26 17:27:18.662  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-26 17:27:18.671  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-26 17:27:18.671  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-26 17:27:18.672  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-26 17:27:18.673  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,07-26 17:27:18.673  9888  9888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-26 17:27:19.134  4649  4649 D io_stats: !@   8,0 r 25969 2279080 w 4955 202928 d 617 73664 f 2015 2015 iot 11700 10853 th 473188 0 0 pt 0 inp 0 0 287.417
,07-26 17:27:19.147  9888  9970 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-26 17:27:19.150  9888  9951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-26 17:27:19.150  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
07-26 17:27:19.151  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
07-26 17:27:19.151  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
,07-26 17:27:19.151  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
07-26 17:27:19.152  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
07-26 17:27:19.152  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
07-26 17:27:19.152  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
07-26 17:27:19.152  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
,07-26 17:27:19.153  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
07-26 17:27:19.153  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
07-26 17:27:19.153  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
07-26 17:27:19.153  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
07-26 17:27:19.154  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
07-26 17:27:19.154  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
07-26 17:27:19.154  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
07-26 17:27:19.155  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
07-26 17:27:19.155  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
,07-26 17:27:19.155  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
07-26 17:27:19.156  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
07-26 17:27:19.156  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
07-26 17:27:19.156  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
07-26 17:27:19.157  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
07-26 17:27:19.157  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
07-26 17:27:19.157  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
07-26 17:27:19.157  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
07-26 17:27:19.157  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
,07-26 17:27:19.158  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
07-26 17:27:19.158  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
07-26 17:27:19.158  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
07-26 17:27:19.158  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
07-26 17:27:19.159  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
07-26 17:27:19.159  9888  9951 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,07-26 17:27:19.160  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,07-26 17:27:19.160  9888  9951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-26 17:27:19.160  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,07-26 17:27:19.160  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-26 17:27:19.161  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-26 17:27:19.161  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-26 17:27:19.162  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-26 17:27:19.162  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-26 17:27:19.162  9888  9968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-26 17:27:19.162  9888  9968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-26 17:27:19.162  9888  9968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-26 17:27:19.163  9888  9888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-26 17:27:19.164  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-26 17:27:19.164  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 17:27:19.165  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.166  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-26 17:27:19.166  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-26 17:27:19.168  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.169  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.170  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.172  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.175  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:19.179  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:19.184  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-26 17:27:19.186  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:19.188  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:19.188  9888  9951 D BluetoothLeScanner: could not find callback wrapper
07-26 17:27:19.188  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-26 17:27:19.189  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.190  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.191  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.191  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,07-26 17:27:19.191  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.193  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:19.195  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:19.195  9888  9951 D BluetoothLeAdvertiser: stop advertising
,07-26 17:27:19.207  4056  4069 E BtGatt.ContextMap: Context not found for ID 5
07-26 17:27:19.207  4056  4585 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-26 17:27:19.208  4056  4571 D BtGatt.AdvertiseManager: message : 1
,07-26 17:27:19.209  4056  4571 D BtGatt.AdvertiseManager: stop advertise for client =  5
,07-26 17:27:19.209  4056  4571 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-26 17:27:19.211  4056  4571 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-26 17:27:19.217  4056  4174 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-26 17:27:19.217  4056  4174 D BtGatt.GattService: Client app is not null!
,07-26 17:27:19.218  9888  9899 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-26 17:27:19.219  4056  4709 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-26 17:27:19.221  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-26 17:27:19.222  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.222  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-26 17:27:19.222  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.223  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.223  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.223  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 17:27:19.223  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 17:27:19.225  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 17:27:19.225  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.228  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.228  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-26 17:27:19.229  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.229  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.230  9888  9888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 17:27:19.230  9888  9888 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-26 17:27:19.230  9888  9888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-26 17:27:19.230  9888  9888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,07-26 17:27:19.231  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 17:27:19.231  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 17:27:19.231  9888  9888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-26 17:27:19.231  9888  9971 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
07-26 17:27:19.231  9888  9951 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-26 17:27:19.232  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:19.232  9888  9951 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-26 17:27:19.232  9888  9951 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
07-26 17:27:19.232  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
07-26 17:27:19.232  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:19.232  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-26 17:27:19.232  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-26 17:27:19.232  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-26 17:27:19.232  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-26 17:27:19.233  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-26 17:27:19.233  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-26 17:27:19.234  9888  9888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-26 17:27:19.237  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:19.237  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:19.237  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.237  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-26 17:27:19.240  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:19.240  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
,07-26 17:27:19.240  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.241  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-26 17:27:19.241  9888  9951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-26 17:27:19.241  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-26 17:27:19.241  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 17:27:19.242  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-26 17:27:19.243  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-26 17:27:19.243  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,07-26 17:27:19.243  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-26 17:27:19.243  9888  9972 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-26 17:27:19.243  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-26 17:27:19.243  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-26 17:27:19.243  9888  9888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-26 17:27:19.243  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 17:27:19.243  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-26 17:27:19.247  9888  9972 D BluetoothSocket: bindListen(): myUserId = 0
,07-26 17:27:19.247  9888  9972 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 17:27:19.249  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-26 17:27:19.249  9888  9951 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 17:27:19.249  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-26 17:27:19.251  9888  9972 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-26 17:27:19.252  9888  9972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@48de74e, port: 6, type: 1, local socket address: null, socket type: 0
,07-26 17:27:19.253  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:19.254  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:19.255  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:19.258  9888  9951 D BluetoothAdapter: isSecureModeEnabled
,07-26 17:27:19.258  4056  4710 D BtConfig.SecureMode: isSecureModeOn:false
,07-26 17:27:19.259  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.259  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 17:27:19.260  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:19.261  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:19.261  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 17:27:19.261  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 17:27:19.262  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
,07-26 17:27:19.264  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:19.266  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.267  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.267  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-26 17:27:19.267  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-26 17:27:19.267  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "35d3e8aa-16e9-4ee5-85be-d6766e758699", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-26 17:27:19.267  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 4A 3E
07-26 17:27:19.268  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:19.268  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-26 17:27:19.268  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.269  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.269  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,07-26 17:27:19.269  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:19.270  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.270  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.271  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.272  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:19.273  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:19.273  9888  9951 D BluetoothAdapter: isSecureModeEnabled
07-26 17:27:19.274  4056  4069 D BtConfig.SecureMode: isSecureModeOn:false
07-26 17:27:19.274  9888  9951 D BluetoothLeAdvertiser: start advertising
,07-26 17:27:19.275  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:19.279  4056  4069 D BtGatt.GattService: registerClient() - UUID=24ea613e-3597-46d8-9810-cfc4acd7c715
,07-26 17:27:19.382  4056  4174 D BtGatt.GattService: onClientRegistered() - UUID=24ea613e-3597-46d8-9810-cfc4acd7c715, clientIf=5, status=0
07-26 17:27:19.383  9888  9900 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-26 17:27:19.387  4056  4709 E BtGatt.ContextMap: Context not found for ID 5
07-26 17:27:19.388  4056  4571 D BtGatt.AdvertiseManager: message : 0
,07-26 17:27:19.388  4056  4585 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-26 17:27:19.390  4056  4571 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-26 17:27:19.390  4056  4571 D BtGatt.AdvertiseManager: size of list is =0
,07-26 17:27:19.400  4056  4571 D BtGatt.AdvertiseManager: starting advertising
,07-26 17:27:19.404  4056  4571 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-26 17:27:19.409  4056  4638 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-26 17:27:19.431  4056  4174 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-26 17:27:19.434  4056  4571 D BtGatt.AdvertiseManager: starting multi advertising
,07-26 17:27:19.447  4056  4174 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-26 17:27:19.448  4056  4571 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-26 17:27:19.448  4056  4571 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-26 17:27:19.448  4056  4571 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-26 17:27:19.448  4056  4571 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
07-26 17:27:19.449  9888  9899 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-26 17:27:19.451  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.452  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.453  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-26 17:27:19.454  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.455  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.456  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.457  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.458  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.458  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-26 17:27:19.464  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-26 17:27:19.465  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.465  9888  9951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,07-26 17:27:19.471  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.472  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.473  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:19.474  9888  9951 I io.jxcore.node.ConnectionHelper: start: OK
07-26 17:27:19.474  9888  9888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-26 17:27:19.477  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-26 17:27:19.478  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:19.478  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-26 17:27:19.479  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-26 17:27:19.480  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-26 17:27:19.482  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-26 17:27:19.483  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:19.483  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-26 17:27:19.483  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,07-26 17:27:19.484  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-26 17:27:19.485  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-26 17:27:19.487  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-26 17:27:19.488  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-26 17:27:19.489  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-26 17:27:19.499  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-26 17:27:19.499  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
07-26 17:27:19.500  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,07-26 17:27:19.501  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-26 17:27:19.502  9888  9888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-26 17:27:19.978  9888  9974 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-26 17:27:19.983  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,07-26 17:27:19.984  9888  9951 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-26 17:27:19.984  9888  9951 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-26 17:27:19.984  9888  9951 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-26 17:27:19.984  9888  9951 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
07-26 17:27:19.985  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,07-26 17:27:19.985  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-26 17:27:19.996  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:19.997  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,07-26 17:27:19.998  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:19.998  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-26 17:27:20.003  9888  9888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,07-26 17:27:20.009  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:20.009  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,07-26 17:27:20.010  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.010  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
07-26 17:27:20.010  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 64731
07-26 17:27:20.010  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
07-26 17:27:20.010  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
07-26 17:27:20.010  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
07-26 17:27:20.010  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
07-26 17:27:20.010  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
07-26 17:27:20.010  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
07-26 17:27:20.010  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
07-26 17:27:20.010  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.011  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
,07-26 17:27:20.011  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.012  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.013  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.015  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:20.017  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:20.018  9888  9951 D BluetoothLeAdvertiser: stop advertising
,07-26 17:27:20.019  4056  4067 E BtGatt.ContextMap: Context not found for ID 5
07-26 17:27:20.020  4056  4571 D BtGatt.AdvertiseManager: message : 1
07-26 17:27:20.020  4056  4585 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-26 17:27:20.021  4056  4571 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-26 17:27:20.021  4056  4571 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-26 17:27:20.023  4056  4571 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-26 17:27:20.033  4056  4174 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-26 17:27:20.033  4056  4174 D BtGatt.GattService: Client app is not null!
,07-26 17:27:20.034  9888  9900 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-26 17:27:20.035  4056  4710 D BtGatt.GattService: unregisterClient() - clientIf=5
07-26 17:27:20.039  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-26 17:27:20.040  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.040  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-26 17:27:20.041  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.041  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.042  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.042  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-26 17:27:20.043  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.044  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.044  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.044  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-26 17:27:20.044  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,07-26 17:27:20.045  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "35d3e8aa-16e9-4ee5-85be-d6766e758699", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-26 17:27:20.048  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 4A 3E
07-26 17:27:20.049  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:20.049  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:20.050  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.051  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.051  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-26 17:27:20.051  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:20.051  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.052  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.053  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.057  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:20.059  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:20.059  9888  9951 D BluetoothAdapter: isSecureModeEnabled
,07-26 17:27:20.060  4056  4067 D BtConfig.SecureMode: isSecureModeOn:false
,07-26 17:27:20.060  9888  9951 D BluetoothLeAdvertiser: start advertising
07-26 17:27:20.062  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:20.064  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:20.064  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:27:20.069  4056  4067 D BtGatt.GattService: registerClient() - UUID=968dd10c-a292-4fa2-b1d2-936fd297259f
,07-26 17:27:20.172  4056  4174 D BtGatt.GattService: onClientRegistered() - UUID=968dd10c-a292-4fa2-b1d2-936fd297259f, clientIf=5, status=0
,07-26 17:27:20.173  9888  9899 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-26 17:27:20.178  4056  4710 E BtGatt.ContextMap: Context not found for ID 5
,07-26 17:27:20.179  4056  4571 D BtGatt.AdvertiseManager: message : 0
,07-26 17:27:20.179  4056  4585 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-26 17:27:20.181  4056  4571 D BtGatt.AdvertiseManager: number of adv instance running = 0
,07-26 17:27:20.182  4056  4571 D BtGatt.AdvertiseManager: size of list is =0
,07-26 17:27:20.191  4056  4571 D BtGatt.AdvertiseManager: starting advertising
,07-26 17:27:20.196  4056  4571 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-26 17:27:20.200  4056  4638 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-26 17:27:20.221  4056  4174 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-26 17:27:20.224  4056  4571 D BtGatt.AdvertiseManager: starting multi advertising
,07-26 17:27:20.235  4056  4174 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-26 17:27:20.235  4056  4571 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-26 17:27:20.236  4056  4571 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-26 17:27:20.236  4056  4571 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-26 17:27:20.236  4056  4571 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-26 17:27:20.237  9888  9900 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-26 17:27:20.239  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.240  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.240  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-26 17:27:20.241  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.242  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.243  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.244  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.245  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.246  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.246  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 17:27:20.247  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.248  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 17:27:20.248  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-26 17:27:20.249  9888  9951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 17:27:20.249  9888  9951 I io.jxcore.node.ConnectionHelper: start: OK
,07-26 17:27:20.250  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-26 17:27:20.252  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:20.252  9888  9976 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
07-26 17:27:20.252  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-26 17:27:20.252  9888  9951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-26 17:27:20.253  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
07-26 17:27:20.253  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.253  9888  9951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-26 17:27:20.253  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-26 17:27:20.253  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-26 17:27:20.253  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-26 17:27:20.254  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-26 17:27:20.254  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-26 17:27:20.254  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-26 17:27:20.255  9888  9972 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-26 17:27:20.255  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-26 17:27:20.255  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.255  9888  9972 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-26 17:27:20.255  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 17:27:20.255  9888  9972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-26 17:27:20.256  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.256  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:20.256  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-26 17:27:20.256  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-26 17:27:20.257  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.257  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-26 17:27:20.258  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,07-26 17:27:20.258  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.259  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.260  9888  9888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-26 17:27:20.261  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.262  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.262  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.263  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.267  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:20.270  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:20.270  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
07-26 17:27:20.272  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:20.274  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:20.274  9888  9951 D BluetoothLeScanner: could not find callback wrapper
07-26 17:27:20.274  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 17:27:20.275  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.276  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.277  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.277  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-26 17:27:20.278  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.280  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:20.282  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:20.282  9888  9951 D BluetoothLeAdvertiser: stop advertising
07-26 17:27:20.283  4056  4067 E BtGatt.ContextMap: Context not found for ID 5
07-26 17:27:20.284  4056  4585 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-26 17:27:20.285  4056  4571 D BtGatt.AdvertiseManager: message : 1
07-26 17:27:20.286  4056  4571 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-26 17:27:20.287  4056  4571 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
07-26 17:27:20.289  4056  4571 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
07-26 17:27:20.298  4056  4174 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-26 17:27:20.298  4056  4174 D BtGatt.GattService: Client app is not null!
07-26 17:27:20.299  9888  9899 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
07-26 17:27:20.301  4056  4710 D BtGatt.GattService: unregisterClient() - clientIf=5
07-26 17:27:20.303  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-26 17:27:20.303  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.304  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-26 17:27:20.304  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.306  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.306  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.307  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 17:27:20.307  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-26 17:27:20.309  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 17:27:20.309  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.313  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.313  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-26 17:27:20.314  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.315  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.316  9888  9888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 17:27:20.316  9888  9888 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
07-26 17:27:20.317  9888  9888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,07-26 17:27:20.317  9888  9888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-26 17:27:20.317  9888  9977 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
07-26 17:27:20.317  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 17:27:20.317  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 17:27:20.318  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:20.319  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.319  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-26 17:27:20.319  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-26 17:27:20.320  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.320  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
07-26 17:27:20.320  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.321  9888  9951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 17:27:20.321  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.321  9888  9951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e96a48b added. We now have 3 listener(s)
07-26 17:27:20.321  9888  9888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 17:27:20.321  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e96a48b added. We now have 5 listener(s)
07-26 17:27:20.321  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 17:27:20.326  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:20.326  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 17:27:20.326  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:20.327  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 17:27:20.327  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac89968 added. We now have 6 listener(s)
07-26 17:27:20.328  9888  9951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 17:27:20.329  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 17:27:20.335  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 17:27:20.345  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:20.350  9888  9951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 17:27:20.350  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:20.350  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:20.350  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:27:20.350  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:27:20.350  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-26 17:27:20.350  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-26 17:27:20.350  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 17:27:20.350  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 17:27:20.350  9888  9951 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 17:27:20.357  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:20.363  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:20.370  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:20.377  9888  9951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:20.390  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:20.397  9888  9951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 17:27:20.397  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:20.397  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:20.397  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:27:20.397  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:27:20.397  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-26 17:27:20.397  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-26 17:27:20.397  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 17:27:20.397  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 17:27:20.398  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 17:27:20.398  9888  9951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 17:27:20.398  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-26 17:27:20.398  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-26 17:27:20.398  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-26 17:27:20.399  9888  9951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e96a48b removed from the list
07-26 17:27:20.399  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e96a48b removed from the list
07-26 17:27:20.399  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 17:27:20.399  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac89968 removed from the list
07-26 17:27:20.400  9888  9951 D io.jxcore.node.ConnectivityMonitor: stop
07-26 17:27:20.400  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 17:27:20.405  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,07-26 17:27:20.406  9888  9951 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,07-26 17:27:20.410  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,07-26 17:27:20.412  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,07-26 17:27:20.416  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
07-26 17:27:20.416  9888  9951 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,07-26 17:27:20.420  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
07-26 17:27:20.420  9888  9951 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,07-26 17:27:20.424  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
07-26 17:27:20.424  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-26 17:27:20.425  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 17:27:20.426  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 17:27:20.426  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 17:27:20.426  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 17:27:20.427  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 17:27:20.427  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 17:27:20.428  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 17:27:20.428  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-26 17:27:20.430  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
07-26 17:27:20.431  9888  9951 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-26 17:27:20.431  9888  9951 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-26 17:27:20.431  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,07-26 17:27:20.436  9888  9951 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-26 17:27:20.437  9888  9951 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,07-26 17:27:20.437  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
,07-26 17:27:20.437  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
,07-26 17:27:20.438  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
,07-26 17:27:20.438  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
,07-26 17:27:20.438  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
,07-26 17:27:20.438  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
07-26 17:27:20.438  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
,07-26 17:27:20.438  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
07-26 17:27:20.438  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
07-26 17:27:20.438  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
07-26 17:27:20.439  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
07-26 17:27:20.439  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
07-26 17:27:20.439  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
07-26 17:27:20.439  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
07-26 17:27:20.439  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
07-26 17:27:20.439  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
07-26 17:27:20.439  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
07-26 17:27:20.440  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
07-26 17:27:20.440  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
07-26 17:27:20.440  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
07-26 17:27:20.440  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
07-26 17:27:20.440  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
07-26 17:27:20.440  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
07-26 17:27:20.440  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
07-26 17:27:20.440  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
07-26 17:27:20.441  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
07-26 17:27:20.441  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
07-26 17:27:20.441  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
07-26 17:27:20.441  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
07-26 17:27:20.441  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
07-26 17:27:20.441  9888  9951 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-26 17:27:20.441  9888  9951 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 17:27:20.442  9888  9951 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-26 17:27:20.442  9888  9951 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 17:27:20.442  9888  9951 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 17:27:20.442  9888  9951 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-26 17:27:20.443  9888  9951 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
0,7-26 17:27:20.443  9888  9951 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 17:27:20.443  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
07-26 17:27:20.449  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-26 17:27:20.450  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
07-26 17:27:20.450  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-26 17:27:20.451  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,07-26 17:27:20.451  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-26 17:27:20.451  9888  9951 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-26 17:27:20.451  9888  9978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 195)
07-26 17:27:20.451  9888  9978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
07-26 17:27:20.451  9888  9978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
07-26 17:27:20.451  9888  9951 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 17:27:20.451  9888  9978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
07-26 17:27:20.451  9888  9951 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,07-26 17:27:20.454  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,07-26 17:27:20.455  9888  9951 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,07-26 17:27:20.457  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
07-26 17:27:20.457  9888  9951 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,07-26 17:27:20.459  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,07-26 17:27:20.460  9888  9951 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-26 17:27:20.460  9888  9951 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-26 17:27:20.460  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 17:27:20.460  9888  9951 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-26 17:27:20.460  9888  9951 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,07-26 17:27:20.461  9888  9951 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-26 17:27:20.461  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-26 17:27:20.461  9888  9978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
07-26 17:27:20.461  9888  9951 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-26 17:27:20.461  9888  9978 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
07-26 17:27:20.461  9888  9951 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-26 17:27:20.461  9888  9951 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-26 17:27:20.462  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 17:27:20.462  9888  9951 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,07-26 17:27:20.463  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
07-26 17:27:20.464  9888  9951 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-26 17:27:20.464  9888  9951 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-26 17:27:20.464  9888  9951 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,07-26 17:27:20.464  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,07-26 17:27:20.465  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-26 17:27:20.468  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:20.468  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-26 17:27:20.469  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.469  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-26 17:27:20.472  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:20.472  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:20.472  9888  9978 D BluetoothSocket: connect(): myUserId = 0
07-26 17:27:20.472  9888  9978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 17:27:20.472  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.472  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-26 17:27:20.472  9888  9951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-26 17:27:20.472  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-26 17:27:20.472  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 17:27:20.474  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-26 17:27:20.474  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-26 17:27:20.474  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-26 17:27:20.474  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-26 17:27:20.474  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,07-26 17:27:20.474  9888  9979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,07-26 17:27:20.475  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,07-26 17:27:20.475  9888  9888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-26 17:27:20.475  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 17:27:20.475  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 17:27:20.478  9888  9979 D BluetoothSocket: bindListen(): myUserId = 0
07-26 17:27:20.478  9888  9979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 17:27:20.483  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-26 17:27:20.483  9888  9979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-26 17:27:20.483  9888  9951 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 17:27:20.483  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 17:27:20.483  9888  9979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@f48fe67, port: 6, type: 1, local socket address: null, socket type: 0
,07-26 17:27:20.486  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:20.487  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:20.487  3714  4858 D SecContentProvider: insert(), uri = 2
07-26 17:27:20.488  3714  4858 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:20.489  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:20.489  4056  4638 W bt_btif : bta_dm_bl_change_cback : reason=0
,07-26 17:27:20.491  4056  4174 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
,07-26 17:27:20.492  9888  9951 D BluetoothAdapter: isSecureModeEnabled
,07-26 17:27:20.493  4056  4067 D BtConfig.SecureMode: isSecureModeOn:false
07-26 17:27:20.494  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.494  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-26 17:27:20.495  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:20.496  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:20.496  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 17:27:20.496  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 17:27:20.496  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,07-26 17:27:20.498  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:20.501  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.501  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.501  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-26 17:27:20.501  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-26 17:27:20.501  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "35d3e8aa-16e9-4ee5-85be-d6766e758699", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-26 17:27:20.501  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 4A 3E
07-26 17:27:20.502  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:20.502  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:20.502  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.502  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.502  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-26 17:27:20.502  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:20.503  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.503  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.503  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.504  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:20.505  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:20.505  9888  9951 D BluetoothAdapter: isSecureModeEnabled
,07-26 17:27:20.505  4056  4069 D BtConfig.SecureMode: isSecureModeOn:false
07-26 17:27:20.506  9888  9951 D BluetoothLeAdvertiser: start advertising
,07-26 17:27:20.507  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:20.513  4056  4069 D BtGatt.GattService: registerClient() - UUID=85849222-c9ab-4760-825a-28a1c4349f96
,07-26 17:27:20.616  4056  4174 D BtGatt.GattService: onClientRegistered() - UUID=85849222-c9ab-4760-825a-28a1c4349f96, clientIf=5, status=0
,07-26 17:27:20.617  9888  9899 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-26 17:27:20.621  4056  4709 E BtGatt.ContextMap: Context not found for ID 5
,07-26 17:27:20.622  4056  4585 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-26 17:27:20.624  4056  4571 D BtGatt.AdvertiseManager: message : 0
07-26 17:27:20.626  4056  4571 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-26 17:27:20.626  4056  4571 D BtGatt.AdvertiseManager: size of list is =0
,07-26 17:27:20.634  4056  4571 D BtGatt.AdvertiseManager: starting advertising
,07-26 17:27:20.639  4056  4571 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-26 17:27:20.643  4056  4638 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-26 17:27:20.664  4056  4174 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-26 17:27:20.669  4056  4571 D BtGatt.AdvertiseManager: starting multi advertising
,07-26 17:27:20.681  4056  4174 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
07-26 17:27:20.682  4056  4571 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,07-26 17:27:20.682  4056  4571 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-26 17:27:20.682  4056  4571 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-26 17:27:20.682  4056  4571 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
07-26 17:27:20.683  9888  9900 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-26 17:27:20.685  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.687  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.687  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-26 17:27:20.688  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.689  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.690  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.691  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.692  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.692  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-26 17:27:20.697  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-26 17:27:20.698  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.699  9888  9951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,07-26 17:27:20.703  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:20.704  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.705  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:20.706  9888  9951 I io.jxcore.node.ConnectionHelper: start: OK
,07-26 17:27:20.706  9888  9888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-26 17:27:20.708  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.709  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:20.709  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-26 17:27:20.710  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.710  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.711  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:20.711  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.712  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-26 17:27:20.712  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-26 17:27:20.712  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.713  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.714  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.715  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.716  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-26 17:27:20.726  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.726  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-26 17:27:20.727  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,07-26 17:27:20.729  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-26 17:27:20.729  9888  9888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-26 17:27:21.207  9888  9970 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
07-26 17:27:21.208  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 17:27:21.209  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-26 17:27:21.209  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-26 17:27:21.209  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,07-26 17:27:21.210  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-26 17:27:21.210  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,07-26 17:27:21.210  9888  9979 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-26 17:27:21.210  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-26 17:27:21.210  9888  9979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-26 17:27:21.210  9888  9979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-26 17:27:21.210  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 17:27:21.211  9888  9888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-26 17:27:21.211  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-26 17:27:21.211  9888  9888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-26 17:27:21.211  9888  9888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,07-26 17:27:21.214  9888  9951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3daa211 removed from the list
,07-26 17:27:21.215  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3daa211 removed from the list
07-26 17:27:21.215  9888  9981 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 195
07-26 17:27:21.215  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 17:27:21.215  9888  9981 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
07-26 17:27:21.215  9888  9981 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 195)
07-26 17:27:21.215  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 17:27:21.216  4056  4744 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
07-26 17:27:21.216  9888  9981 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 195)
07-26 17:27:21.217  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:21.218  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-26 17:27:21.218  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-26 17:27:21.220  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:21.221  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:21.221  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:21.222  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:21.222  9888  9978 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
07-26 17:27:21.222  9888  9978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
07-26 17:27:21.223  9888  9978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 195)
,07-26 17:27:21.224  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:21.225  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:21.225  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-26 17:27:21.227  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:21.229  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:21.229  9888  9951 D BluetoothLeScanner: could not find callback wrapper
07-26 17:27:21.229  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-26 17:27:21.230  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:21.230  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:21.231  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:21.231  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-26 17:27:21.231  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:21.233  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:21.234  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:21.234  9888  9951 D BluetoothLeAdvertiser: stop advertising
,07-26 17:27:21.235  4056  4710 E BtGatt.ContextMap: Context not found for ID 5
07-26 17:27:21.236  4056  4571 D BtGatt.AdvertiseManager: message : 1
07-26 17:27:21.236  4056  4585 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-26 17:27:21.237  4056  4571 D BtGatt.AdvertiseManager: stop advertise for client =  5
,07-26 17:27:21.237  4056  4571 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-26 17:27:21.239  4056  4571 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-26 17:27:21.244  4056  4174 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-26 17:27:21.244  4056  4174 D BtGatt.GattService: Client app is not null!
,07-26 17:27:21.245  9888  9899 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-26 17:27:21.247  4056  4067 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-26 17:27:21.248  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-26 17:27:21.249  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:21.249  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-26 17:27:21.250  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:21.250  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:21.251  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:21.251  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 17:27:21.251  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-26 17:27:21.252  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 17:27:21.253  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:21.255  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:21.256  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-26 17:27:21.256  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:21.257  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:21.257  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9e5f76 removed from the list
,07-26 17:27:21.257  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 17:27:21.257  9888  9951 D io.jxcore.node.ConnectivityMonitor: stop
07-26 17:27:21.257  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 17:27:21.257  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 17:27:21.257  9888  9888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-26 17:27:21.258  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:21.258  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:21.259  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-26 17:27:21.259  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-26 17:27:21.259  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-26 17:27:21.260  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-26 17:27:21.260  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-26 17:27:21.261  9888  9888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-26 17:27:21.762  9888  9888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-26 17:27:22.866  3714  3799 I PowerManagerService: [PWL] On : 0 (291150 ms ago)
07-26 17:27:22.866  3714  3799 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-26 17:27:23.091  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:23.091  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:27:24.139  4649  4649 D io_stats: !@   8,0 r 25970 2279084 w 4986 203500 d 628 73708 f 2025 2025 iot 11750 10884 th 473040 0 0 pt 0 inp 0 0 292.422
,07-26 17:27:24.907  3714  5765 D SSRM:f  : SIOP:: AP = 300, PST = 311 (W:14), CP = 255, CUR = -35, LCD = 57
,07-26 17:27:26.111  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:26.111  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:27:26.260  9888  9971 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,07-26 17:27:26.264  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,07-26 17:27:26.267  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-26 17:27:26.267  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 17:27:26.271  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-26 17:27:26.273  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,07-26 17:27:26.274  9888  9982 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-26 17:27:26.274  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-26 17:27:26.274  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-26 17:27:26.275  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,07-26 17:27:26.275  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-26 17:27:26.275  9888  9888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-26 17:27:26.280  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,07-26 17:27:26.281  9888  9951 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
07-26 17:27:26.281  9888  9982 D BluetoothSocket: bindListen(): myUserId = 0
07-26 17:27:26.281  9888  9982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 17:27:26.283  9888  9951 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-26 17:27:26.284  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 17:27:26.285  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 17:27:26.290  9888  9982 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,07-26 17:27:26.290  9888  9982 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@d0464bd, port: 6, type: 1, local socket address: null, socket type: 0
,07-26 17:27:26.292  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,07-26 17:27:26.308  9888  9951 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,07-26 17:27:26.310  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 17:27:26.310  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-26 17:27:26.310  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-26 17:27:26.310  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-26 17:27:26.311  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 17:27:26.311  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-26 17:27:26.311  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-26 17:27:26.312  9888  9982 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-26 17:27:26.312  9888  9982 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-26 17:27:26.312  9888  9982 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-26 17:27:26.312  9888  9888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-26 17:27:26.312  9888  9951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3daa211 not in the list
07-26 17:27:26.312  9888  9951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3daa211 not in the list
07-26 17:27:26.312  9888  9888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-26 17:27:26.312  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 17:27:26.312  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 17:27:26.313  9888  9888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-26 17:27:26.313  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:26.314  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-26 17:27:26.314  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-26 17:27:26.314  9888  9951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 17:27:26.314  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 17:27:26.316  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:26.321  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:26.322  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-26 17:27:26.322  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:26.323  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:26.324  9888  9951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9e5f76 not in the list
07-26 17:27:26.324  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 17:27:26.324  9888  9951 D io.jxcore.node.ConnectivityMonitor: stop
07-26 17:27:26.324  9888  9951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 17:27:26.324  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 17:27:26.324  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 17:27:26.325  9888  9888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-26 17:27:26.329  9888  9951 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,07-26 17:27:26.330  9888  9951 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-26 17:27:26.331  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-26 17:27:26.331  9888  9951 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-26 17:27:26.332  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 17:27:26.332  9888  9951 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-26 17:27:26.332  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-26 17:27:26.335  9888  9951 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,07-26 17:27:26.338  9888  9951 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,07-26 17:27:26.341  9888  9951 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,07-26 17:27:26.342  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
07-26 17:27:26.342  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,07-26 17:27:26.345  9888  9951 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,07-26 17:27:26.347  9888  9951 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-26 17:27:26.347  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,07-26 17:27:26.347  9888  9951 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-26 17:27:26.348  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-26 17:27:26.348  9888  9951 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-26 17:27:26.348  9888  9951 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-26 17:27:26.350  9888  9951 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,07-26 17:27:26.351  9888  9951 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-26 17:27:26.351  9888  9951 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-26 17:27:26.353  9888  9951 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
07-26 17:27:26.354  9888  9951 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,07-26 17:27:26.354  9888  9951 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-26 17:27:26.355  9888  9951 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,07-26 17:27:26.355  9888  9951 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,07-26 17:27:26.357  9888  9951 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,07-26 17:27:26.359  9888  9951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 17:27:26.359  9888  9951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8beaab2 added. We now have 2 listener(s)
07-26 17:27:26.360  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8beaab2 added. We now have 3 listener(s)
07-26 17:27:26.360  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 17:27:26.363  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-26 17:27:26.364  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 17:27:26.364  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:26.365  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 17:27:26.365  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8dd1a03 added. We now have 4 listener(s)
,07-26 17:27:26.365  9888  9951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 17:27:26.366  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 17:27:26.372  9888  9951 D BluetoothAdapter: enable()
,07-26 17:27:26.377  4056  4709 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-26 17:27:26.377  4056  4709 D AdapterProvider: query
,07-26 17:27:26.382  3714  3763 I ActivityManager: KPU : put [com.google.android.gm] : 32480 K
,07-26 17:27:26.383  3714  3763 I ActivityManager: Killing 8787:com.google.android.gm/u0a108 (adj 906): DHA:empty #33
,07-26 17:27:26.388  4056  4709 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@38c50fc
,07-26 17:27:26.390  4056  4709 D BluetoothAdapterService: updateEvent - already set, update
07-26 17:27:26.390  4056  4709 W BluetoothAdapterService: updateEvent - alreadySet is true
07-26 17:27:26.390  4056  4709 D AdapterProvider: update
,07-26 17:27:26.394  4056  4709 E BluetoothAdapterService: updateEvent - update success 1
,07-26 17:27:26.397  9888  9951 D BluetoothAdapter: enable(): BT is already enabled..!
,07-26 17:27:26.403  3714  4541 D WifiService: setWifiEnabled: true pid=9888, uid=10033
07-26 17:27:26.403  3714  4541 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-26 17:27:26.404  3714  4541 D WifiControlHistoryProvider: query
,07-26 17:27:26.411  3714  4541 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-26 17:27:26.412  3714  4541 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:26.413  3714  4541 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-26 17:27:26.416  3714  4541 I WifiService: Wi-Fi Sharing settings has not been accessed
07-26 17:27:26.416  3714  4541 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-26 17:27:26.419  9888  9951 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,07-26 17:27:26.422  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:26.424  3714  3739 D ActivityManager: cleanUpApplicationRecord -- 8787
,07-26 17:27:26.427  9888  9951 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
07-26 17:27:26.429  4844  4856 D ForegroundUtils: could not check pending caller
07-26 17:27:26.430  9888  9951 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
07-26 17:27:26.436  9888  9951 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,07-26 17:27:26.443  9888  9983 D BluetoothAdapter: disable()
,07-26 17:27:26.446  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:26.447  4056  4067 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : false
07-26 17:27:26.448  4056  4067 D AdapterProvider: query
07-26 17:27:26.455  4056  4067 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@fbe7a0b
,07-26 17:27:26.456  4056  4067 D BluetoothAdapterService: updateEvent - already set, update
,07-26 17:27:26.457  4056  4067 W BluetoothAdapterService: updateEvent - alreadySet is true
07-26 17:27:26.457  4056  4067 D AdapterProvider: update
,07-26 17:27:26.459  9888  9951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 17:27:26.459  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:26.459  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:26.459  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:27:26.459  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:27:26.459  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-26 17:27:26.459  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-26 17:27:26.459  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 17:27:26.459  9888  9951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 17:27:26.461  4056  4067 E BluetoothAdapterService: updateEvent - update success 1
07-26 17:27:26.466  3714  3796 D SecContentProvider: insert(), uri = 2
07-26 17:27:26.467  3714  3796 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:26.468  4056  4163 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,07-26 17:27:26.471  4056  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-26 17:27:26.471  4056  4163 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-26 17:27:26.473  4056  4056 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
07-26 17:27:26.474  3714  3796 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
07-26 17:27:26.475  4056  4163 D BluetoothAdapterService: Autoconnection is available 
07-26 17:27:26.475  4056  4163 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-26 17:27:26.476  4056  4163 D BluetoothAdapterService: terminating service from this receiver
,07-26 17:27:26.481  4056  4056 D DOWNLOADABLE_DB: onReceive of BR
07-26 17:27:26.481  4056  4056 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-26 17:27:26.481  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.481  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
,07-26 17:27:26.483  4068  4068 D BluetoothPbap: Proxy object disconnected
07-26 17:27:26.483  4068  4068 D PbapServerProfile: Bluetooth service disconnected
,07-26 17:27:26.489  4056  4163 W bt_btif : btif_dm_cancel_discovery
,07-26 17:27:26.491  3714  3738 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
07-26 17:27:26.492  3714  3738 D SecContentProvider: called from android.uid.bluetooth:1002
07-26 17:27:26.492  3714  3946 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{cd501bc: PendingIntentRecord{a13545 com.google.android.gms broadcastIntent}}
,07-26 17:27:26.493  3714  4546 D SecContentProvider: insert(), uri = 2
07-26 17:27:26.494  3714  4546 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:26.495  4068  4284 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:26.495  4068  4284 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
07-26 17:27:26.496  4056  4163 I BluetoothAdapterState: Entering PendingCommandState
07-26 17:27:26.499  3714  3714 D BluetoothPhoneService: Bluetooth Adapter state : 13
,07-26 17:27:26.507  3714  3714 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-26 17:27:26.507  3714  3714 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:26.507  3714  3714 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-26 17:27:26.518  3714  4857 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4056 / op:PendingIntent{b3ce49a: PendingIntentRecord{fb071cb com.android.bluetooth broadcastIntent}}
07-26 17:27:26.520  3714  4937 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{ece7da8: PendingIntentRecord{24e0c1 com.google.android.gms broadcastIntent}}
07-26 17:27:26.522  9888  9888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 17:27:26.522  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 17:27:26.522  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:26.522  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:26.522  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:27:26.522  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 17:27:26.522  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-26 17:27:26.522  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-26 17:27:26.522  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 17:27:26.522  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 17:27:26.524  4056  4174 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,07-26 17:27:26.524  9888  9888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 17:27:26.524  9888  9888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
07-26 17:27:26.524  4056  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,07-26 17:27:26.528  4056  4056 D DOWNLOADABLE_DB: onReceive of BR
,07-26 17:27:26.529  4056  4056 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-26 17:27:26.529  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.529  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.529  4056  4056 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-26 17:27:26.529  4056  4163 E BluetoothServiceJni: disableBrEdrNative:
07-26 17:27:26.529  4056  4163 E bt_btif : disable_bredr
07-26 17:27:26.529  4056  4056 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
,07-26 17:27:26.530  4056  4056 D BluetoothSdpJni: SDP Remove record success - handle: 1
07-26 17:27:26.530  4056  4174 W bt_btif : btif_dm_generic_evt: event=33035
07-26 17:27:26.530  4056  4746 W bt_osi_thread: run_thread: thread id 4746, thread name btif_sock exited
07-26 17:27:26.531  4056  4739 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
07-26 17:27:26.531  4056  4739 D BluetoothSdpJni: SDP Remove record success - handle: 0
07-26 17:27:26.531  4056  4739 D BluetoothMapMasInstance: RemoveSDPrecord returns true
07-26 17:27:26.532  4056  4739 D ObexServerSockets: shutdown(block = true)
07-26 17:27:26.533  4056  4739 D ObexServerSockets: shutdown called from another thread - interrupt().
07-26 17:27:26.533  4056  4739 D ObexServerSockets: shutdown called from another thread - interrupt().
07-26 17:27:26.533  4056  5047 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 17:27:26.533  4056  4169 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-26 17:27:26.533  4056  5047 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-26 17:27:26.533  4056  5049 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 17:27:26.533  4056  5595 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 17:27:26.535  4056  5049 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-26 17:27:26.535  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 17:27:26.535  4056  4169 E bt_btif : BTA_DisableBluetoothOnly
07-26 17:27:26.536  4056  4056 I BtOppRfcommListener: stopping Accept Thread
07-26 17:27:26.536  4056  4638 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
07-26 17:27:26.538  4056  5595 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-26 17:27:26.551  4056  4174 W bt_btif : btif_dm_generic_evt: event=33035
,07-26 17:27:26.552  9173  9173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-26 17:27:26.553  4056  4056 V BluetoothOppManager: cleanUp...
,07-26 17:27:26.555  4056  4638 W bt_btm  : btm_sec_connected
07-26 17:27:26.555  4056  4638 W bt_btif : bta_dm_bl_change_cback : reason=2
,07-26 17:27:26.556  4056  4638 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
07-26 17:27:26.556  4056  4638 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
07-26 17:27:26.556  4056  4638 W bt_btif : bta_dm_bl_change_cback : reason=2
07-26 17:27:26.562  4056  4174 W bt_btif : btif_dm_generic_evt: event=33035
,07-26 17:27:26.568  4056  4174 W bt_btif : btif_dm_generic_evt: event=33035
,07-26 17:27:26.571  4056  4174 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
07-26 17:27:26.571  4056  4174 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
,07-26 17:27:26.578  9173  9173 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,07-26 17:27:26.580  4056  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
,07-26 17:27:26.582  4056  4174 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 1
,07-26 17:27:26.584  4056  4174 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-26 17:27:26.584  4056  4174 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 241
07-26 17:27:26.584  4068  4284 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
07-26 17:27:26.585  9173  9173 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,07-26 17:27:26.587  9173  9173 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,07-26 17:27:26.592  9173  9173 D LocalBluetoothProfileManager: LocalBluetoothProfileManager :: uuid is null
,07-26 17:27:26.592  9173  9173 D LocalBluetoothProfileManager: PANU : true
,07-26 17:27:26.605  9173  9173 D BluetoothSap: Create BluetoothSap proxy object
,07-26 17:27:26.611  9173  9173 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-26 17:27:26.611  9173  9173 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,07-26 17:27:26.617  9173  9173 D DockEventReceiver: finishStartingService: stopping service
,07-26 17:27:26.625  9173  9173 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:26.625  9173  9173 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
,07-26 17:27:26.625  9173  9173 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 17:27:26.626  9173  9173 D PanProfile: Bluetooth service connected
,07-26 17:27:26.628  9173  9173 D BluetoothSap: Proxy object connected
,07-26 17:27:26.629  9173  9173 D SapProfile: Bluetooth service connected
,07-26 17:27:26.666  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-26 17:27:26.674  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-26 17:27:26.675  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-26 17:27:26.737  4056  4174 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_BT_EVT
07-26 17:27:26.737  4056  4174 E BluetoothAdapterState: stateChangeCallback : 16
07-26 17:27:26.737  4056  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
,07-26 17:27:26.826  9888  9888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-26 17:27:26.831  4056  4163 D BtConfig.SecureMode: isSecureModeOn:false
07-26 17:27:26.832  4056  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-26 17:27:26.835  4056  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-26 17:27:26.836  4056  4056 D HeadsetService: Received stop request...Stopping profile...
,07-26 17:27:26.838  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
,07-26 17:27:26.838  4056  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-26 17:27:26.838  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
07-26 17:27:26.838  4056  4056 D HeadsetService: notifyProfileServiceStateChanged
,07-26 17:27:26.843  4056  4056 D A2dpService: Received stop request...Stopping profile...
,07-26 17:27:26.844  4056  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-26 17:27:26.845  4056  4716 D A2dpStateMachine: Exit Disconnected: -1
07-26 17:27:26.846  4068  4068 D HeadsetProfile: Bluetooth service disconnected
07-26 17:27:26.847  3714  3714 W BluetoothHeadset: Proxy not attached to service
07-26 17:27:26.847  3714  3714 I Telecom : SecBluetoothManager : not single connected gear
07-26 17:27:26.847  3714  3714 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
,07-26 17:27:26.847  3714  3714 D BluetoothHeadset: unRegisterMessageListener : 11
07-26 17:27:26.847  3714  3714 W BluetoothHeadset: Proxy not attached to service
07-26 17:27:26.847  3714  3714 I Telecom : SecBluetoothManager : unregister MessageListener
07-26 17:27:26.847  3714  4567 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACU_0
07-26 17:27:26.848  3714  4567 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACU_0
07-26 17:27:26.848  3714  4567 I Telecom : SecBluetoothManager : mBluetoothHeadset is null
07-26 17:27:26.848  3714  4567 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACU_0
07-26 17:27:26.849  4056  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-26 17:27:26.849  4056  4056 D Avrcp   : unregisterContentObserver
,07-26 17:27:26.851  4056  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-26 17:27:26.852  4056  4056 D Avrcp   : removeOnActiveSessionsChangedListener
07-26 17:27:26.853  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.853  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
07-26 17:27:26.854  4056  4056 D A2dpService: notifyProfileServiceStateChanged
07-26 17:27:26.854  4056  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-26 17:27:26.856  4068  4068 D A2dpProfile: Bluetooth service disconnected
07-26 17:27:26.857  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:26.857  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
07-26 17:27:26.857  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-26 17:27:26.857  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-26 17:27:26.857  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:26.857  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:26.857  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.859  4056  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-26 17:27:26.860  4056  4163 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-26 17:27:26.860  4056  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
07-26 17:27:26.860  4056  4163 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
07-26 17:27:26.860  4056  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-26 17:27:26.863  4056  4056 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-26 17:27:26.863  4056  4056 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-26 17:27:26.866  4056  4056 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
,07-26 17:27:26.867  4056  4056 D HidService: Received stop request...Stopping profile...
07-26 17:27:26.867  4056  4056 D HidService: Stopping Bluetooth HidService
07-26 17:27:26.867  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.867  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
07-26 17:27:26.868  4056  4056 D HidService: notifyProfileServiceStateChanged
,07-26 17:27:26.869  4068  4068 D BluetoothInputDevice: Proxy object disconnected
07-26 17:27:26.869  4068  4068 D HidProfile: Bluetooth service disconnected
,07-26 17:27:26.871  4056  4056 D HealthService: Received stop request...Stopping profile...
07-26 17:27:26.871  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.871  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
07-26 17:27:26.871  4056  4056 D HealthService: notifyProfileServiceStateChanged
,07-26 17:27:26.874  4056  4056 D PanService: Received stop request...Stopping profile...
,07-26 17:27:26.875  4056  4056 D EnhancedTetheringManager: stop
,07-26 17:27:26.877  4056  4056 D EnhancedTetheringManager: tetherEnabled : false
,07-26 17:27:26.877  4056  4056 D ETMLeHelper: stopAdvertise
07-26 17:27:26.877  4056  4056 D BluetoothAdapter: STATE_TURNING_OFF
07-26 17:27:26.878  4056  4056 D BluetoothAdapter: STATE_TURNING_OFF
07-26 17:27:26.878  4056  4056 D BluetoothLeAdvertiser: stop advertising
07-26 17:27:26.879  4056  4056 D BluetoothLeAdvertiser: wrapper is null
07-26 17:27:26.879  4056  4056 D EnhancedTetheringManager: removeNapWakeAlarm
,07-26 17:27:26.883  3714  4543 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4056 / op:PendingIntent{af4f6a2: PendingIntentRecord{be8f33 com.android.bluetooth broadcastIntent}}
,07-26 17:27:26.885  4056  4056 D EnhancedTetheringManager: cancelFindTetherServer
07-26 17:27:26.885  4056  4056 D ETMLeHelper: stopScan
,07-26 17:27:26.886  4056  4056 D BluetoothAdapter: STATE_TURNING_OFF
,07-26 17:27:26.887  4056  4056 D BluetoothAdapter: STATE_TURNING_OFF
07-26 17:27:26.887  4056  4056 D BluetoothLeScanner: could not find callback wrapper
07-26 17:27:26.887  4056  4056 D EnhancedTetheringManager: removePanuWakeAlarm
07-26 17:27:26.889  3714  4938 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4056 / op:PendingIntent{536b2f0: PendingIntentRecord{86f8069 com.android.bluetooth broadcastIntent}}
,07-26 17:27:26.890  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.890  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
07-26 17:27:26.890  4056  4056 D PanService: notifyProfileServiceStateChanged
07-26 17:27:26.891  4068  4068 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-26 17:27:26.891  4068  4068 D PanProfile: Bluetooth service disconnected
07-26 17:27:26.893  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:26.893  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
07-26 17:27:26.893  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-26 17:27:26.893  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-26 17:27:26.893  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:26.893  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:26.894  4056  4056 D BluetoothMapService: Received stop request...Stopping profile...
07-26 17:27:26.895  9173  9173 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-26 17:27:26.896  9173  9173 D PanProfile: Bluetooth service disconnected
,07-26 17:27:26.900  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.900  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
07-26 17:27:26.900  4056  4056 D BluetoothMapService: notifyProfileServiceStateChanged
,07-26 17:27:26.903  4068  4068 D BluetoothMap: Proxy object disconnected
07-26 17:27:26.903  4068  4068 D MapProfile: Bluetooth service disconnected
,07-26 17:27:26.904  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
,07-26 17:27:26.906  4056  4718 W bt_osi_thread: run_thread: thread id 4718, thread name media_worker exited
,07-26 17:27:26.909  4056  4056 D SapService: Received stop request...Stopping profile...
07-26 17:27:26.909  4056  4056 V SapService: stop()
07-26 17:27:26.910  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.910  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
07-26 17:27:26.910  4056  4056 D SapService: notifyProfileServiceStateChanged
,07-26 17:27:26.911  4068  4068 D BluetoothSap: Proxy object disconnected
07-26 17:27:26.911  4068  4068 D SapProfile: Bluetooth service disconnected
07-26 17:27:26.911  9173  9173 D BluetoothSap: Proxy object disconnected
07-26 17:27:26.912  9173  9173 D SapProfile: Bluetooth service disconnected
,07-26 17:27:26.914  4056  4056 D HidDevService: Received stop request...Stopping profile...
,07-26 17:27:26.914  4056  4056 D HidDevService: stop()
,07-26 17:27:26.915  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.915  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Message sending
07-26 17:27:26.915  4056  4056 D HidDevService: notifyProfileServiceStateChanged
,07-26 17:27:26.917  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:26.917  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
07-26 17:27:26.917  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-26 17:27:26.917  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-26 17:27:26.917  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:26.917  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:26.918  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.918  4056  4056 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-26 17:27:26.918  4056  4056 W bt_btif : cleanup: HH disabling or disabled already, status = 0
07-26 17:27:26.918  4056  4056 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-26 17:27:26.918  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:26.918  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
07-26 17:27:26.918  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-26 17:27:26.918  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-26 17:27:26.918  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:26.918  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:26.919  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.919  4056  4056 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-26 17:27:26.920  4056  4056 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-26 17:27:26.920  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:26.920  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
07-26 17:27:26.920  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-26 17:27:26.920  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-26 17:27:26.920  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:26.920  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:26.921  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.921  4056  4056 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-26 17:27:26.921  4056  4056 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-26 17:27:26.923  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:26.923  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
07-26 17:27:26.923  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-26 17:27:26.923  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-26 17:27:26.923  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:26.923  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:26.924  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.926  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:26.926  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
07-26 17:27:26.926  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-26 17:27:26.926  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-26 17:27:26.926  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:26.926  4056  4056 V Bluet,oothAdapterState: isBleTurningOff()=false
07-26 17:27:26.926  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.926  3714  3923 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{acfdaee: PendingIntentRecord{148eb8f com.google.android.gms broadcastIntent}}
07-26 17:27:26.926  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:26.926  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Before synchronized
07-26 17:27:26.926  4056  4056 V BluetoothAdapterState: isTurningOff()=true
07-26 17:27:26.926  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-26 17:27:26.926  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:26.926  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:26.926  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.926  4056  4056 D HidDevService: cleanup()
07-26 17:27:26.926  4056  4056 V BluetoothHidDevServiceJni: cleanupNative enter
07-26 17:27:26.926  4056  4056 I BluetoothHidDevServiceJni: Cleaning up interface
07-26 17:27:26.926  4056  4056 I BluetoothHidDevServiceJni: Cleaning up callback object
07-26 17:27:26.926  4056  4056 V BluetoothHidDevServiceJni: cleanupNative done
07-26 17:27:26.926  4056  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
,07-26 17:27:26.929  4056  4163 D BtGatt.GattService: getGattService(): returning com.android.bluetooth.gatt.GattService@c1c4be3
07-26 17:27:26.929  4056  4163 D BtGatt.GattService: serverDisconnectIncomingConnClients()
07-26 17:27:26.930  4056  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,07-26 17:27:26.930  4056  4638 W bt_btif : BTA got unregistered event id 32
07-26 17:27:26.930  4056  4163 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-26 17:27:26.933  4779  6820 I BeaconBle: Client requested to stop, listener=hjz@6bde9b2
07-26 17:27:26.933  4056  4163 D BluetoothAdapterService: Autoconnection is available 
07-26 17:27:26.933  4056  4163 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
07-26 17:27:26.933  4056  4163 I BluetoothAdapterState: Entering BleOnState
,07-26 17:27:26.938  9888  9900 D BluetoothAdapter: onBluetoothStateChange: up=false
07-26 17:27:26.938  9888  9900 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-26 17:27:26.938  9888  9900 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
07-26 17:27:26.939  9888  9900 D BluetoothLeAdvertiser: Exit stop advertising
,07-26 17:27:26.940  4779  6820 I BeaconBle: Scan canceled successfully.
07-26 17:27:26.940  9888  9900 D BluetoothAdapter: There are no active google scan apps, stop scan
07-26 17:27:26.940  4056  4056 D DOWNLOADABLE_DB: onReceive of BR
07-26 17:27:26.940  4056  4056 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-26 17:27:26.940  9888  9900 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
07-26 17:27:26.940  9888  9900 D BluetoothLeScanner: Exiting stopAllScan
07-26 17:27:26.940  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.940  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
,07-26 17:27:26.944  4056  4056 D DOWNLOADABLE_DB: onReceive of BR
,07-26 17:27:26.945  4056  4056 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-26 17:27:26.945  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.945  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:26.946  3714  4900 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{36c0e1c: PendingIntentRecord{6f6ba25 com.google.android.gms broadcastIntent}}
07-26 17:27:26.946  3714  3725 I art     : Background partial concurrent mark sweep GC freed 207359(13MB) AllocSpace objects, 116(2MB) LOS objects, 28% free, 40MB/56MB, paused 1.848ms total 180.761ms
,07-26 17:27:26.951  4779  5201 D BluetoothAdapter: onBluetoothStateChange: up=false
07-26 17:27:26.951  4779  5201 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-26 17:27:26.957  4779  5201 D BluetoothAdapter: There are no active google scan apps, stop scan
07-26 17:27:26.957  4779  5201 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,07-26 17:27:26.957  4779  5201 D BluetoothLeScanner: Exiting stopAllScan
,07-26 17:27:26.965  3714  3918 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{5fdd3a1: PendingIntentRecord{31459c6 com.google.android.gms broadcastIntent}}
,07-26 17:27:26.969  9173  9184 D BluetoothAdapter: onBluetoothStateChange: up=false
07-26 17:27:26.969  9173  9184 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-26 17:27:26.970  9173  9184 D BluetoothAdapter: There are no active google scan apps, stop scan
07-26 17:27:26.970  4844  4856 D BluetoothAdapter: onBluetoothStateChange: up=false
07-26 17:27:26.970  4844  4856 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-26 17:27:26.971  4779  6807 W NearbyMessages: NetworkPollManager:  No operations for client(com.google.android.gms#0p:discoverer). It should not be in the tracker.
,07-26 17:27:26.971  4779  6807 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
07-26 17:27:26.971  4844  4856 D BluetoothAdapter: There are no active google scan apps, stop scan
07-26 17:27:26.973  9503  9514 D BluetoothAdapter: onBluetoothStateChange: up=false
07-26 17:27:26.974  9503  9514 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-26 17:27:26.975  9503  9514 D BluetoothAdapter: There are no active google scan apps, stop scan
07-26 17:27:26.975  4068  4082 D BluetoothMap: onBluetoothStateChange: up=false
,07-26 17:27:26.977  4043  4292 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-26 17:27:26.977  4043  4292 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-26 17:27:26.977  4043  4292 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-26 17:27:26.978  9173  9185 D BluetoothPan: onBluetoothStateChange on: false
07-26 17:27:26.979  4056  4067 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-26 17:27:26.981  4068  4549 D BluetoothSap: onBluetoothStateChange: up=false
,07-26 17:27:26.982  9173  9184 D BluetoothSap: onBluetoothStateChange: up=false
,07-26 17:27:26.983  4068  4084 D BluetoothPbap: onBluetoothStateChange: up=false
,07-26 17:27:26.984  3714  3796 D BluetoothAdapter: onBluetoothStateChange: up=false
07-26 17:27:26.984  3714  3796 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-26 17:27:26.984  3714  3796 D BluetoothAdapter: There are no active google scan apps, stop scan
07-26 17:27:26.985  4068  4082 D BluetoothPan: onBluetoothStateChange on: false
,07-26 17:27:26.986  4068  4361 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-26 17:27:26.987  4068  4549 D BluetoothAdapter: onBluetoothStateChange: up=false
07-26 17:27:26.987  4068  4549 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-26 17:27:26.988  4068  4549 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-26 17:27:26.990  4056  4163 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,07-26 17:27:26.990  9888  9983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 17:27:26.990  9888  9983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 17:27:26.990  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:26.990  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:26.990  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:27:26.990  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 17:27:26.990  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-26 17:27:26.990  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-26 17:27:26.990  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 17:27:26.990  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 17:27:26.992  9888  9983 D BluetoothAdapter: enable()
,07-26 17:27:26.996  9888  9951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:26.997  4068  4284 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:26.997  4068  4284 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
07-26 17:27:26.997  3714  3714 D Telecom : SecBluetoothManager : unregister BluetoothHeadset after STATE_OFF : null
07-26 17:27:26.997  3714  3714 D Telecom : SecBluetoothManager : unRegisterBluetoothHeadsetMessageListener fail
,07-26 17:27:26.998  3714  3714 D BluetoothPhoneService: Bluetooth Adapter state : 10
,07-26 17:27:27.001  3714  3714 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-26 17:27:27.001  3714  3714 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:27.001  3714  3714 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-26 17:27:27.006  9173  9173 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:27.007  9173  9173 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
07-26 17:27:27.008  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:27.011  4056  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-26 17:27:27.011  4056  4163 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-26 17:27:27.012  3714  3796 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
07-26 17:27:27.013  4056  4163 D BluetoothAdapterService: Autoconnection is available 
07-26 17:27:27.013  4056  4163 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
07-26 17:27:27.014  3714  4858 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
07-26 17:27:27.016  3714  3739 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{828bd87: PendingIntentRecord{8204b4 com.google.android.gms broadcastIntent}}
07-26 17:27:27.016  3714  4858 D SecContentProvider: called from android.uid.bluetooth:1002
07-26 17:27:27.016  4056  4056 D DOWNLOADABLE_DB: onReceive of BR
07-26 17:27:27.017  4056  4056 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-26 17:27:27.017  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:27.017  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:27.018  4056  4069 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-26 17:27:27.019  4056  4069 D AdapterProvider: query
07-26 17:27:27.019  9173  9173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-26 17:27:27.020  3714  4542 D SecContentProvider: insert(), uri = 2
07-26 17:27:27.021  3714  4542 D SecContentProvider: called from android.uid.bluetooth:1002
07-26 17:27:27.022  4056  4169 E bt_btif : btif_vhci_sock_cleanup
07-26 17:27:27.022  4056  4163 I BluetoothAdapterState: Entering PendingCommandState
07-26 17:27:27.024  4056  4169 I bt_core_module: module_shut_down Shutting down module "btif_config_module"
07-26 17:27:27.026  4056  4174 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,07-26 17:27:27.030  4056  4056 D DOWNLOADABLE_DB: onReceive of BR
07-26 17:27:27.030  4056  4056 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-26 17:27:27.030  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:27.030  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:27.034  3714  4936 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{1ec4c52: PendingIntentRecord{a49ab23 com.google.android.gms broadcastIntent}}
07-26 17:27:27.037  4056  4069 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@c3e5632
07-26 17:27:27.038  4056  4069 D BluetoothAdapterService: updateEvent - already set, update
07-26 17:27:27.039  4056  4069 W BluetoothAdapterService: updateEvent - alreadySet is true
07-26 17:27:27.039  4056  4069 D AdapterProvider: update
,07-26 17:27:27.043  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:27.043  9173  9173 D DockEventReceiver: finishStartingService: stopping service
07-26 17:27:27.047  4056  4069 E BluetoothAdapterService: updateEvent - update success 1
07-26 17:27:27.049  9173  9173 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:27.049  9173  9173 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
07-26 17:27:27.052  4056  4638 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-26 17:27:27.052  4056  4174 W bt_btif : btif_dm_generic_evt: event=33035
,07-26 17:27:27.061  4056  4169 I bt_core_module: module_shut_down Shutdown of module "btif_config_module" completed
,07-26 17:27:27.062  4056  4174 W bt_btif : btif_dm_generic_evt: event=33035
07-26 17:27:27.064  3714  4543 W ActivityManager: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-26 17:27:27.068  3714  4543 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-26 17:27:27.068  3714  4543 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-26 17:27:27.068  3714  4543 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-26 17:27:27.068  3714  4543 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-26 17:27:27.068  3714  4543 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-26 17:27:27.068  3714  4543 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-26 17:27:27.068  3714  4543 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-26 17:27:27.068  3714  4543 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-26 17:27:27.068  3714  4543 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-26 17:27:27.068  3714  4543 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
07-26 17:27:27.069  3714  4543 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-26 17:27:27.070  3714  4543 D SecContentProvider: called from com.thaliproject.thalitest
,07-26 17:27:27.081  4056  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
,07-26 17:27:27.256  4056  4174 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_EVT
,07-26 17:27:27.257  4056  4174 I bt_core_module: module_shut_down Shutting down module "hci_module"
07-26 17:27:27.257  4056  4174 I bt_hci  : shut_down
,07-26 17:27:27.273  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-26 17:27:27.284  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-26 17:27:27.284  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-26 17:27:27.291  4056  4587 D bt_hwcfg: hw_epilog_process
07-26 17:27:27.294  4056  4587 I bt_vendor: low_power_mode_cb
,07-26 17:27:27.297  4056  4587 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-26 17:27:27.298  4056  4587 I bt_vendor: epilog_cb
,07-26 17:27:27.298  4056  4587 I bt_hci  : epilog_finished_callback
07-26 17:27:27.298  4056  4587 W bt_osi_thread: run_thread: thread id 4587, thread name hci_thread exited
,07-26 17:27:27.300  4056  4174 I bt_hci_h4: hal_close
07-26 17:27:27.300  4056  4600 W bt_osi_thread: run_thread: thread id 4600, thread name hci_single_chann exited
07-26 17:27:27.301  4056  4174 I bt_userial_vendor: device fd = 96 close
07-26 17:27:27.302  4056  4174 I bt_upio : upio_set_bluetooth_power(on: 0)
07-26 17:27:27.309  4056  4174 I bt_core_module: module_shut_down Shutdown of module "hci_module" completed
07-26 17:27:27.311  5160  5340 I Authzen : [PermitStore] Getting all permits...
07-26 17:27:27.311  4056  4174 I bt_core_module: module_shut_down Shutting down module "btsnoop_module"
07-26 17:27:27.312  4056  4174 I bt_core_module: module_shut_down Shutdown of module "btsnoop_module" completed
07-26 17:27:27.312  4056  4174 I bt_core_module: module_clean_up Cleaning up module "bte_logmsg_module"
07-26 17:27:27.312  4056  4174 I bt_core_module: module_clean_up Cleanup of module "bte_logmsg_module" completed
07-26 17:27:27.313  4056  4638 W bt_osi_thread: run_thread: thread id 4638, thread name bt_workqueue exited
07-26 17:27:27.315  4056  4169 I bt_core_module: module_shut_down Shutting down module "controller_module"
07-26 17:27:27.315  4056  4169 I bt_core_module: module_shut_down Shutdown of module "controller_module" completed
07-26 17:27:27.317  4056  4174 E BluetoothAdapterState: stateChangeCallback : 0
07-26 17:27:27.320  4056  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
,07-26 17:27:27.333  4056  4056 D BtGatt.DebugUtils: handleDebugAction() action=null
07-26 17:27:27.334  4056  4163 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-26 17:27:27.337  4056  4056 D BtGatt.GattService: Received stop request...Stopping profile...
07-26 17:27:27.337  4056  4056 D BtGatt.GattService: stop()
07-26 17:27:27.337  4056  4056 D BtGatt.GattService: cleanup binder
07-26 17:27:27.337  4056  4056 D BtGatt.AdvertiseManager: advertise clients cleared
07-26 17:27:27.337  4056  4056 D BtGatt.ScanManager: cleanup
07-26 17:27:27.338  3714  4859 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4056 / op:PendingIntent{3d913aa: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
,07-26 17:27:27.342  4056  4056 D BtGatt.ScanManager: cleanup handler
,07-26 17:27:27.346  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:27.346  4056  4056 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
07-26 17:27:27.346  4056  4056 D BtGatt.GattService: notifyProfileServiceStateChanged
,07-26 17:27:27.347  4056  4056 E BluetoothAdapterService: handleMessage() - Message: 1
,07-26 17:27:27.347  4056  4056 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
07-26 17:27:27.347  4056  4056 V BluetoothAdapterState: isTurningOff()=false
07-26 17:27:27.347  4056  4056 V BluetoothAdapterState: isTurningOn()=false
07-26 17:27:27.347  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:27.347  4056  4056 V BluetoothAdapterState: isBleTurningOff()=true
07-26 17:27:27.348  4056  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
07-26 17:27:27.350  4056  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-26 17:27:27.350  4056  4163 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-26 17:27:27.351  3714  3796 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-26 17:27:27.352  4056  4163 D BluetoothAdapterService: Autoconnection is available 
07-26 17:27:27.352  4056  4163 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
07-26 17:27:27.352  4056  4163 I BluetoothAdapterState: Entering OffState
,07-26 17:27:27.362  3714  3796 D BluetoothManagerService: Entering STATE_OFF but mEnabled is true; restarting.
,07-26 17:27:27.364  4056  4056 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-26 17:27:27.364  3714  4546 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{34d6b38: PendingIntentRecord{3f1e711 com.google.android.gms broadcastIntent}}
07-26 17:27:27.364  4056  4056 W BluetoothSdpJni: Cleaning up Bluetooth SDP object
07-26 17:27:27.365  4056  4169 E BluetoothServiceJni: Callback env check fail: env: 0x0, callback: 0xe21b6870
07-26 17:27:27.365  4056  4169 E BluetoothServiceJni: Callback: 'callback_thread_event' is not called on the correct thread
07-26 17:27:27.366  4056  4174 W bt_btif : btif_dm_generic_evt: event=33035
07-26 17:27:27.366  4056  4174 E bt_btif_dm: ### ASSERT : system/bt/btif/src/btif_dm.c line 2983 Callback is NULL (0) ###
07-26 17:27:27.366  4056  4174 W bt_osi_thread: run_thread: thread id 4174, thread name bt_jni_workqueue exited
,07-26 17:27:27.366  3714  3796 E BluetoothManagerService: waitForOnOff time out
07-26 17:27:27.367  4056  4169 I bt_core_module: module_clean_up Cleaning up module "stack_config_module"
07-26 17:27:27.367  4056  4169 I bt_core_module: module_clean_up Cleanup of module "stack_config_module" completed
07-26 17:27:27.367  4056  4169 I bt_core_module: module_clean_up Cleaning up module "interop_module"
07-26 17:27:27.367  4056  4169 I bt_core_module: module_clean_up Cleanup of module "interop_module" completed
07-26 17:27:27.367  4056  4169 I bt_core_module: module_clean_up Cleaning up module "btif_config_module"
,07-26 17:27:27.374  4056  4169 I bt_core_module: module_clean_up Cleanup of module "btif_config_module" completed
,07-26 17:27:27.374  4056  4169 I bt_core_module: module_clean_up Cleaning up module "bt_utils_module"
07-26 17:27:27.374  4056  4169 I bt_core_module: module_clean_up Cleanup of module "bt_utils_module" completed
07-26 17:27:27.374  4056  4169 I bt_core_module: module_clean_up Cleaning up module "osi_module"
07-26 17:27:27.375  4056  4173 D bt_osi_alarm: callback_dispatch Callback thread exited
07-26 17:27:27.375  4056  4173 W bt_osi_thread: run_thread: thread id 4173, thread name alarm_dispatcher exited
07-26 17:27:27.375  4056  4172 W bt_osi_thread: run_thread: thread id 4172, thread name alarm_default_ca exited
07-26 17:27:27.376  4056  4169 I bt_core_module: module_clean_up Cleanup of module "osi_module" completed
,07-26 17:27:27.379  4056  4056 I BluetoothServiceJni: cleanupNative: return from cleanup
07-26 17:27:27.379  4056  4056 D DOWNLOADABLE_DB: cleanup
,07-26 17:27:27.383  4056  4056 I art     : System.exit called, status: 0
,07-26 17:27:27.383  4056  4056 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-26 17:27:27.398  4779  6807 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,07-26 17:27:27.410  3714  4936 I ActivityManager: Process com.android.bluetooth (pid 4056) has died(76,1805)
,07-26 17:27:27.411  3714  4936 D ActivityManager: cleanUpApplicationRecord -- 4056
07-26 17:27:27.411  3714  4936 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
07-26 17:27:27.412  4844  4855 D ForegroundUtils: could not check pending caller
,07-26 17:27:27.572  9888  9983 D BluetoothAdapter: enable()
,07-26 17:27:27.589  3714  4937 W ActivityManager: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-26 17:27:27.591  3714  4937 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-26 17:27:27.591  3714  4937 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-26 17:27:27.591  3714  4937 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-26 17:27:27.591  3714  4937 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-26 17:27:27.591  3714  4937 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-26 17:27:27.591  3714  4937 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-26 17:27:27.591  3714  4937 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-26 17:27:27.591  3714  4937 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-26 17:27:27.591  3714  4937 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-26 17:27:27.591  3714  4937 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-26 17:27:27.594  3714  4937 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-26 17:27:27.596  3714  4937 D SecContentProvider: called from com.thaliproject.thalitest
,07-26 17:27:27.875  3714  3864 D SamsungAlarmManager: Expired : 4
,07-26 17:27:27.876  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T173210, SetElapsed=578379, nowELAPSED=296160
07-26 17:27:27.877  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170726T172800, SetElapsed=328285, nowELAPSED=296161
,07-26 17:27:27.877  3714  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@20e30b1 alarm=Alarm{3fc6e02 type 2 when 296159 android}
,07-26 17:27:27.881  3714  3929 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
07-26 17:27:27.885  4287  4287 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-26 17:27:27.886  4287  4287 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-26 17:27:27.894  3714  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T172742 - CU:1000/CP:3714
07-26 17:27:27.894  3714  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172742, SetElapsed=311172, nowELAPSED=296179
,07-26 17:27:27.899  4287  4287 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-26 17:27:28.100  9888  9983 D BluetoothAdapter: enable()
,07-26 17:27:28.113  3714  4857 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-26 17:27:28.114  3714  4857 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-26 17:27:28.115  3714  4857 D BatteryService: online:4, current avg:-27, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
,07-26 17:27:28.116  3714  3714 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-26 17:27:28.116  3714  3738 W ActivityManager: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-26 17:27:28.118  3714  3738 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-26 17:27:28.118  3714  3738 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-26 17:27:28.118  3714  3738 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-26 17:27:28.118  3714  3738 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-26 17:27:28.118  3714  3738 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-26 17:27:28.118  3714  3738 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-26 17:27:28.118  3714  3738 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-26 17:27:28.118  3714  3738 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-26 17:27:28.118  3714  3738 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-26 17:27:28.119  3714  3738 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-26 17:27:28.122  3714  3738 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-26 17:27:28.123  3714  3738 D SecContentProvider: called from com.thaliproject.thalitest
,07-26 17:27:28.128  3714  3714 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-26 17:27:28.128  3714  3714 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-26 17:27:28.132  3714  3714 D GameManagerService: new battery level: 100
,07-26 17:27:28.136  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-26 17:27:28.136  4068  4068 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-26 17:27:28.143  4068  4068 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-26 17:27:28.152  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-26 17:27:28.159  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
07-26 17:27:28.163  4068  4068 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-26 17:27:28.416  3714  3763 D MountService: getExternalStorageMountMode : 3
07-26 17:27:28.416  3714  3763 D MountService: getExternalStorageMountMode : 3
07-26 17:27:28.416  3714  3763 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 1002, packageName : com.android.bluetooth
,07-26 17:27:28.460 10011 10011 E Zygote  : v2
07-26 17:27:28.460 10011 10011 I libpersona: KNOX_SDCARD checking this for 1002
07-26 17:27:28.460 10011 10011 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:28.462 10011 10011 E Zygote  : accessInfo : 0
,07-26 17:27:28.464  3714  3763 W ActivityManager: Slow operation: 51ms so far, now at startProcess: done updating battery stats
,07-26 17:27:28.465  3714  3763 W ActivityManager: Slow operation: 51ms so far, now at startProcess: building log message
07-26 17:27:28.465  3714  3763 I ActivityManager: Start proc 10011:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
07-26 17:27:28.465  3714  3763 W ActivityManager: Slow operation: 51ms so far, now at startProcess: starting to update pids map
07-26 17:27:28.465  3714  3763 W ActivityManager: Slow operation: 51ms so far, now at startProcess: done updating pids map
07-26 17:27:28.465  3714  3763 W ActivityManager: Slow operation: 53ms so far, now at startProcess: done starting proc!
,07-26 17:27:28.474 10011 10011 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:28.476 10011 10011 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.android.bluetooth 
,07-26 17:27:28.505 10011 10011 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 17:27:28.506 10011 10011 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:28.509  3714  4543 I ActivityManager: DSS on for com.android.bluetooth and scale is 1.0
,07-26 17:27:28.568 10011 10011 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-26 17:27:28.573 10011 10011 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:28.581 10011 10011 I HeadsetProvider: onCreate
,07-26 17:27:28.592 10011 10011 D BtSettings.ProfileConfig: Adding GattService
07-26 17:27:28.592 10011 10011 D BtSettings.ProfileConfig: Adding HeadsetService
07-26 17:27:28.592 10011 10011 D BtSettings.ProfileConfig: Adding A2dpService
07-26 17:27:28.592 10011 10011 D BtSettings.ProfileConfig: Adding HidService
07-26 17:27:28.592 10011 10011 D BtSettings.ProfileConfig: Adding HealthService
07-26 17:27:28.592 10011 10011 D BtSettings.ProfileConfig: Adding PanService
07-26 17:27:28.592 10011 10011 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-26 17:27:28.592 10011 10011 D BtSettings.ProfileConfig: Adding SapService
07-26 17:27:28.593 10011 10011 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-26 17:27:28.593 10011 10011 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-26 17:27:28.593 10011 10011 D BtSettings.ProfileConfig: Adding HidDevService
07-26 17:27:28.593 10011 10011 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-26 17:27:28.600  3714  4900 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-26 17:27:28.602  3714  4900 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:28.604  3714  4900 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-26 17:27:28.606  3714  4900 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:28.609  3714  3918 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-26 17:27:28.611  3714  3918 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:28.614  3714  3946 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-26 17:27:28.615  3714  3946 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:28.619  3714  4542 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-26 17:27:28.620  3714  4542 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:28.623  3714  4938 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-26 17:27:28.625  3714  4938 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:28.626  9888  9983 D BluetoothAdapter: enable()
07-26 17:27:28.628  3714  4543 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-26 17:27:28.629  3714  4543 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:28.632  3714  3909 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-26 17:27:28.633  3714  3909 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:28.635  3714  4541 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-26 17:27:28.635  3714  3923 W ActivityManager: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-26 17:27:28.636  3714  4541 D SecContentProvider: called from android.uid.bluetooth:1002
07-26 17:27:28.636  3714  3923 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-26 17:27:28.636  3714  3923 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-26 17:27:28.636  3714  3923 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-26 17:27:28.636  3714  3923 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-26 17:27:28.636  3714  3923 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-26 17:27:28.636  3714  3923 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-26 17:27:28.636  3714  3923 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-26 17:27:28.636  3714  3923 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-26 17:27:28.636  3714  3923 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-26 17:27:28.636  3714  3923 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-26 17:27:28.638  3714  3923 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-26 17:27:28.638  3714  4857 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-26 17:27:28.639  3714  3923 D SecContentProvider: called from com.thaliproject.thalitest
07-26 17:27:28.640  3714  4857 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:28.642  3714  3738 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-26 17:27:28.643  3714  3738 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:28.726 10011 10011 D BluetoothAdapterState: make() - Creating AdapterState
,07-26 17:27:28.729 10011 10024 I BluetoothAdapterState: Entering OffState
,07-26 17:27:28.732 10011 10026 W bt_osi_thread: run_thread: thread id 10026, thread name stack_manager started
07-26 17:27:28.733 10011 10026 I bt_core_module: module_init Initializing module "osi_module"
07-26 17:27:28.733 10011 10026 I bt_core_module: module_init Initialized module "osi_module"
07-26 17:27:28.733 10011 10026 I bt_core_module: module_init Initializing module "bt_utils_module"
07-26 17:27:28.733 10011 10026 I bt_core_module: module_init Initialized module "bt_utils_module"
07-26 17:27:28.733 10011 10026 I bt_core_module: module_init Initializing module "btif_config_module"
,07-26 17:27:28.735 10011 10029 W bt_osi_thread: run_thread: thread id 10029, thread name alarm_default_ca started
07-26 17:27:28.735 10011 10030 W bt_osi_thread: run_thread: thread id 10030, thread name alarm_dispatcher started
07-26 17:27:28.735 10011 10026 I bt_core_module: module_init Initialized module "btif_config_module"
07-26 17:27:28.735 10011 10026 I bt_core_module: module_init Initializing module "interop_module"
07-26 17:27:28.735 10011 10026 I bt_core_module: module_init Initialized module "interop_module"
07-26 17:27:28.736 10011 10026 I bt_core_module: module_init Initializing module "stack_config_module"
,07-26 17:27:28.737 10011 10026 I bt_core_module: module_init Initialized module "stack_config_module"
,07-26 17:27:28.739 10011 10031 W bt_osi_thread: run_thread: thread id 10031, thread name bt_jni_workqueue started
07-26 17:27:28.739 10011 10011 I bt_osi_wakelock: wakelock_set_os_callouts set to non-native
,07-26 17:27:28.739 10011 10011 W bt_btif : btif_get_adapter_property 2
07-26 17:27:28.739 10011 10011 W bt_btif : btif_get_adapter_property 1
,07-26 17:27:28.742 10011 10031 E BluetoothServiceJni: populateRssiValuesNative
07-26 17:27:28.742 10011 10031 I bt_btif : getModelRssiValues
07-26 17:27:28.742 10011 10031 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
,07-26 17:27:28.743 10011 10011 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-26 17:27:28.745 10011 10011 D BluetoothAdapterService: makeHashMapAvPerformance: Loading from conf
,07-26 17:27:28.760  3714  3796 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,07-26 17:27:28.766 10011 10022 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-26 17:27:28.767 10011 10022 D AdapterProvider: query
07-26 17:27:28.767 10011 10024 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,07-26 17:27:28.775 10011 10024 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-26 17:27:28.775 10011 10024 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-26 17:27:28.776 10011 10024 D BluetoothAdapterService: Autoconnection is available 
07-26 17:27:28.776 10011 10024 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
07-26 17:27:28.777  3714  3796 D BluetoothManagerService: Ble Turning On/Off, G state: 0, S state: 0
,07-26 17:27:28.778 10011 10024 D BluetoothAdapterState: Set Downloadbale DB
07-26 17:27:28.778 10011 10024 D DOWNLOADABLE_DB: initBluetoothDatabase
,07-26 17:27:28.779 10011 10024 D DOWNLOADABLE_DB: initBroadcastReceiver
,07-26 17:27:28.783 10011 10024 D DOWNLOADABLE_DB: cleanupLooper
07-26 17:27:28.783 10011 10024 D DOWNLOADABLE_DB: quit init handler
,07-26 17:27:28.787 10011 10022 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@c0b5a74
,07-26 17:27:28.789 10011 10022 D BluetoothAdapterService: updateEvent - already set, update
,07-26 17:27:28.789 10011 10022 W BluetoothAdapterService: updateEvent - alreadySet is true
07-26 17:27:28.790 10011 10022 D AdapterProvider: update
,07-26 17:27:28.794 10011 10022 E BluetoothAdapterService: updateEvent - update success 1
,07-26 17:27:28.805 10011 10024 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-26 17:27:28.809  3714  4542 D MountService: getExternalStorageMountMode : 1
07-26 17:27:28.809  3714  4542 D MountService: getExternalStorageMountMode : 3
07-26 17:27:28.810  3714  4542 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10135, packageName : com.samsung.android.sm.policy
,07-26 17:27:28.833 10034 10034 E Zygote  : v2
07-26 17:27:28.834 10034 10034 I libpersona: KNOX_SDCARD checking this for 10135
07-26 17:27:28.834 10034 10034 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:28.835 10034 10034 E Zygote  : accessInfo : 0
,07-26 17:27:28.839  3714  4542 I ActivityManager: Start proc 10034:com.samsung.android.sm.policy/u0a135 for content provider com.samsung.android.sm.policy/.db.PolicyClientProvider
,07-26 17:27:28.846 10034 10034 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:28.848 10034 10034 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,07-26 17:27:28.880 10034 10034 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:28.881 10034 10034 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:28.884  3714  4936 I ActivityManager: DSS on for com.samsung.android.sm.policy and scale is 1.0
,07-26 17:27:28.911 10034 10034 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient_N/lib/arm64
,07-26 17:27:28.929 10034 10034 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:28.966 10011 10024 D DOWNLOADABLE_DB: Local DB version is = 20160428 SCPM Client DB version is= 20160428
07-26 17:27:28.966 10011 10024 D DOWNLOADABLE_DB: latest polices have already been updated for BT_HFP
,07-26 17:27:28.985 10011 10024 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-26 17:27:29.004 10011 10024 D DOWNLOADABLE_DB: Local DB version is = 20160617 SCPM Client DB version is= 20160617
07-26 17:27:29.004 10011 10024 D DOWNLOADABLE_DB: latest polices have already been updated for BT_BLE
,07-26 17:27:29.020 10011 10024 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-26 17:27:29.037 10011 10024 D DOWNLOADABLE_DB: Local DB version is = 201612050001 SCPM Client DB version is= 201612050001
07-26 17:27:29.037 10011 10024 D DOWNLOADABLE_DB: latest polices have already been updated for BT_A2DP
,07-26 17:27:29.048 10011 10024 D BluetoothSecureManager: getInstant: null
07-26 17:27:29.048 10011 10024 D BluetoothSecureManager: calling getMethod for getService
,07-26 17:27:29.048 10011 10024 D BluetoothSecureManager: calling getService
,07-26 17:27:29.050 10011 10024 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@bbda9e0
,07-26 17:27:29.052  3714  4939 D BluetoothSecureManagerService: isSecureModeEnabled
07-26 17:27:29.052  3714  4939 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,07-26 17:27:29.053 10011 10024 D BtConfig.SecureMode: isSecureModeOn:false
07-26 17:27:29.053 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-26 17:27:29.055 10011 10024 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-26 17:27:29.055 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-26 17:27:29.056 10011 10024 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-26 17:27:29.056 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-26 17:27:29.057 10011 10024 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-26 17:27:29.058 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-26 17:27:29.059 10011 10024 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-26 17:27:29.059 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-26 17:27:29.060 10011 10024 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-26 17:27:29.060 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-26 17:27:29.061 10011 10024 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-26 17:27:29.061 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-26 17:27:29.062 10011 10024 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,07-26 17:27:29.062 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-26 17:27:29.063 10011 10024 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
07-26 17:27:29.063 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-26 17:27:29.064 10011 10024 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-26 17:27:29.065 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
,07-26 17:27:29.066 10011 10024 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
07-26 17:27:29.066 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-26 17:27:29.067 10011 10024 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidDevService
07-26 17:27:29.068 10011 10024 D BluetoothBondStateMachine: make
,07-26 17:27:29.070 10011 10047 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-26 17:27:29.077 10011 10024 I BluetoothAdapterState: Entering PendingCommandState
,07-26 17:27:29.078 10011 10011 I BtGatt.JNI: classInitNative(L979): classInitNative: Success!
,07-26 17:27:29.085 10011 10011 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-26 17:27:29.086 10011 10011 D BtGatt.GattService: Received start request. Starting profile...
,07-26 17:27:29.086 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:29.086 10011 10011 D BtGatt.GattService: start()
,07-26 17:27:29.088 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:29.088 10011 10011 D BtGatt.AdvertiseManager: advertise manager created
07-26 17:27:29.088 10011 10011 D BtGatt.AdvertiseManager: start
,07-26 17:27:29.093 10011 10011 D BtGatt.ScanManager: start
,07-26 17:27:29.118 10011 10011 D BtGatt.GattService: setGattService(): set to: com.android.bluetooth.gatt.GattService@2d5545b
07-26 17:27:29.119 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
,07-26 17:27:29.119 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:29.119 10011 10011 D BtGatt.GattService: refreshAbusiveScanPackages
,07-26 17:27:29.123  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:29.123  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:27:29.126 10011 10011 D DOWNLOADABLE_DB: getAbuseScanPackages
,07-26 17:27:29.133 10011 10011 D BtGatt.GattService: refreshAbusiveScanValue()
,07-26 17:27:29.134 10011 10011 D DOWNLOADABLE_DB: getAbuseMaxScanCount
,07-26 17:27:29.141 10011 10011 D DOWNLOADABLE_DB: getAbuseAccumulatedScanTime
,07-26 17:27:29.142  4649  4649 D io_stats: !@   8,0 r 26062 2284732 w 5045 204560 d 648 73804 f 2051 2051 iot 11810 10943 th 476096 0 0 pt 0 inp 0 0 297.426
,07-26 17:27:29.144  9888  9983 D BluetoothAdapter: enable()
,07-26 17:27:29.149 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:29.149 10011 10011 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
07-26 17:27:29.149 10011 10011 D BtGatt.GattService: notifyProfileServiceStateChanged
07-26 17:27:29.149 10011 10032 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-26 17:27:29.150 10011 10032 D AdapterProvider: query
07-26 17:27:29.150 10011 10011 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:29.150 10011 10011 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
07-26 17:27:29.150 10011 10011 V BluetoothAdapterState: isTurningOff()=false
07-26 17:27:29.150 10011 10011 V BluetoothAdapterState: isTurningOn()=false
07-26 17:27:29.151 10011 10011 V BluetoothAdapterState: isBleTurningOn()=true
07-26 17:27:29.151 10011 10011 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:29.151 10011 10024 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,07-26 17:27:29.158 10011 10026 I bt_core_module: module_start_up Starting module "btif_config_module"
07-26 17:27:29.158 10011 10026 I bt_core_module: module_start_up Started module "btif_config_module"
07-26 17:27:29.159 10011 10026 I bt_core_module: module_start_up Starting module "btsnoop_module"
,07-26 17:27:29.159 10011 10026 I bt_core_module: module_start_up Started module "btsnoop_module"
,07-26 17:27:29.159 10011 10026 I bt_core_module: module_start_up Starting module "hci_module"
07-26 17:27:29.159 10011 10026 I bt_hci  : start_up
07-26 17:27:29.159 10011 10031 W bt_btif : btif_dm_generic_evt: event=33035
07-26 17:27:29.160 10011 10061 W bt_osi_thread: run_thread: thread id 10061, thread name hci_thread started
,07-26 17:27:29.162 10011 10032 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@7448a4
07-26 17:27:29.163 10011 10032 D BluetoothAdapterService: updateEvent - already set, update
07-26 17:27:29.163 10011 10032 W BluetoothAdapterService: updateEvent - alreadySet is true
07-26 17:27:29.163 10011 10032 D AdapterProvider: update
,07-26 17:27:29.168 10011 10026 I bt_vendor: alloc value 0xce60bd35
,07-26 17:27:29.168 10011 10026 I bt_vendor: init
07-26 17:27:29.168 10011 10026 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-26 17:27:29.168 10011 10026 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-26 17:27:29.168 10011 10026 I bt_upio : upio_set_bluetooth_power(on: 0)
07-26 17:27:29.168 10011 10032 E BluetoothAdapterService: updateEvent - update success 1
,07-26 17:27:29.169 10011 10026 I bt_upio : upio_set_bluetooth_power(on: 1)
,07-26 17:27:29.174  3714  3918 W ActivityManager: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-26 17:27:29.176  3714  3918 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-26 17:27:29.176  3714  3918 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-26 17:27:29.176  3714  3918 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-26 17:27:29.176  3714  3918 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-26 17:27:29.176  3714  3918 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-26 17:27:29.176  3714  3918 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-26 17:27:29.176  3714  3918 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-26 17:27:29.176  3714  3918 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-26 17:27:29.176  3714  3918 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-26 17:27:29.176  3714  3918 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-26 17:27:29.177  3714  3918 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-26 17:27:29.178  3714  3918 D SecContentProvider: called from com.thaliproject.thalitest
,07-26 17:27:29.276 10011 10026 D bt_hci  : start_up starting async portion
,07-26 17:27:29.277 10011 10061 I bt_hci  : event_finish_startup
07-26 17:27:29.277 10011 10061 I bt_hci_h4: hal_open
07-26 17:27:29.278 10011 10061 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,07-26 17:27:29.280 10011 10061 I bt_userial_vendor: userial_vendor_open():UART is setup
07-26 17:27:29.280 10011 10061 I bt_userial_vendor: device fd = 85 open
,07-26 17:27:29.281 10011 10064 W bt_osi_thread: run_thread: thread id 10064, thread name hci_single_chann started
07-26 17:27:29.282 10011 10061 E bt_hwcfg: Start CFG HW, HCI reset
,07-26 17:27:29.287 10011 10061 E bt_hwcfg: Read Local Name after HCI reset
,07-26 17:27:29.312 10011 10061 D bt_hwcfg: Chipset BCM4359C0
07-26 17:27:29.313 10011 10061 D bt_hwcfg: Target name = [BCM4359C0]
07-26 17:27:29.313 10011 10061 I bt_hwcfg: module_type[semco_b90s_c0].
,07-26 17:27:29.314 10011 10061 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
07-26 17:27:29.314 10011 10061 E bt_hwcfg: ORG patchram base 0092
07-26 17:27:29.314 10011 10061 E bt_hwcfg: ORG patchram minor 0143
07-26 17:27:29.314 10011 10061 E bt_hwcfg: fw ver (org)92.143
07-26 17:27:29.314 10011 10061 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
,07-26 17:27:29.328 10011 10061 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-26 17:27:29.332 10011 10061 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,07-26 17:27:29.684  9888  9983 D BluetoothAdapter: enable()
,07-26 17:27:29.695 10011 10032 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,07-26 17:27:29.696 10011 10032 D AdapterProvider: query
,07-26 17:27:29.712 10011 10032 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@6a7f3d3
,07-26 17:27:29.715 10011 10032 D BluetoothAdapterService: updateEvent - already set, update
,07-26 17:27:29.719 10011 10032 W BluetoothAdapterService: updateEvent - alreadySet is true
07-26 17:27:29.719 10011 10032 D AdapterProvider: update
,07-26 17:27:29.724 10011 10032 E BluetoothAdapterService: updateEvent - update success 1
,07-26 17:27:29.733  3714  4939 W ActivityManager: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-26 17:27:29.734  3714  4939 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-26 17:27:29.734  3714  4939 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-26 17:27:29.734  3714  4939 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-26 17:27:29.734  3714  4939 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-26 17:27:29.734  3714  4939 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-26 17:27:29.734  3714  4939 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-26 17:27:29.734  3714  4939 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-26 17:27:29.734  3714  4939 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-26 17:27:29.734  3714  4939 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-26 17:27:29.734  3714  4939 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-26 17:27:29.736  3714  4939 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-26 17:27:29.738  3714  4939 D SecContentProvider: called from com.thaliproject.thalitest
,07-26 17:27:29.899 10011 10061 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-26 17:27:29.899 10011 10061 I bt_hwcfg: FW Download delta = 612095
07-26 17:27:29.899 10011 10061 D bt_hwcfg: Settlement delay -- 100 ms
07-26 17:27:29.900 10011 10061 I bt_hwcfg: Setting fw settlement delay to 100 
,07-26 17:27:30.025 10011 10061 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,07-26 17:27:30.129 10011 10061 I bt_hwcfg: vendor lib fwcfg completed
07-26 17:27:30.129 10011 10061 I bt_vendor: firmware callback
07-26 17:27:30.129 10011 10061 I bt_hci  : firmware_config_callback
07-26 17:27:30.130 10011 10026 I bt_core_module: module_start_up Started module "hci_module"
,07-26 17:27:30.131 10011 10065 W bt_osi_thread: run_thread: thread id 10065, thread name bt_workqueue started
,07-26 17:27:30.134 10011 10065 I bt_core_module: module_init Initializing module "bte_logmsg_module"
07-26 17:27:30.134 10011 10065 I bt_core_module: module_init Initialized module "bte_logmsg_module"
,07-26 17:27:30.135 10011 10031 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-26 17:27:30.140  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 10011
07-26 17:27:30.140  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
07-26 17:27:30.141 10011 10031 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-26 17:27:30.141 10011 10031 W bt_btif : get_secure_storage_key - ss_is_supported = 1
07-26 17:27:30.141 10011 10031 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
07-26 17:27:30.141 10011 10031 W bt_btif : btif_dm_generic_evt: event=33035
07-26 17:27:30.141  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,07-26 17:27:30.144 10011 10031 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-26 17:27:30.144  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 10011
07-26 17:27:30.144  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,07-26 17:27:30.241  9888  9983 D BluetoothAdapter: enable()
,07-26 17:27:30.245 10011 10032 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-26 17:27:30.246 10011 10032 D AdapterProvider: query
,07-26 17:27:30.260 10011 10032 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@d9800e
,07-26 17:27:30.262 10011 10032 D BluetoothAdapterService: updateEvent - already set, update
,07-26 17:27:30.263 10011 10032 W BluetoothAdapterService: updateEvent - alreadySet is true
07-26 17:27:30.263 10011 10032 D AdapterProvider: update
,07-26 17:27:30.269 10011 10032 E BluetoothAdapterService: updateEvent - update success 1
,07-26 17:27:30.278  3714  4543 W ActivityManager: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-26 17:27:30.279  3714  4543 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-26 17:27:30.279  3714  4543 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-26 17:27:30.279  3714  4543 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-26 17:27:30.279  3714  4543 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-26 17:27:30.279  3714  4543 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-26 17:27:30.279  3714  4543 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-26 17:27:30.279  3714  4543 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-26 17:27:30.279  3714  4543 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-26 17:27:30.279  3714  4543 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-26 17:27:30.279  3714  4543 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-26 17:27:30.281  3714  4543 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-26 17:27:30.282  3714  4543 D SecContentProvider: called from com.thaliproject.thalitest
,07-26 17:27:30.383  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,07-26 17:27:30.384 10011 10031 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,07-26 17:27:30.386 10011 10066 W bt_osi_thread: run_thread: thread id 10066, thread name module_wrapper started
07-26 17:27:30.387 10011 10066 I bt_core_module: module_start_up Starting module "controller_module"
,07-26 17:27:30.498 10011 10066 I bt_core_module: module_start_up Started module "controller_module"
07-26 17:27:30.498 10011 10066 W bt_osi_thread: run_thread: thread id 10066, thread name module_wrapper exited
,07-26 17:27:30.530 10011 10031 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
,07-26 17:27:30.539 10011 10031 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
07-26 17:27:30.539 10011 10031 W bt_btif : btif_dm_generic_evt: event=33035
,07-26 17:27:30.542 10011 10031 D bt_hci  : do_postload posting postload work item
07-26 17:27:30.542 10011 10061 I bt_hci  : event_postload
07-26 17:27:30.542 10011 10031 E bt_btif_sock: btif_sock_init: !vhci_init
07-26 17:27:30.543 10011 10061 D bt_hwcfg: hw_sco_config
07-26 17:27:30.543 10011 10031 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:227 ##
07-26 17:27:30.543 10011 10061 I bt_hwcfg: I2SPCM config {0x1, 0x0, 0x0, 0x1}
,07-26 17:27:30.543 10011 10061 I bt_vendor: sco_config_cb
07-26 17:27:30.543 10011 10061 I bt_hci  : sco_config_callback postload finished.
,07-26 17:27:30.547 10011 10031 I         : iop_db_open: iop_db_open status 0
,07-26 17:27:30.548 10011 10031 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
07-26 17:27:30.548 10011 10031 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
07-26 17:27:30.549 10011 10031 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
07-26 17:27:30.549 10011 10031 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Grace SWB-B90S eLNA-0092
07-26 17:27:30.549 10011 10031 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0092.0143_semco.hcd
07-26 17:27:30.549 10011 10031 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
07-26 17:27:30.549 10011 10031 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = true
07-26 17:27:30.550 10011 10031 E BluetoothAdapterState: stateChangeCallback : 1
07-26 17:27:30.551 10011 10024 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
,07-26 17:27:30.555 10011 10024 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:30.555 10011 10024 D DOWNLOADABLE_DB: refreshDbFile
07-26 17:27:30.555 10011 10024 D BluetoothServiceJni: refreshDownloadableDbFileNative:
07-26 17:27:30.555 10011 10024 I bt_btif : refreshDownloadableDbFile
,07-26 17:27:30.558 10011 10061 I bt_hwcfg: SCO PCM configure {0x0, 0x1, 0x0, 0x0, 0x0}
,07-26 17:27:30.559 10011 10061 I bt_vendor: low_power_mode_cb
,07-26 17:27:30.560 10011 10024 I         : iop_db_open: iop_db_open status 0
07-26 17:27:30.560 10011 10024 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-26 17:27:30.560 10011 10024 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-26 17:27:30.570 10011 10024 D BluetoothAdapterService: Autoconnection is available 
07-26 17:27:30.570 10011 10024 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
07-26 17:27:30.570 10011 10024 I BluetoothAdapterState: Entering BleOnState
,07-26 17:27:30.577  3714  3796 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
07-26 17:27:30.579  3714  3796 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-26 17:27:30.579  3714  3796 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:30.581 10011 10022 E BluetoothBondStateMachine: initStateMachine
07-26 17:27:30.581 10011 10024 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,07-26 17:27:30.583 10011 10024 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-26 17:27:30.583 10011 10024 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-26 17:27:30.584  3714  3796 D BluetoothManagerService: Turning On/Off, G state: 0, S state: 0, mBLE count: 0, s BLE count: 0
,07-26 17:27:30.586 10011 10024 D BluetoothAdapterService: Autoconnection is available 
07-26 17:27:30.586 10011 10024 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
07-26 17:27:30.586 10011 10024 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-26 17:27:30.586 10011 10024 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
07-26 17:27:30.587 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-26 17:27:30.593  3714  3714 D BluetoothPhoneService: Bluetooth Adapter state : 11
,07-26 17:27:30.593  4068  4284 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,07-26 17:27:30.596  3714  3714 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-26 17:27:30.596  4068  4284 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
07-26 17:27:30.596  3714  3714 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:30.596  3714  3714 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-26 17:27:30.608  9173  9173 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,07-26 17:27:30.608  9173  9173 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-26 17:27:30.614  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:30.623 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-26 17:27:30.626  3714  3738 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{c68c344: PendingIntentRecord{eb20c2d com.google.android.gms broadcastIntent}}
07-26 17:27:30.644 10011 10011 D HeadsetService: Received start request. Starting profile...
07-26 17:27:30.644 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:30.650 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-26 17:27:30.656 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-26 17:27:30.662 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-26 17:27:30.669 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-26 17:27:30.670 10011 10011 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
,07-26 17:27:30.673 10011 10011 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-26 17:27:30.673 10011 10011 D HeadsetStateMachine: make
,07-26 17:27:30.675 10011 10011 E HeadsetStateMachine: # of Max HF connection is 3
,07-26 17:27:30.678 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-26 17:27:30.687 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-26 17:27:30.687 10011 10024 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-26 17:27:30.687 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
,07-26 17:27:30.688 10011 10024 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
,07-26 17:27:30.689 10011 10024 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-26 17:27:30.696 10011 10024 I BluetoothAdapterState: Entering PendingCommandState
,07-26 17:27:30.710 10011 10011 I DualScoManager: Instantiating Dual Sco Manager
07-26 17:27:30.710 10011 10011 I DualScoManager: Set HeadsetServiceHelper
07-26 17:27:30.710 10011 10011 I DualScoManager: setNotificationManager
07-26 17:27:30.710 10011 10011 I DualScoManager: setAudioManager
07-26 17:27:30.711 10011 10011 D BluetoothAtMessage: createCMTIContentObservers
,07-26 17:27:30.717 10011 10011 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@7ac08be
,07-26 17:27:30.719 10011 10011 I HeadsetService: getHeadsetDB(true) - 44:78:3E:94:4A:XX, 300, 1
,07-26 17:27:30.719 10011 10011 I DualScoManager: setSystemAudioInbandSupported : true
07-26 17:27:30.720 10011 10011 I HeadsetStateMachine: isAutoAppInstalled : false
07-26 17:27:30.720 10011 10011 I HeadsetStateMachine: IBR : true (SysA : 1 / DB : 1)
,07-26 17:27:30.721 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
,07-26 17:27:30.722 10011 10011 D DOWNLOADABLE_DB: getNotAllowedVoiceRecognitionDeviceList
,07-26 17:27:30.726 10011 10068 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,07-26 17:27:30.729 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:30.729 10011 10011 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
07-26 17:27:30.729 10011 10011 D HeadsetService: notifyProfileServiceStateChanged
,07-26 17:27:30.730 10011 10061 I bt_hwcfg: SCO PCM data format {0x0, 0x0, 0x3, 0x0, 0x0}
07-26 17:27:30.731 10011 10011 D A2dpService: Received start request. Starting profile...
07-26 17:27:30.731 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:30.732 10011 10068 D HeadsetStateMachine: Clear mHeadsetBrsf
07-26 17:27:30.732 10011 10011 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-26 17:27:30.732 10011 10068 D HeadsetStateMachine: map size, before remove : 0
07-26 17:27:30.732 10011 10068 D HeadsetStateMachine: map size, after remove: 0
07-26 17:27:30.732 10011 10068 D HeadsetStateMachine: connectNextConnectingDevice(false) : null
,07-26 17:27:30.733 10011 10061 I bt_hwcfg: sco I2S/PCM config result 0 [0-Success, 1-Fail]
07-26 17:27:30.733 10011 10061 I bt_vendor: sco_audiostate_cb(status: 0)
,07-26 17:27:30.738 10011 10011 I Avrcp   : No of Audio players :: 1
07-26 17:27:30.738 10011 10011 I Avrcp   : App Package name is GM
,07-26 17:27:30.747 10011 10011 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,07-26 17:27:30.748 10011 10011 I Avrcp   : No of Video players :: 2
07-26 17:27:30.748 10011 10011 I Avrcp   : Video App Package name is VP
,07-26 17:27:30.752 10011 10011 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-26 17:27:30.752 10011 10011 I Avrcp   : Video App Package name is others
,07-26 17:27:30.758 10011 10011 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-26 17:27:30.758 10011 10011 I Avrcp   : Add tempPlayer
07-26 17:27:30.758 10011 10011 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-26 17:27:30.758 10011 10011 V Avrcp   : no_of_players : 4
07-26 17:27:30.758 10011 10011 I Avrcp   : Total no of players: 4
07-26 17:27:30.758 10011 10011 V Avrcp   : Samsung player is the 1st player
,07-26 17:27:30.758 10011 10011 D Avrcp   : Compose Browsing Service Candidate
,07-26 17:27:30.760 10011 10011 D Avrcp   : ResolveInfo info ResolveInfo{cb42f58 com.android.bluetooth/.a2dpsink.mbs.A2dpMediaBrowserService m=0x108000}
07-26 17:27:30.760 10011 10011 D Avrcp   : ResolveInfo info ResolveInfo{53528b1 com.google.android.music/.browse.MediaBrowserService m=0x108000}
07-26 17:27:30.760 10011 10011 D Avrcp   : Initialize Media Controller
,07-26 17:27:30.761 10011 10011 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,07-26 17:27:30.764 10011 10011 E Avrcp   : getActiveSessions
07-26 17:27:30.764 10011 10011 D Avrcp   : pick active media Controller
07-26 17:27:30.764 10011 10011 D Avrcp   : Get the active Media Controller 
,07-26 17:27:30.765 10011 10011 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-26 17:27:30.765 10011 10011 D A2dpStateMachine: make
,07-26 17:27:30.766 10011 10071 W bt_osi_thread: run_thread: thread id 10071, thread name media_worker started
07-26 17:27:30.766 10011 10011 E bt_btif : warning : media task started media_task_refcnt 1 
07-26 17:27:30.766 10011 10011 W bt_btif : btif_ar_init
07-26 17:27:30.767 10011 10031 W bt_btif : av start inhibit off
,07-26 17:27:30.768 10011 10011 E A2dpStateMachine: isDualPlayEnabled : Dual Play not supported
07-26 17:27:30.768 10011 10070 D A2dpStateMachine: Enter Disconnected: -2
,07-26 17:27:30.769 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
,07-26 17:27:30.769 10011 10011 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
07-26 17:27:30.770 10011 10011 D A2dpService: notifyProfileServiceStateChanged
,07-26 17:27:30.770 10011 10011 I BluetoothHidServiceJni: classInitNative: succeeds
,07-26 17:27:30.772 10011 10011 D HidService: Received start request. Starting profile...
07-26 17:27:30.772 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:30.773 10011 10011 D HidService: setHidService(): set to: null
07-26 17:27:30.773 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:30.773 10011 10011 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
07-26 17:27:30.773 10011 10011 D HidService: notifyProfileServiceStateChanged
,07-26 17:27:30.773 10011 10011 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-26 17:27:30.775 10011 10011 D HealthService: Received start request. Starting profile...
07-26 17:27:30.775 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
,07-26 17:27:30.776  9173  9173 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:30.776  9173  9173 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
07-26 17:27:30.777 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
,07-26 17:27:30.777 10011 10011 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
07-26 17:27:30.777 10011 10011 D HealthService: notifyProfileServiceStateChanged
,07-26 17:27:30.777 10011 10011 I BluetoothPanServiceJni: classInitNative(L139): succeeds
,07-26 17:27:30.779 10011 10011 D PanService: Received start request. Starting profile...
07-26 17:27:30.780 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:30.780 10011 10011 D BluetoothPanServiceJni: initializeNative(L144): pan
,07-26 17:27:30.786  9888  9983 D BluetoothAdapter: enable()
,07-26 17:27:30.791 10011 10022 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,07-26 17:27:30.791 10011 10022 D AdapterProvider: query
,07-26 17:27:30.798 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:30.798 10011 10011 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
07-26 17:27:30.798 10011 10011 D PanService: notifyProfileServiceStateChanged
07-26 17:27:30.799 10011 10022 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@55a9b34
07-26 17:27:30.800 10011 10022 D BluetoothAdapterService: updateEvent - already set, update
,07-26 17:27:30.801 10011 10011 D BluetoothMapService: Received start request. Starting profile...
07-26 17:27:30.801 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
,07-26 17:27:30.801 10011 10022 W BluetoothAdapterService: updateEvent - alreadySet is true
,07-26 17:27:30.801 10011 10022 D AdapterProvider: update
07-26 17:27:30.806 10011 10022 E BluetoothAdapterService: updateEvent - update success 1
,07-26 17:27:30.814 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:30.814 10011 10011 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
07-26 17:27:30.815 10011 10011 D BluetoothMapService: notifyProfileServiceStateChanged
07-26 17:27:30.819 10011 10011 V SapService: SapBinder()
07-26 17:27:30.820 10011 10011 D SapService: Received start request. Starting profile...
07-26 17:27:30.820 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:30.820 10011 10011 V SapService: start()
07-26 17:27:30.820 10011 10011 D SapService: Disable sap : false
,07-26 17:27:30.979  3714  4859 W ActivityManager: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-26 17:27:30.981  3714  4859 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-26 17:27:30.981  3714  4859 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9888, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-26 17:27:30.981  3714  4859 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-26 17:27:30.981  3714  4859 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-26 17:27:30.981  3714  4859 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-26 17:27:30.981  3714  4859 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-26 17:27:30.981  3714  4859 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-26 17:27:30.981  3714  4859 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-26 17:27:30.981  3714  4859 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
,07-26 17:27:30.981  3714  4859 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
07-26 17:27:30.983 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:30.983 10011 10011 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
07-26 17:27:30.983 10011 10011 D SapService: notifyProfileServiceStateChanged
07-26 17:27:30.986  3714  4859 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-26 17:27:30.989  3714  4859 D SecContentProvider: called from com.thaliproject.thalitest
07-26 17:27:31.007 10011 10011 V BluetoothHidDevServiceJni: classInitNative: done
07-26 17:27:31.014 10011 10011 D HidDevService: Received start request. Starting profile...
07-26 17:27:31.015 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:31.015 10011 10011 D HidDevService: start()
07-26 17:27:31.015 10011 10011 V BluetoothHidDevServiceJni: initNative enter
07-26 17:27:31.015 10011 10011 V BluetoothHidDevServiceJni: initNative done
07-26 17:27:31.015 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:31.015 10011 10011 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Message sending
07-26 17:27:31.015 10011 10011 D HidDevService: notifyProfileServiceStateChanged
07-26 17:27:31.019 10011 10011 D HeadsetStateMachine: Proxy object connected
07-26 17:27:31.020 10011 10011 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:31.020 10011 10011 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
07-26 17:27:31.020 10011 10011 V BluetoothAdapterState: isTurningOff()=false
07-26 17:27:31.020 10011 10011 V BluetoothAdapterState: isTurningOn()=true
07-26 17:27:31.020 10011 10011 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:31.021 10011 10011 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:31.028 10011 10011 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-26 17:27:31.028 10011 10011 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:31.028 10011 10068 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-26 17:27:31.028 10011 10011 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
07-26 17:27:31.029 10011 10011 V BluetoothAdapterState: isTurningOff()=false
07-26 17:27:31.029 10011 10011 V BluetoothAdapterState: isTurningOn()=true
07-26 17:27:31.029 10011 10011 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:31.029 10011 10011 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:31.029 10011 10068 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-26 17:27:31.029 10011 10011 D A2dpService: A2dpService - WIFI_STATE_ENABLED
07-26 17:27:31.029 10011 10011 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:31.029 10011 10011 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
07-26 17:27:31.029 10011 10011 V BluetoothAdapterState: isTurningOff()=false
07-26 17:27:31.029 10011 10011 V BluetoothAdapterState: isTurningOn()=true
07-26 17:27:31.029 10011 10068 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-26 17:27:31.029 10011 10011 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:31.029 10011 10011 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:31.029 10011 10068 E HeadsetStateMachine: Unknown message: 11
07-26 17:27:31.029 10011 10011 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:31.030 10011 100,11 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
07-26 17:27:31.030 10011 10011 V BluetoothAdapterState: isTurningOff()=false
07-26 17:27:31.030 10011 10011 V BluetoothAdapterState: isTurningOn()=true
07-26 17:27:31.030 10011 10011 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:31.030 10011 10011 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:31.035 10011 10011 D BluetoothUtils: readSalesCode :: sales code is XEO
07-26 17:27:31.035 10011 10011 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:31.035 10011 10011 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
07-26 17:27:31.035 10011 10011 V BluetoothAdapterState: isTurningOff()=false
07-26 17:27:31.035 10011 10011 V BluetoothAdapterState: isTurningOn()=true
07-26 17:27:31.035 10011 10011 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:31.035 10011 10011 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:31.035 10011 10011 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:31.036 10011 10011 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
07-26 17:27:31.036 10011 10011 V BluetoothAdapterState: isTurningOff()=false
07-26 17:27:31.036 10011 10011 V BluetoothAdapterState: isTurningOn()=true
07-26 17:27:31.036 10011 10011 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:31.036 10011 10011 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 17:27:31.042 10011 10011 E BluetoothAdapterService: handleMessage() - Message: 1
,07-26 17:27:31.042 10011 10011 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
07-26 17:27:31.043 10011 10011 V BluetoothAdapterState: isTurningOff()=false
07-26 17:27:31.043 10011 10011 V BluetoothAdapterState: isTurningOn()=true
07-26 17:27:31.043 10011 10011 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:31.043 10011 10011 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:31.043 10011 10011 E BluetoothAdapterService: handleMessage() - Message: 1
07-26 17:27:31.043 10011 10011 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Before synchronized
07-26 17:27:31.043 10011 10011 V BluetoothAdapterState: isTurningOff()=false
07-26 17:27:31.044 10011 10011 V BluetoothAdapterState: isTurningOn()=true
07-26 17:27:31.045 10011 10011 V BluetoothAdapterState: isBleTurningOn()=false
07-26 17:27:31.045 10011 10011 V BluetoothAdapterState: isBleTurningOff()=false
07-26 17:27:31.046 10011 10011 I BluetoothA2dpServiceJni: Attempting to set busy level
07-26 17:27:31.048 10011 10024 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,07-26 17:27:31.052 10011 10024 E BluetoothServiceJni: enableBrEdrNative:
07-26 17:27:31.052 10011 10024 I bt_btif : enable_bredr
07-26 17:27:31.052 10011 10031 W bt_btif : btif_dm_generic_evt: event=33035
,07-26 17:27:31.055 10011 10031 W bt_btif : btif_dm_generic_evt: event=33035
,07-26 17:27:31.058 10011 10031 W bt_btif : IsSoftphone: 
,07-26 17:27:31.058 10011 10031 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
,07-26 17:27:31.058 10011 10031 W bt_btif : btif_dm_generic_evt: event=33035
,07-26 17:27:31.058 10011 10065 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
,07-26 17:27:31.063 10011 10031 E BluetoothServiceJni: populateRssiValuesNative
07-26 17:27:31.063 10011 10031 I bt_btif : getModelRssiValues
07-26 17:27:31.063 10011 10031 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
07-26 17:27:31.067 10011 10065 D CODEC_IF_MOD: codec_open: codec_open
07-26 17:27:31.068 10011 10065 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
07-26 17:27:31.068 10011 10065 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
07-26 17:27:31.068 10011 10065 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
07-26 17:27:31.068 10011 10065 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-26 17:27:31.068 10011 10065 D CODEC_IF: codec_if_close: codec_if_close hdl -599887868
07-26 17:27:31.068 10011 10065 D CODEC_IF_MOD: codec_close: codec_close
07-26 17:27:31.068 10011 10065 D CODEC_IF_MOD: codec_close: freed apt-x encoder
07-26 17:27:31.068 10011 10065 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
07-26 17:27:31.068 10011 10065 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,07-26 17:27:31.078 10011 10065 D CODEC_IF_SSHD: codec_open: codec_open
07-26 17:27:31.078 10011 10065 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
07-26 17:27:31.078 10011 10065 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
07-26 17:27:31.078 10011 10065 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-26 17:27:31.078 10011 10065 D CODEC_IF: codec_if_close: codec_if_close hdl -876614272
07-26 17:27:31.078 10011 10065 D CODEC_IF_SSHD: codec_close: codec_close
07-26 17:27:31.078 10011 10065 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
07-26 17:27:31.078 10011 10065 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
07-26 17:27:31.078 10011 10065 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
,07-26 17:27:31.082  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:31.085 10011 10031 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-26 17:27:31.086 10011 10031 E bt_btif : btif_handle_bluetooth_enable_evt
07-26 17:27:31.086 10011 10031 E bt_btif : ANT+ socket does not initialize.
,07-26 17:27:31.088 10011 10084 W bt_osi_thread: run_thread: thread id 10084, thread name btif_sock started
,07-26 17:27:31.089 10011 10031 E BluetoothAdapterState: stateChangeCallback : 17
07-26 17:27:31.089 10011 10031 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
07-26 17:27:31.090 10011 10024 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
07-26 17:27:31.090 10011 10065 D CODEC_IF_SSHD2: codec_open: codec_open
07-26 17:27:31.090 10011 10065 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
,07-26 17:27:31.090 10011 10065 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
07-26 17:27:31.090 10011 10065 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-26 17:27:31.090 10011 10065 D CODEC_IF: codec_if_close: codec_if_close hdl -846434304
07-26 17:27:31.090 10011 10065 D CODEC_IF_SSHD2: codec_close: codec_close
07-26 17:27:31.090 10011 10065 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
07-26 17:27:31.091 10011 10065 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
07-26 17:27:31.092 10011 10024 D BluetoothAdapterProperties: ScanMode =  20
07-26 17:27:31.092 10011 10024 D BluetoothAdapterProperties: State =  11
07-26 17:27:31.092 10011 10065 D CODEC_IF_MOD: codec_open: codec_open
07-26 17:27:31.092 10011 10065 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
07-26 17:27:31.092 10011 10065 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
07-26 17:27:31.092 10011 10065 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
07-26 17:27:31.092 10011 10065 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-26 17:27:31.092 10011 10065 D CODEC_IF: codec_if_close: codec_if_close hdl -599887868
07-26 17:27:31.092 10011 10065 D CODEC_IF_MOD: codec_close: codec_close
07-26 17:27:31.092 10011 10065 D CODEC_IF_MOD: codec_close: freed apt-x encoder
07-26 17:27:31.092 10011 10065 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
07-26 17:27:31.092 10011 10065 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
07-26 17:27:31.095 10011 10065 D CODEC_IF_SSHD: codec_open: codec_open
07-26 17:27:31.095 10011 10065 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
07-26 17:27:31.095 10011 10065 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
07-26 17:27:31.095 10011 10065 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-26 17:27:31.095 10011 10065 D CODEC_IF: codec_if_close: codec_if_close hdl -876614272
07-26 17:27:31.095 10011 10065 D CODEC_IF_SSHD: codec_close: codec_close
07-26 17:27:31.095 10011 10065 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
07-26 17:27:31.095 10011 10065 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
07-26 17:27:31.095 10011 10065 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
07-26 17:27:31.095  3714  3738 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
07-26 17:27:31.095 10011 10031 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
07-26 17:27:31.095 10011 10031 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
07-26 17:27:31.095 10011 10031 E bt_btif : no av control block available at state:3
07-26 17:27:31.095 10011 10031 E bt_btif : no av control block available at state:3
07-26 17:27:31.095 10011 10031 E bt_btif : no av control block available at state:2
07-26 17:27:31.096 10011 10031 E bt_btif : warning : no command pending, ignore ack
07-26 17:27:31.096 10011 10031 E bt_btif : no av control block available at state:3
07-26 17:27:31.096 10011 10031 E bt_btif : no av control block available at state:2
07-26 17:27:31.096 10011 10031 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
07-26 17:27:31.096 10011 10071 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
07-26 17:27:31.096 10011 10071 E bt_btif : warning : no command pending, ignore ack
07-26 17:27:31.096 10011 10065 D CODEC_IF_SSHD2: codec_open: codec_open
,07-26 17:27:31.097 10011 10065 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
07-26 17:27:31.097  3714  3738 D SecContentProvider: called from android.uid.bluetooth:1002
,07-26 17:27:31.098 10011 10065 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
07-26 17:27:31.098 10011 10065 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-26 17:27:31.098 10011 10065 D CODEC_IF: codec_if_close: codec_if_close hdl -846434304
07-26 17:27:31.098 10011 10065 D CODEC_IF_SSHD2: codec_close: codec_close
07-26 17:27:31.098 10011 10065 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
07-26 17:27:31.099  3714  4859 D SecContentProvider: insert(), uri = 2
07-26 17:27:31.100  3714  4859 D SecContentProvider: called from android.uid.bluetooth:1002
07-26 17:27:31.100 10011 10031 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
07-26 17:27:31.100 10011 10031 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
07-26 17:27:31.100 10011 10031 E bt_btif : no av control block available at state:3
07-26 17:27:31.100 10011 10031 E bt_btif : no av control block available at state:3
07-26 17:27:31.100 10011 10031 E bt_btif : BTA got event 0x1716
07-26 17:27:31.100 10011 10031 E bt_btif : warning : no command pending, ignore ack
07-26 17:27:31.100 10011 10031 E bt_btif : no av control block available at state:3
07-26 17:27:31.100 10011 10031 E bt_btif : no av control block available at state:2
07-26 17:27:31.100 10011 10071 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
07-26 17:27:31.100 10011 10031 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
07-26 17:27:31.100 10011 10071 E bt_btif : warning : no command pending, ignore ack
07-26 17:27:31.103 10011 10024 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-26 17:27:31.104 10011 10024 D BluetoothAdapterService: [VendorCapa] prevState: 11, newState: 12
07-26 17:27:31.107  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
07-26 17:27:31.109 10011 10024 I bt_btif : vsc_getvendorcapabilities
07-26 17:27:31.110 10011 10024 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-26 17:27:31.110 10011 10031 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-26 17:27:31.110  9888  9888 D BluetoothAdapter: STATE_ON
07-26 17:27:31.110 10011 10031 D BluetoothPanServiceJni: control_state_callback(L64): state:0, local_role:3, ifname:bt-pan
07-26 17:27:31.111  9888  9888 D BluetoothAdapter: STATE_ON
07-26 17:27:31.116  9888  9888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,07-26 17:27:31.121  9888  9888 D BluetoothAdapter: STATE_ON
07-26 17:27:31.122  9888  9888 D BluetoothAdapter: STATE_ON
07-26 17:27:31.122 10011 10024 D BluetoothAdapterService: Autoconnection is available 
07-26 17:27:31.122 10011 10024 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-26 17:27:31.122 10011 10024 D BluetoothAdapterService: starting service from this receiver
07-26 17:27:31.124  4068  4549 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-26 17:27:31.125  9888  9888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
07-26 17:27:31.136  9888  9888 D BluetoothAdapter: STATE_ON
07-26 17:27:31.139  3714  3796 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-26 17:27:31.140  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 17:27:31.140  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:31.140  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:31.140  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:27:31.140  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:27:31.140  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-26 17:27:31.140  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-26 17:27:31.140  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 17:27:31.140  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 17:27:31.141  9888  9900 D BluetoothAdapter: onBluetoothStateChange: up=true
07-26 17:27:31.141  9888  9900 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-26 17:27:31.143  9888  9888 D BluetoothAdapter: STATE_ON
07-26 17:27:31.148  9888  9888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
07-26 17:27:31.150 10011 10024 I BluetoothAdapterState: Entering OnState
07-26 17:27:31.154 10011 10011 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
07-26 17:27:31.163  4068  4082 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-26 17:27:31.163  4779  6807 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,07-26 17:27:31.168  4779  8131 D BluetoothAdapter: onBluetoothStateChange: up=true
07-26 17:27:31.168  4779  8131 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-26 17:27:31.174  9173  9185 D BluetoothAdapter: onBluetoothStateChange: up=true
07-26 17:27:31.174  9173  9185 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-26 17:27:31.175  4844  4856 D BluetoothAdapter: onBluetoothStateChange: up=true
07-26 17:27:31.175  4844  4856 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-26 17:27:31.176 10011 10032 D BluetoothAdapter: onBluetoothStateChange: up=true
07-26 17:27:31.176 10011 10032 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-26 17:27:31.177  9503  9515 D BluetoothAdapter: onBluetoothStateChange: up=true
07-26 17:27:31.177  9503  9515 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-26 17:27:31.178  4068  4361 D BluetoothMap: onBluetoothStateChange: up=true
07-26 17:27:31.179  4068  4068 D A2dpProfile: Bluetooth service connected
,07-26 17:27:31.181 10011 10011 I BluetoothPbapService: Handler(): got msg=1
,07-26 17:27:31.183 10011 10086 V BluetoothPbapService: PBAP Service initSocket try: 0
07-26 17:27:31.186 10011 10033 D A2dpStateMachine: getConnectedDevices : size=0
07-26 17:27:31.187 10011 10022 D A2dpStateMachine: getConnectedDevices : size=0
07-26 17:27:31.187  4043  4054 D BluetoothAdapter: onBluetoothStateChange: up=true
07-26 17:27:31.187  4043  4054 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-26 17:27:31.188  4068  4068 D BluetoothMap: Proxy object connected
,07-26 17:27:31.188  4068  4068 D MapProfile: Bluetooth service connected
07-26 17:27:31.188  4068  4068 D BluetoothMap: getConnectedDevices()
07-26 17:27:31.188  9173  9184 D BluetoothPan: onBluetoothStateChange on: true
07-26 17:27:31.195 10011 10086 D BluetoothSocket: bindListen(): myUserId = 0
07-26 17:27:31.195 10011 10086 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 17:27:31.198  9173  9173 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 17:27:31.198  9173  9173 D PanProfile: Bluetooth service connected
07-26 17:27:31.199 10011 10086 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
07-26 17:27:31.200  4068  4361 D BluetoothSap: onBluetoothStateChange: up=true
07-26 17:27:31.200  4068  4361 D BluetoothSap: Binding service...
07-26 17:27:31.200 10011 10031 W bt_btif : btif_dm_generic_evt: event=34050
07-26 17:27:31.200 10011 10031 D BluetoothAdapterProperties: [VendorCapa] : mDbfwSupported: 1 , mA2dpLinkFeedbackSupported: 1
,07-26 17:27:31.205  9173  9184 D BluetoothSap: onBluetoothStateChange: up=true
07-26 17:27:31.205  9173  9184 D BluetoothSap: Binding service...
07-26 17:27:31.207  4068  4068 D BluetoothSap: Proxy object connected
,07-26 17:27:31.207  4068  4068 D SapProfile: Bluetooth service connected
,07-26 17:27:31.210  9173  9173 D BluetoothSap: Proxy object connected
07-26 17:27:31.210  4068  4084 D BluetoothPbap: onBluetoothStateChange: up=true
,07-26 17:27:31.210  9173  9173 D SapProfile: Bluetooth service connected
,07-26 17:27:31.213  3714  3796 D BluetoothAdapter: onBluetoothStateChange: up=true
07-26 17:27:31.213  3714  3796 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-26 17:27:31.213  4068  4082 D BluetoothPan: onBluetoothStateChange on: true
,07-26 17:27:31.215  4068  4068 D BluetoothPbap: Proxy object connected
07-26 17:27:31.216  4068  4068 D PbapServerProfile: Bluetooth service connected
,07-26 17:27:31.217  4068  4068 D BluetoothPan: BluetoothPAN Proxy object connected
,07-26 17:27:31.217  4068  4068 D PanProfile: Bluetooth service connected
,07-26 17:27:31.217  4068  4084 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-26 17:27:31.223  4068  4361 D BluetoothAdapter: onBluetoothStateChange: up=true
07-26 17:27:31.223  4068  4361 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-26 17:27:31.224  4068  4068 D BluetoothInputDevice: Proxy object connected
07-26 17:27:31.224  4068  4068 D HidProfile: Bluetooth service connected
,07-26 17:27:31.228  4068  4284 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:31.228  3714  3714 D Telecom : SecBluetoothManager : register BluetoothHeadset after STATE_ON : null
07-26 17:27:31.228  3714  3714 D Telecom : SecBluetoothManager : registerBluetoothHeadsetMessageListener fail
07-26 17:27:31.228  4068  4284 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-26 17:27:31.229  3714  3714 D BluetoothPhoneService: Bluetooth Adapter state : 12
07-26 17:27:31.229  3714  3714 I BluetoothPhoneService: queryPhoneState
07-26 17:27:31.229  3714  3714 I BluetoothPhoneService: updateHeadsetWithCallState : true
,07-26 17:27:31.233  3714  3714 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-26 17:27:31.233  3714  3714 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:31.233  3714  3714 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-26 17:27:31.236  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,07-26 17:27:31.238  9173  9173 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:31.238  9173  9173 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-26 17:27:31.239 10011 10011 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:31.239 10011 10011 D PanService: BT STATE ON
07-26 17:27:31.240 10011 10011 D EnhancedTetheringManager: EnhancedTetheringManager()
07-26 17:27:31.240 10011 10011 D EnhancedTetheringManager: start
,07-26 17:27:31.244  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:31.251  3714  3738 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{b24df46: PendingIntentRecord{de9507 com.google.android.gms broadcastIntent}}
07-26 17:27:31.252 10011 10011 D ETMLeHelper: ETMLeHelper()
07-26 17:27:31.252 10011 10011 D ETMLeHelper: initTetherAdv
07-26 17:27:31.252  9173  9173 E BluetoothEventManager: unregisterProfileIntentReceiver :: mProfileConnectionReceiver was not registered.
07-26 17:27:31.252  9173  9173 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-26 17:27:31.255 10011 10011 D BluetoothAdapter: STATE_ON
,07-26 17:27:31.256 10011 10011 D BluetoothAdapter: STATE_ON
,07-26 17:27:31.257 10011 10011 D BluetoothAdapter: STATE_ON
,07-26 17:27:31.258  4068  4284 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
07-26 17:27:31.259 10011 10011 D BluetoothAdapter: isSecureModeEnabled
,07-26 17:27:31.259  4068  4284 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
07-26 17:27:31.259  4068  4284 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
07-26 17:27:31.259 10011 10011 D BtConfig.SecureMode: isSecureModeOn:false
07-26 17:27:31.259  4068  4284 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
07-26 17:27:31.259  4068  4284 W LocalBluetoothProfileManager: updateLocalProfiles :: Spp profile was created already 
07-26 17:27:31.260 10011 10011 D ETMLeHelper: initTetherScan
,07-26 17:27:31.261 10011 10011 D BluetoothAdapter: STATE_ON
,07-26 17:27:31.262 10011 10011 D BluetoothAdapter: STATE_ON
07-26 17:27:31.264  9173  9173 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-26 17:27:31.264 10011 10011 D BluetoothMapUtils: [RCS] imsConfigCscFeatures : , enableCpmFeature : false
07-26 17:27:31.264 10011 10011 D BluetoothMapUtils: mRcsSupported : false
,07-26 17:27:31.267  9173  9173 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-26 17:27:31.269  3714  3739 D MountService: getExternalStorageMountMode : 1
07-26 17:27:31.270  3714  3739 D MountService: getExternalStorageMountMode : 3
07-26 17:27:31.270  3714  3739 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
,07-26 17:27:31.271  9173  9173 E BluetoothHeadset: BTStateChangeCB is registed
,07-26 17:27:31.274  9173  9173 D BluetoothMap: Create BluetoothMap proxy object
,07-26 17:27:31.290 10090 10090 E Zygote  : v2
07-26 17:27:31.290 10090 10090 I libpersona: KNOX_SDCARD checking this for 10049
07-26 17:27:31.290 10090 10090 I libpersona: KNOX_SDCARD not a persona
07-26 17:27:31.291 10090 10090 E Zygote  : isSdpEnabledProcess - SDP enabled
,07-26 17:27:31.292 10090 10090 E Zygote  : accessInfo : 64
07-26 17:27:31.292 10090 10090 E Zygote  : isSdpEnabledProcess - SDP enabled
07-26 17:27:31.292 10090 10090 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
,07-26 17:27:31.300  3714  3739 I ActivityManager: Start proc 10090:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,07-26 17:27:31.302 10090 10090 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-26 17:27:31.304 10090 10090 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,07-26 17:27:31.310  9173  9173 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,07-26 17:27:31.317  9173  9173 D LocalBluetoothProfileManager: Adding local Spp profile
,07-26 17:27:31.330 10090 10090 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:31.330  9173  9173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-26 17:27:31.330 10090 10090 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:31.338  9173  9173 D A2dpProfile: Bluetooth service connected
,07-26 17:27:31.343  3714  4857 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
,07-26 17:27:31.350 10011 10032 D A2dpStateMachine: getConnectedDevices : size=0
,07-26 17:27:31.351  9173  9173 D BluetoothMap: Proxy object connected
07-26 17:27:31.351  9173  9173 D MapProfile: Bluetooth service connected
07-26 17:27:31.352  9173  9173 D BluetoothMap: getConnectedDevices()
,07-26 17:27:31.355  9173  9173 D BluetoothPbap: Proxy object connected
,07-26 17:27:31.356  9173  9173 D PbapServerProfile: Bluetooth service connected
07-26 17:27:31.356  9173  9173 D BluetoothInputDevice: Proxy object connected
,07-26 17:27:31.357  9173  9173 D HidProfile: Bluetooth service connected
,07-26 17:27:31.365  9173  9173 D DockEventReceiver: finishStartingService: stopping service
,07-26 17:27:31.379 10090 10090 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
,07-26 17:27:31.396 10090 10090 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:31.411  3714  3946 D RCPManagerService: exchangeData() failure , invalid userId
,07-26 17:27:31.432 10090 10090 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,07-26 17:27:31.433 10090 10090 I QBNRClientHelper: init SyncClientHelper : Email
07-26 17:27:31.433 10090 10090 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : EMAILFOLDER, 55LAYJm0O2, com.samsung.android.email.provider.service.sCloudBNRService2
07-26 17:27:31.433 10090 10090 I QBNRClientHelper: init SyncClientHelper : EMAILFOLDER
,07-26 17:27:31.466  3714  4858 D RCPManagerService: exchangeData() failure , invalid userId
,07-26 17:27:31.471 10090 10105 D skia    : ---- fAsset->read(8192) returned 0
07-26 17:27:31.471 10090 10105 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-26 17:27:31.474 10090 10090 D SamsungAnalytics:1.8.25: cf feature is supported
,07-26 17:27:31.476  3714  4900 D MountService: getExternalStorageMountMode : 1
07-26 17:27:31.476  3714  4900 D MountService: getExternalStorageMountMode : 3
07-26 17:27:31.476  3714  4900 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
,07-26 17:27:31.481 10090 10090 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
07-26 17:27:31.482 10090 10105 D skia    : ---- fAsset->read(8192) returned 0
07-26 17:27:31.482 10090 10105 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-26 17:27:31.483 10090 10105 D skia    : ---- fAsset->read(8192) returned 0
07-26 17:27:31.483 10090 10105 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-26 17:27:31.499  3714  4900 I ActivityManager: Start proc 10109:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
07-26 17:27:31.500 10109 10109 E Zygote  : v2
07-26 17:27:31.500 10109 10109 I libpersona: KNOX_SDCARD checking this for 10049
07-26 17:27:31.500 10109 10109 I libpersona: KNOX_SDCARD not a persona
07-26 17:27:31.501 10109 10109 E Zygote  : isSdpEnabledProcess - SDP enabled
07-26 17:27:31.502 10109 10109 E Zygote  : accessInfo : 64
07-26 17:27:31.502 10109 10109 E Zygote  : isSdpEnabledProcess - SDP enabled
07-26 17:27:31.502 10109 10109 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
,07-26 17:27:31.512 10109 10109 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:31.513 10109 10109 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,07-26 17:27:31.537 10109 10109 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 17:27:31.538 10109 10109 D ActivityThread: Added TimaKeyStore provider
07-26 17:27:31.540  3714  3946 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
,07-26 17:27:31.545  9888  9983 D BluetoothAdapter: STATE_ON
,07-26 17:27:31.548  9888  9983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 17:27:31.548  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:31.548  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:31.548  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:27:31.548  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:27:31.548  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-26 17:27:31.548  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-26 17:27:31.548  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 17:27:31.548  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 17:27:31.550  9888  9951 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,07-26 17:27:31.555  9888  9951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 17:27:31.555  3714  4541 D WifiService: setWifiEnabled: false pid=9888, uid=10033
,07-26 17:27:31.555  3714  4541 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-26 17:27:31.556  3714  4541 D WifiControlHistoryProvider: query
,07-26 17:27:31.562 10011 10011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:31.563 10011 10011 D BtConfig.SecureMode: isSecureModeOn:false
,07-26 17:27:31.564  9173  9173 D HeadsetProfile: Bluetooth service connected
07-26 17:27:31.565  3714  4541 D WifiNative-wlan0: callSECApiVoid - ID [312]
07-26 17:27:31.566  3714  4016 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
07-26 17:27:31.566  4068  4068 D HeadsetProfile: Bluetooth service connected
,07-26 17:27:31.566  3714  3714 I BluetoothPhoneService: updateHeadsetWithCallState : true
07-26 17:27:31.568  3714  4541 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-26 17:27:31.569  3714  4541 D SecContentProvider: called from android.uid.system:1000
07-26 17:27:31.569  3714  4541 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-26 17:27:31.571 10109 10109 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
07-26 17:27:31.573  3714  4541 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-26 17:27:31.574  3714  3927 D SecContentProvider: insert(), uri = 2
,07-26 17:27:31.576  3714  3927 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:31.577  3714  3927 D SecContentProvider: insert(), uri = 2
,07-26 17:27:31.577  3714  3927 D SecContentProvider: called from android.uid.system:1000
07-26 17:27:31.579  3714  3929 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-26 17:27:31.580  3714  3929 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@298c388
07-26 17:27:31.580  3714  3929 D WifiStateMachine: isFindLocationId() - Location Id : 1
07-26 17:27:31.580  3714  3929 D WifiStateMachine: ConnectedState - exit() - stopLearning id : 1
,07-26 17:27:31.580  3714  3929 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-26 17:27:31.581 10011 10075 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,07-26 17:27:31.584  9173  9173 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-26 17:27:31.584  9173  9173 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,07-26 17:27:31.586 10011 10068 D HeadsetStateMachine: Disconnected process message: 9, size: 0
,07-26 17:27:31.586 10011 10068 D A2dpSinkService: getA2dpSinkService(): service is NULL
,07-26 17:27:31.587 10109 10109 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-26 17:27:31.587  3714  3714 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.bluetooth.SecBluetoothMessageListener@e5c9bfc
07-26 17:27:31.587  3714  3714 D BluetoothHeadset: registerMessageListener
07-26 17:27:31.587 10011 10068 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-26 17:27:31.592  3714  3929 D SLocation: system
07-26 17:27:31.592  3714  3929 D SLocation: stopLearning ID = 1
,07-26 17:27:31.592  3714  3929 D SLocation: setLearningStatus ID = 1 / status = false
07-26 17:27:31.593  3714  3929 D SecContentProvider: insert(), uri = 2
07-26 17:27:31.594  3279  3851 D audio_hw_primary: adev_set_parameters: enter: kvpairs: A2dpSuspended=false
,07-26 17:27:31.594 10011 10068 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
07-26 17:27:31.602 10011 10075 D BluetoothSocket: bindListen(): myUserId = 0
07-26 17:27:31.602 10011 10075 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 17:27:31.602 10011 10022 D HeadsetService: registerMessageListener
07-26 17:27:31.603  3714  3929 D SecContentProvider: called from android.uid.system:1000
07-26 17:27:31.603  3714  3929 D WifiStateMachine: Wifi got Disconnected in connectedstate, Send provisioning intent mAutoRoamingfalse
07-26 17:27:31.604  3714  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiStateMachine$ConnectedState.exit:11809 com.android.internal.util.StateMachine$SmHandler.invokeExitMethods:1009 com.android.internal.util.StateMachine$SmHandler.performTransitions:865 com.android.internal.util.StateMachine$SmHandler.handleMessage:809 
07-26 17:27:31.605 10011 10022 D HeadsetService: registerMessageListener
07-26 17:27:31.606  3714  3714 I Telecom : SecBluetoothManager : register MessageListener
07-26 17:27:31.607  3714  3929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 17:27:31.607 10011 10126 D BluetoothSocket: bindListen(): myUserId = 0
07-26 17:27:31.607 10011 10126 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 17:27:31.608  3714  3934 D DhcpClient: doQuit
07-26 17:27:31.609  3714  3934 D ApfFilter: (wlan0): shutting down
07-26 17:27:31.609  3714  5087 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@bfb6174
07-26 17:27:31.609 10011 10126 D BluetoothSdpJni: sdpCreateSapsRecordNative:
07-26 17:27:31.609 10011 10126 D BluetoothSdpJni: SDP Create record success - handle: 0
07-26 17:27:31.610  3714  5087 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@1ed6f99
07-26 17:27:31.610 10011 10011 V BtOppService: isOwner == true
07-26 17:27:31.611  3714  5087 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@86d10d
07-26 17:27:31.614 10011 10068 D HeadsetStateMachine: Disconnected process message: 70, size: 0
07-26 17:27:31.614 10011 10075 D BluetoothSocket: bindListen(): myUserId = 0
07-26 17:27:31.615 10011 10068 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2537385
07-26 17:27:31.615 10011 10075 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 17:27:31.620  3714  3925 D WifiP2pService: InactiveState{ what=143375 }
07-26 17:27:31.620  3714  3925 D WifiP2pService: P2pEnabledState{ what=143375 }
07-26 17:27:31.624  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-26 17:27:31.625  3714  4016 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
07-26 17:27:31.625  3714  3959 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-26 17:27:31.625  3714  3959 D ConnectivityService: ignoring duplicate network state non-change
07-26 17:27:31.626  3714  3959 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 12
07-26 17:27:31.627  3714  3959 V NetworkStats: updateIfacesLocked()
07-26 17:27:31.627  3714  3959 V NetworkStats: performPollLocked(flags=0x1)
07-26 17:27:31.627  3714  3959 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 17:27:31.633  3714  3959 V NetworkStats: performPollLocked() took 6ms
,07-26 17:27:31.634  3714  3959 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:31.637 10011 10075 D ObexServerSockets: Succeed to create listening sockets 
07-26 17:27:31.637 10011 10075 D ObexServerSockets: startAccept()
07-26 17:27:31.638  3714  3929 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
07-26 17:27:31.638  3714  3929 I WifiConnectivityManager: Set WiFi disabled
07-26 17:27:31.638  3714  3929 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@298c388
07-26 17:27:31.638 10011 10075 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-26 17:27:31.638  3714  3929 I WifiStateMachine: deinitGeofence
07-26 17:27:31.639 10011 10075 D BluetoothSdpJni: SDP Create record success - handle: 1
07-26 17:27:31.642 10011 10128 D ObexServerSockets: Accepting socket connection for masId0
07-26 17:27:31.642 10011 10127 D ObexServerSockets: Accepting socket connection for masId0
07-26 17:27:31.650  4043  4043 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
07-26 17:27:31.649  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:31.653  3714  3929 D SLocation: stopGeofence ID = 1
07-26 17:27:31.654  3714  3959 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,07-26 17:27:31.654  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.654  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-26 17:27:31.655  3714  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [] ]
07-26 17:27:31.655  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
07-26 17:27:31.655  3714  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [] ]
07-26 17:27:31.655  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.656  3714  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.656  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 17:27:31.656  3714  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.656  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.656  3714  4014 D DnsEventListenerService: Logging 30 results for netId 502
07-26 17:27:31.656  3714  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.657  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.657  3714  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.657  4526  4593 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [false]
07-26 17:27:31.658  4526  4612 D PdnController: handleMessage: what 106
07-26 17:27:31.658  4526  4612 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [false]
07-26 17:27:31.659  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:31.659  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:31.659  3714  3714 I Telecom : SecBluetoothManager : not single connected gear
07-26 17:27:31.661  4526  4612 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [false]
07-26 17:27:31.661  4526  4612 D ResipRegiMgr: handleMessage(): 3
07-26 17:27:31.661  4526  4612 D RegiMgrBase: handleMessage: what 3
07-26 17:27:31.666  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.666  3714  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.666  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:31.667  3714  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-26 17:27:31.667  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.667  3714  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.668  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:31.668  3714  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:31.668  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:31.668  3714  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:31.669  4526  4593 D GeolocationController: WIFI : onLost
07-26 17:27:31.669  3714  5076 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-26 17:27:31.669  3714  5076 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: unregister CaptivePortalReceiver
07-26 17:27:31.670  3714  3796 D EntConnectivity: Not allowed due to - mEnabled false
07-26 17:27:31.676  3714  5087 D DhcpClient: onQuitting
07-26 17:27:31.678  3714  3959 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.683  4043  4043 D PhoneSwitcherNetworkRequstListener: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.683 10011 10011 D BluetoothUtils: readSalesCode :: sales code is XEO
07-26 17:27:31.684  4043  4043 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-26 17:27:31.684  4043  4043 D PhoneSwitcherNetworkRequstListener: evalRequest
07-26 17:27:31.684  4043  4043 D PhoneSwitcherNetworkRequstListener:   done
07-26 17:27:31.684  3714  3925 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.685  3714  3925 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 17:27:31.685  3714  3925 D WIFI_P2P: evalRequest
07-26 17:27:31.685  3714  3925 D WIFI_P2P:   done
07-26 17:27:31.690  3714  4025 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.690  3714  4025 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-26 17:27:31.690  3714  4025 D Ethernet: evalRequest
07-26 17:27:31.690  3714  4025 D Ethernet:   done
07-26 17:27:31.693  3714  4541 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
07-26 17:27:31.696  3714  4541 D SecContentProvider: called from android.uid.bluetooth:1002
07-26 17:27:31.699  3714  3714 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
07-26 17:27:31.702  3714  4567 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACo_0
07-26 17:27:31.702  3714  4567 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACo_0
,07-26 17:27:31.712  3244  3244 E audit   : type=1320 audit(1501082851.695:538): 
,07-26 17:27:31.715  3714  4567 I Telecom : SecBluetoothManager : not single connected gear
07-26 17:27:31.715  3714  4567 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACo_0
,07-26 17:27:31.719 10011 10133 D BluetoothSocket: bindListen(): myUserId = 0
07-26 17:27:31.719 10011 10133 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 17:27:31.723  3714  3946 D RCPManagerService: exchangeData() failure , invalid userId
,07-26 17:27:31.725  3714  3714 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
07-26 17:27:31.726  3714  3714 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-26 17:27:31.726  3714  3714 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-26 17:27:31.726  3714  3714 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
,07-26 17:27:31.727  3714  3714 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,07-26 17:27:31.727  3714  3955 I WifiHs20Service: Message received 5007
07-26 17:27:31.731 10109 10109 D SamsungAnalytics:1.8.25: cf feature is supported
07-26 17:27:31.731  3244  3244 E audit   : type=1320 audit(1501082851.715:539): 
07-26 17:27:31.733  3298  3774 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-26 17:27:31.734 10109 10135 D skia    : ---- fAsset->read(8192) returned 0
07-26 17:27:31.734 10109 10135 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-26 17:27:31.735  3714  4016 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-26 17:27:31.736  3714  3714 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
07-26 17:27:31.739 10109 10109 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
07-26 17:27:31.740 10011 10133 I BtOppRfcommListener: Accept thread started.
07-26 17:27:31.742  3714  3929 E SLocation: pendingIntent set to null
07-26 17:27:31.742  3714  3929 D SLocation: setStatus ID = 1 / status = 0
07-26 17:27:31.742  3714  3929 D SLocation: updateSession : trigger = false
07-26 17:27:31.742  3714  3929 D SLocation: updateSession : mSessionStatus = 0
07-26 17:27:31.742  3714  3929 D WifiStateMachine:  stopGeofence() - id : 1
07-26 17:27:31.742  3714  3929 D wifi    : android_net_wifi_reset_alert_handler = 0x725b63ec40
07-26 17:27:31.743  3714  3929 E WifiHAL : failed to request reset; result = -95
07-26 17:27:31.743  3714  3929 D wifi    : android_net_wifi_reset_log_handler = 0x725b63ec40
07-26 17:27:31.743  3714  3929 I WifiHAL : Failed to remove command 1: 0x0
07-26 17:27:31.743  3714  3929 D WifiHAL : Success to clear alerthandler
07-26 17:27:31.746  3714  4483 D SLocation: Session stopped
07-26 17:27:31.746  3714  4483 D SLocation: triggerAlarm
07-26 17:27:31.746  3714  4483 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / op:PendingIntent{f7a6e94: PendingIntentRecord{f4a5d3d android broadcastIntent}}
07-26 17:27:31.746  3714  4483 D SLocation: All alarm stopped
07-26 17:27:31.746  3714  3929 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-26 17:27:31.747  3714  3929 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.747  3714  3929 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 17:27:31.747  3714  3929 D WIFI_UT : evalRequest
07-26 17:27:31.747  3714  3929 D WIFI_UT :   done
07-26 17:27:31.747  3714  3929 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:31.747  3714  3929 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 17:27:31.747  3714  3929 D WIFI    : evalRequest
07-26 17:27:31.747  3714  3929 D WIFI    :   needNetworkFor
07-26 17:27:31.747  3714  3925 D WifiP2pService: InactiveState{ what=131204 }
07-26 17:27:31.747 10109 10135 D skia    : ---- fAsset->read(8192) returned 0
07-26 17:27:31.747 10109 10135 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-26 17:27:31.747  3714  3925 D WifiP2pService: P2pEnabledState{ what=131204 }
07-26 17:27:31.749 10109 10135 D skia    : ---- fAsset->read(8192) returned 0
07-26 17:27:31.749 10109 10135 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-26 17:27:31.752  3714  3956 I WifiScanningService: wifi driver unloaded
07-26 17:27:31.752  3714  3714 D RttService: SCAN_AVAILABLE : 1
07-26 17:27:31.752  3714  3958 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-26 17:27:31.752  4287  4287 I wpa_supplicant: P2,P: Set prekey state (NONE -> NONE)
07-26 17:27:31.753  4287  4287 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
07-26 17:27:31.754  3714  3925 D WifiP2pService: sending p2p connection changed broadcast: FAILED
07-26 17:27:31.755  3244  3244 E audit   : type=1320 audit(1501082851.735:540): 
07-26 17:27:31.758  3714  4858 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BleCentralService newState = 1 callingPackage = 10019
07-26 17:27:31.759  3714  3956 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.scanner.SupplicantWifiScannerImpl$2@5407932
07-26 17:27:31.764  3714  4543 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BlePeripheralService newState = 1 callingPackage = 10019
07-26 17:27:31.766  3714  3929 E WifiConnectivityManager: SingleScanListener onFailure: reason: -1 description: Scan was interrupted
07-26 17:27:31.770  3714  3797 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
,07-26 17:27:31.778  3714  3929 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170726T172733 - CU:1000/CP:3714
07-26 17:27:31.778  3714  3929 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172733, SetElapsed=302051, nowELAPSED=300063
07-26 17:27:31.780  3714  3925 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-26 17:27:31.783  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-26 17:27:31.783  3714  3797 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-26 17:27:31.783  3714  3797 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-26 17:27:31.784  3714  3797 D WifiDisplayController: disconnect
07-26 17:27:31.784  3714  3797 D WifiDisplayAdapter: onFeatureStateChanged empty
07-26 17:27:31.784  3714  3797 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-26 17:27:31.786  3714  3925 D SecContentProvider: insert(), uri = 2
07-26 17:27:31.788  3714  3925 D SecContentProvider: called from android.uid.system:1000
07-26 17:27:31.791  3714  3925 D WifiP2pService: P2pDisablingState
07-26 17:27:31.792  3714  3925 D WifiP2pService: P2pDisablingState{ what=147458 }
,07-26 17:27:31.792  3714  3925 D WifiP2pService: p2p socket connection lost
07-26 17:27:31.792  3714  3925 D SecContentProvider: insert(), uri = 2
,07-26 17:27:31.808  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-26 17:27:31.808  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-26 17:27:31.837  3244  3244 E audit   : type=1320 audit(1501082851.825:541): 
,07-26 17:27:31.846  3298  3774 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-26 17:27:31.846  3298  3774 D CommandListener: Clearing all IP addresses on wlan0
,07-26 17:27:31.847  3714  3959 D ConnectivityService: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
07-26 17:27:31.847  3714  3959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-26 17:27:31.848  3298  3766 I Netd    : Destroyed 15 sockets on 192.168.1.105 in 1.1 ms
07-26 17:27:31.848  4779  6828 V NativeCrypto: Read error: ssl=0x727dda6d00: I/O error during system call, Software caused connection abort
,07-26 17:27:31.850  3714  3796 D EntConnectivity: Not allowed due to - mEnabled false
,07-26 17:27:31.923  3714  3925 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:31.924  3714  3929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 17:27:31.924  3714  3925 D WifiP2pService: P2pDisabledState
07-26 17:27:31.927  4779  6828 V NativeCrypto: SSL shutdown failed: ssl=0x727dda6d00: I/O error during system call, Broken pipe
07-26 17:27:31.931  3714  3797 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: false, roaming: false, metered: false]
07-26 17:27:31.931  3714  3925 D WifiP2pService: P2pDisabledState{ what=143375 }
07-26 17:27:31.931  3714  3925 D WifiP2pService: DefaultState{ what=143375 }
07-26 17:27:31.936  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=-3ms what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-26 17:27:31.937  3714  4016 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
07-26 17:27:31.945  4287  4287 I wpa_supplicant: nl80211: Received scan results (22 BSSes)
07-26 17:27:31.946  3298  3766 D Netd    : Iface wlan0 link up
07-26 17:27:31.950  3714  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@38ba313
,07-26 17:27:31.964  3714  3918 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{4049039: PendingIntentRecord{6bcff04 com.google.android.gms broadcastIntent}}
,07-26 17:27:31.966  4779  6828 E GCM     : Wifi connection closed with errorCode 20
,07-26 17:27:31.969  3714  3929 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-26 17:27:31.971  4287  4287 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-26 17:27:31.972  5160  5340 I Authzen : [PermitStore] Getting all permits...
07-26 17:27:31.977  3244  3244 E audit   : type=1320 audit(1501082851.965:542): 
07-26 17:27:31.979  3714  3929 D SecContentProvider: insert(), uri = 2
07-26 17:27:31.980  3714  3929 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:31.986  3714 10155 I ApplicationPolicy: updateDataUsageMap
07-26 17:27:31.987  3714  3714 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-26 17:27:31.987  3714  3915 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
07-26 17:27:31.987  3714  3915 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
07-26 17:27:31.987  4779  4779 I BeaconBle: 'L' hardware scan: scan stopped, no clients
07-26 17:27:31.987  3714  3714 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = true
07-26 17:27:31.988  3714  3714 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-26 17:27:31.988  3714  3714 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
07-26 17:27:31.988  3714  3916 I KnoxVpnEngineService: vpn handle : Message received
07-26 17:27:31.988  3714  3714 D Tethering: Tethering got CONNECTIVITY_ACTION
07-26 17:27:31.988  3714  3916 I KnoxVpnEngineService: vpn handle : Message received
07-26 17:27:31.988  3714  3961 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
07-26 17:27:31.989  3714  3961 D Tethering: MasterInitialState.processMessage what=327683
07-26 17:27:31.989  3714  3916 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = true
,07-26 17:27:31.994  3244  3244 E audit   : type=1320 audit(1501082851.975:543): 
07-26 17:27:31.994  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-26 17:27:32.008  5160  5160 I CastMediaRouteProvider: Network connectivity changed
,07-26 17:27:32.011  3714  3920 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
07-26 17:27:32.011  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 17:27:32.012  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:32.012  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:32.012  3714  3920 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
07-26 17:27:32.012  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:32.013  3714  3920 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
,07-26 17:27:32.026  3298  3766 D Netd    : Iface p2p0 link up
,07-26 17:27:32.032  9405  9405 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
07-26 17:27:32.032  9405  9405 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
,07-26 17:27:32.034  9466  9466 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@4576d41 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-26 17:27:32.041  4043  4043 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-26 17:27:32.043 10011 10011 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-26 17:27:32.044  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135179 arg1=286 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-26 17:27:32.077  4068  4284 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
07-26 17:27:32.078  9405  9405 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 2
07-26 17:27:32.078  9405  9405 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
07-26 17:27:32.078  9405  9405 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
07-26 17:27:32.085  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:27:32.085  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
07-26 17:27:32.085  9888  9983 D BluetoothAdapter: STATE_ON
07-26 17:27:32.085  9888  9888 D BluetoothAdapter: STATE_ON
07-26 17:27:32.086  3714  3795 D Tethering: interfaceLinkStateChanged p2p0, true
07-26 17:27:32.086  3714  3795 D Tethering: interfaceStatusChanged p2p0, true
07-26 17:27:32.089  9888  9983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 17:27:32.089  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:32.089  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:32.089  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 17:27:32.089  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:27:32.089  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 17:27:32.089  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-26 17:27:32.089  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 17:27:32.089  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 17:27:32.089  3714  3929 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-26 17:27:32.092  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 17:27:32.092  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:32.092  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:32.092  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 17:27:32.092  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:27:32.092  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 17:27:32.092  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-26 17:27:32.092  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 17:27:32.092  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 17:27:32.093  9888  9951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 17:27:32.095  9888  9888 D BluetoothAdapter: STATE_ON
07-26 17:27:32.095  4904  4904 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-26 17:27:32.099  3714  4939 D WifiService: setWifiEnabled: true pid=9888, uid=10033
07-26 17:27:32.102  9888  9888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
07-26 17:27:32.105  9466  9466 I NetworkConnectivity: Network state changed: null
07-26 17:27:32.106  4287  4287 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-26 17:27:32.108  4287  4287 E wpa_supplicant: can't get BSS information
07-26 17:27:32.108  4287  4287 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.E6.C2 reason=3 locally_generated=1
07-26 17:27:32.117  3298  3766 D Netd    : Iface wlan0 link up
,07-26 17:27:32.118  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:32.118  3298  3774 E Netd    : netlink response contains error (No such file or directory)
07-26 17:27:32.123  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:32.127  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 17:27:32.127  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:27:32.127  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
,07-26 17:27:32.134  3714  3714 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
07-26 17:27:32.134  3714  4483 D SLocation: checkWifiInfo
07-26 17:27:32.134  3714  3714 V MARsPolicyManager: DataConnection: false
,07-26 17:27:32.135  3714  3714 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-26 17:27:32.135  3714  4483 D SLocation: wifi available : false
07-26 17:27:32.135  3714  3714 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-26 17:27:32.135  3714  4483 W SLocation: No Active Data Connection
07-26 17:27:32.135  3714  3714 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-26 17:27:32.135  3714  3955 I WifiHs20Service: Message received 5007
07-26 17:27:32.136  4779  4779 D BluetoothAdapter: STATE_ON
07-26 17:27:32.138  4779  4779 D BluetoothAdapter: STATE_ON
07-26 17:27:32.139  3714  3959 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED
07-26 17:27:32.139  3714  3959 D ConnectivityService: ignoring duplicate network state non-change
07-26 17:27:32.141  3714  4483 D SLocation: Session stopped
07-26 17:27:32.141  3714  4483 D SLocation: triggerAlarm
07-26 17:27:32.141  3714  4483 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / op:PendingIntent{f7a6e94: PendingIntentRecord{f4a5d3d android broadcastIntent}}
07-26 17:27:32.142  3714  4483 D SLocation: All alarm stopped
07-26 17:27:32.143  3714  4939 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-26 17:27:32.144  3714  4939 D WifiControlHistoryProvider: query
07-26 17:27:32.146  9466  9466 I NetworkPolicyMonitor: Download-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
07-26 17:27:32.149  3714  4040 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-26 17:27:32.155  4779  4779 I BeaconBle: Using BLE 'L' hardware layer
07-26 17:27:32.156  3714  3714 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-26 17:27:32.156  3714  3714 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-26 17:27:32.156  3714  3955 I WifiHs20Service: Message received 5011
07-26 17:27:32.156  3714  3714 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-26 17:27:32.156  3714  4040 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-26 17:27:32.157  3714  4483 D SLocation: checkWifiInfo
07-26 17:27:32.157  3714  4016 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-26 17:27:32.157  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-26 17:27:32.157  3714  3714 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
07-26 17:27:32.159  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 17:27:32.160  3714  4040 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-26 17:27:32.163  9466  9466 I NetworkPolicyMonitor: Stream-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
07-26 17:27:32.164  3714  4040 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-26 17:27:32.165  3714  4857 D MountService: getExternalStorageMountMode : 1
07-26 17:27:32.165  3714  4857 D MountService: getExternalStorageMountMode : 3
07-26 17:27:32.165  3714  4857 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10003, packageName : com.sec.android.provider.badge
07-26 17:27:32.168  3298  3769 D EnterpriseController: netId is 0
07-26 17:27:32.168  3298  3769 D Netd    : getNetworkForDns: using netid 0 for uid 10001
07-26 17:27:32.168  3298  3769 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-26 17:27:32.176  5160  5330 W MdnsClient_Cast: Multicast lock held. Releasing. Subtypes:"805741C9"
,07-26 17:27:32.180  5300 10159 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
07-26 17:27:32.180  5300 10159 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-26 17:27:32.180  5300 10159 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
07-26 17:27:32.180  5300 10159 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
07-26 17:27:32.180  5300 10159 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
07-26 17:27:32.180  5300 10159 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
07-26 17:27:32.180  5300 10159 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
07-26 17:27:32.180  5300 10159 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-26 17:27:32.180  5300 10159 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
07-26 17:27:32.180  5300 10159 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
07-26 17:27:32.180  5300 10159 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
07-26 17:27:32.180  5300 10159 E         : 	at java.lang.Thread.run(Thread.java:762)
07-26 17:27:32.180  5300 10159 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-26 17:27:32.180  5300 10159 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
07-26 17:27:32.180  5300 10159 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
07-26 17:27:32.180  5300 10159 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:175)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
07-26 17:27:32.180  5300 10159 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
07-26 17:27:32.180  5300 10159 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
07-26 17:27:32.180  5300 10159 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
07-26 17:27:32.180  5300 10159 E         : 	... 9 more
07-26 17:27:32.180  5300 10159 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-26 17:27:32.180  5300 10159 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-26 17:27:32.180  5300 10159 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(F,orwardingOs.java:55)
07-26 17:27:32.180  5300 10159 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
07-26 17:27:32.180  5300 10159 E         : 	... 26 more
07-26 17:27:32.180  5300 10159 E         : 
07-26 17:27:32.181  5160  5330 W MdnsClient: unicast receiver thread is already dead.
,07-26 17:27:32.184  5300 10159 E         : Unable to fetch advertisement frequency.
07-26 17:27:32.184  5300 10159 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-26 17:27:32.184  5300 10159 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
07-26 17:27:32.184  5300 10159 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
07-26 17:27:32.184  5300 10159 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
07-26 17:27:32.184  5300 10159 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
07-26 17:27:32.184  5300 10159 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
07-26 17:27:32.184  5300 10159 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-26 17:27:32.184  5300 10159 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
07-26 17:27:32.184  5300 10159 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
07-26 17:27:32.184  5300 10159 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
07-26 17:27:32.184  5300 10159 E         : 	at java.lang.Thread.run(Thread.java:762)
07-26 17:27:32.184  5300 10159 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-26 17:27:32.184  5300 10159 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
07-26 17:27:32.184  5300 10159 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
07-26 17:27:32.184  5300 10159 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(R,outeSelector.java:175)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
07-26 17:27:32.184  5300 10159 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
07-26 17:27:32.184  5300 10159 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
07-26 17:27:32.184  5300 10159 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
07-26 17:27:32.184  5300 10159 E         : 	... 9 more
07-26 17:27:32.184  5300 10159 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-26 17:27:32.184  5300 10159 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-26 17:27:32.184  5300 10159 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-26 17:27:32.184  5300 10159 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
07-26 17:27:32.184  5300 10159 E         : 	... 26 more
07-26 17:27:32.184  5300 10159 E         : 
,07-26 17:27:32.189 10161 10161 E Zygote  : v2
,07-26 17:27:32.190 10161 10161 I libpersona: KNOX_SDCARD checking this for 10003
07-26 17:27:32.190 10161 10161 I libpersona: KNOX_SDCARD not a persona
07-26 17:27:32.190 10161 10161 E Zygote  : accessInfo : 0
,07-26 17:27:32.195 10161 10161 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:32.196 10161 10161 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,07-26 17:27:32.199  3714  4857 I ActivityManager: Start proc 10161:com.sec.android.provider.badge/u0a3 for broadcast com.sec.android.provider.badge/.BadgeCountReceiver
,07-26 17:27:32.201  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-26 17:27:32.207  3714  4939 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-26 17:27:32.210  3714  4939 D SecContentProvider: called from android.uid.system:1000
07-26 17:27:32.211  3714  4939 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-26 17:27:32.214 10161 10161 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:32.214 10161 10161 D ActivityThread: Added TimaKeyStore provider
07-26 17:27:32.215  3714  4939 I WifiService: Wi-Fi Sharing settings has not been accessed
07-26 17:27:32.215  3714  4939 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-26 17:27:32.216  3714  3927 D SecContentProvider: insert(), uri = 2
07-26 17:27:32.217  3714  3927 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:32.218  3714  3927 D SecContentProvider: insert(), uri = 2
07-26 17:27:32.218  3714  4858 I ActivityManager: DSS on for com.sec.android.provider.badge and scale is 1.0
,07-26 17:27:32.223  3714  3927 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:32.225  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:32.225  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:32.225  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:32.226  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:32.226  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:32.226  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:32.226  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:32.226  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:32.226  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:32.226  4287  4287 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
07-26 17:27:32.226  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:32.232  4779  6820 I BeaconBle: Client requested scan, settings=BleSettings [scanMode=LOW_LATENCY, callbackType=ALL_MATCHES, reportDelayMillis=0, 3 filters, 0 clients, callingClientName=Nearby], listener=hjz@1cb1bb1
,07-26 17:27:32.238  9466  9466 I DevicePlayback: Got network change: mobile=falsewifi=false
,07-26 17:27:32.238  9466  9466 I DevicePlayback: Disabling Woodstock in 200000ms
,07-26 17:27:32.239 10161 10161 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_N/lib/arm64
,07-26 17:27:32.246 10161 10161 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:32.249 10161 10161 D BadgeProvider: onCreate
,07-26 17:27:32.249 10161 10161 D BadgeProvider: DatabaseHelper
07-26 17:27:32.251 10161 10161 D BadgeCountReceiver: badge intent : Intent { act=com.sec.intent.action.BADGE_COUNT_UPDATE flg=0x10 cmp=com.sec.android.provider.badge/.BadgeCountReceiver launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:32.251  4779  6820 I BeaconBle: 'L' hardware scan: 3 filters, scanMode=2, reportdelay=0, callback type=1, #clients=1
07-26 17:27:32.251 10161 10161 D BadgeCountReceiver: packageName: com.samsung.android.email.provider, className: com.samsung.android.email.ui.activity.MessageListXL, count: 0
,07-26 17:27:32.254 10161 10161 D BadgeProvider: onOpen
,07-26 17:27:32.255 10161 10161 D BaseReflect: null getOwnClass TEST
07-26 17:27:32.255 10161 10161 D MethodReflector: android.content.ContentResolver getClass TEST
07-26 17:27:32.256 10161 10161 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
07-26 17:27:32.256 10161 10161 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
07-26 17:27:32.257 10161 10161 D MethodReflector: notifyChange is called
07-26 17:27:32.258  5003  5003 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
07-26 17:27:32.258 10161 10161 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-26 17:27:32.258 10161 10161 D BadgeProvider: sendNotify, [notify] : null
07-26 17:27:32.258  5003  5003 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
07-26 17:27:32.258 10161 10161 D BadgeProvider: update, getCallingPackage() : com.sec.android.provider.badge
07-26 17:27:32.258 10161 10161 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-26 17:27:32.258 10161 10161 D BadgeProvider: update, [uri.query] : null
07-26 17:27:32.258 10161 10161 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-26 17:27:32.258 10161 10161 D BadgeProvider: update, [UpdateCount] : 1
07-26 17:27:32.259  4779  6820 I BeaconBle: Starting scan on delegate scanner - BT state: 12
07-26 17:27:32.259  4779  6820 D BluetoothLeScanner: Start Scan
,07-26 17:27:32.264  4779  6820 D BluetoothAdapter: STATE_ON
07-26 17:27:32.265  4779  6820 D BluetoothAdapter: STATE_ON
07-26 17:27:32.267  9173  9173 I WifiApBroadcastReceiver: onReceive: action com.samsung.intent.action.START_PROVISIONING userID :0
07-26 17:27:32.267  4779  6820 D BluetoothAdapter: STATE_ON
,07-26 17:27:32.270  4779  6807 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,07-26 17:27:32.270  4779  6820 D BluetoothAdapter: STATE_ON
07-26 17:27:32.270  3714  4858 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-26 17:27:32.274 10011 10032 D BtGatt.GattService: registerClient() - UUID=33125518-29b1-4026-b459-fe2dab95fabc
,07-26 17:27:32.276  3298  3766 D Netd    : Iface wlan0 link up
,07-26 17:27:32.276  3298  3766 D Netd    : Iface wlan0 link up
07-26 17:27:32.277  4287  4287 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-26 17:27:32.277  4287  4287 I wpa_supplicant: CTRL_IFACE: Detach monitor that cannot receive messages: /data/misc/wifi/sockets/wpa_ctrl_3714-2\x00
07-26 17:27:32.278  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
,07-26 17:27:32.278  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
07-26 17:27:32.279  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:27:32.279  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
,07-26 17:27:32.286  3714 10158 D MountService: getExternalStorageMountMode : 3
,07-26 17:27:32.286  3714 10158 D MountService: getExternalStorageMountMode : 3
07-26 17:27:32.286  3714 10158 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 5017, packageName : com.samsung.android.radiobasedlocation
,07-26 17:27:32.306  4068  4207 D vol.MediaSessions: onQueueChanged com.google.android.music []
,07-26 17:27:32.309 10178 10178 E Zygote  : v2
07-26 17:27:32.309 10178 10178 I libpersona: KNOX_SDCARD checking this for 5017
07-26 17:27:32.309 10178 10178 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:32.310  3714 10158 I ActivityManager: Start proc 10178:com.samsung.android.radiobasedlocation/5017 for broadcast com.samsung.android.radiobasedlocation/.RblServiceReceiver
07-26 17:27:32.310 10178 10178 E Zygote  : accessInfo : 0
,07-26 17:27:32.314  3714 10158 I ActivityManager: KPU : put [com.android.printspooler] : 26732 K
07-26 17:27:32.314  3714 10158 I ActivityManager: Killing 8162:com.android.printspooler/u0a138 (adj 906): DHA:empty #33
,07-26 17:27:32.320 10178 10178 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:32.321 10178 10178 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.radiobasedlocation 
,07-26 17:27:32.335  3714  4901 D ActivityManager: cleanUpApplicationRecord -- 8162
,07-26 17:27:32.337  4844  4855 D ForegroundUtils: could not check pending caller
,07-26 17:27:32.343 10178 10178 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:32.343  3714  3929 D wifi    : In wifi stop Hal
07-26 17:27:32.343  3714  3929 D wifi    : halHandle = 0x725b6235e0, mVM = 0x7289690300, mCls = 0x1010be
07-26 17:27:32.343  3714  4286 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-26 17:27:32.343  3714  4286 D WifiHAL : Got a signal to exit!!!
07-26 17:27:32.343  3714  4286 I WifiHAL : Exit wifi_event_loop
07-26 17:27:32.343 10178 10178 D ActivityThread: Added TimaKeyStore provider
07-26 17:27:32.344  3714  3929 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-26 17:27:32.344  3714  3929 E WifiHAL : Event processing terminated
,07-26 17:27:32.349  3714  3714 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-26 17:27:32.349  3714  3954 D HS20StateMachine: WIFI_STATE_DISABLED
07-26 17:27:32.349  3714  3954 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
07-26 17:27:32.349  3714  3714 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-26 17:27:32.350  3714  3955 I WifiHs20Service: Message received 5011
,07-26 17:27:32.352  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135173 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-26 17:27:32.353  3298  3766 D Netd    : Iface p2p0 link down
07-26 17:27:32.355  3714  3795 D Tethering: interfaceLinkStateChanged p2p0, false
,07-26 17:27:32.355  3714  3795 D Tethering: interfaceStatusChanged p2p0, false
07-26 17:27:32.359  3714  4040 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-26 17:27:32.359  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-26 17:27:32.359  3714  3714 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-26 17:27:32.360  3714  4483 D SLocation: checkWifiInfo
07-26 17:27:32.362  3714  4040 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-26 17:27:32.362  4779  5414 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 17:27:32.364 10011 10011 D A2dpService: A2dpService - WIFI_STATE_DISABLED
,07-26 17:27:32.364 10011 10011 I BluetoothA2dpServiceJni: Attempting to set busy level
07-26 17:27:32.364  3714  4541 I ActivityManager: DSS on for com.samsung.android.radiobasedlocation and scale is 1.0
,07-26 17:27:32.368  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:32.377 10011 10031 D BtGatt.GattService: onClientRegistered() - UUID=33125518-29b1-4026-b459-fe2dab95fabc, clientIf=5, status=0
,07-26 17:27:32.378  4779  5201 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
,07-26 17:27:32.380 10011 10022 D BtGatt.GattService: start scan with filters
,07-26 17:27:32.382 10011 10022 D BtGatt.GattService: getScanSettings
,07-26 17:27:32.385 10011 10022 D BtGatt.GattService: Is it foreground application = false
07-26 17:27:32.385 10011 10022 D BtGatt.GattService: Its third party background application, change scanmode to low power
,07-26 17:27:32.391 10178 10178 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-26 17:27:32.393 10011 10059 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.google.uid.shared, msg: MESSAGE_START_SCAN
07-26 17:27:32.393 10178 10178 W System  : ClassLoader referenced unknown path: /system/priv-app/RadioBasedLocation/lib/arm64
07-26 17:27:32.394 10011 10049 D BtGatt.ScanManager: handling starting scan
07-26 17:27:32.394 10011 10049 D BtGatt.ScanManager: isFilteringSupported
07-26 17:27:32.395 10011 10049 D BluetoothAdapter: enableStandAloneBleMode=
07-26 17:27:32.396 10011 10049 D BluetoothAdapter: STATE_ON
07-26 17:27:32.397  3714  3929 D wifi    : In wifi cleaned up handler
07-26 17:27:32.397  3714  3929 I WifiHAL : Internal cleanup completed
07-26 17:27:32.397 10011 10049 D BluetoothAdapter: STATE_ON
07-26 17:27:32.399 10011 10049 D BluetoothAdapter: STATE_ON
07-26 17:27:32.400 10011 10049 D BluetoothAdapter: STATE_ON
07-26 17:27:32.401 10011 10049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:32.403 10011 10049 D BluetoothAdapter: STATE_ON
07-26 17:27:32.404 10011 10049 D BluetoothAdapter: STATE_ON
07-26 17:27:32.411 10178 10178 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:32.415 10011 10031 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-26 17:27:32.415 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 17:27:32.416  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-26 17:27:32.417  4779  6820 I BeaconBle: Client requested to stop, listener=hjz@1cb1bb1
,07-26 17:27:32.419 10011 10049 D BtGatt.ScanManager: set filter index= 3 for clientIf= 5
07-26 17:27:32.419 10178 10178 I [RBL] PathProvider: @onCreate
07-26 17:27:32.420 10011 10049 D BtGatt.ScanManager: addFilterToController: 5
,07-26 17:27:32.424 10178 10178 I [RBL] ServiceReceiver: @onReceive - rawData : null
07-26 17:27:32.426  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-26 17:27:32.427 10011 10031 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=5, availableSpace=47
07-26 17:27:32.427 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 17:27:32.427  3714  3793 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
07-26 17:27:32.429 10011 10049 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-26 17:27:32.429 10011 10049 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-26 17:27:32.429 10011 10049 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
,07-26 17:27:32.436 10011 10031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
07-26 17:27:32.436 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:32.436  4779  6820 I BeaconBle: Stopping scan on delegate scanner - BT state: 12
07-26 17:27:32.437 10011 10049 D BtGatt.ScanManager: set filter index= 4 for clientIf= 5
07-26 17:27:32.437 10011 10049 D BtGatt.ScanManager: addFilterToController: 5
07-26 17:27:32.438  3714  4541 I ActivityManager: KPU : put [com.android.defcontainer] : 28104 K
07-26 17:27:32.438  3714  4541 I ActivityManager: Killing 9053:com.android.defcontainer/u0a8 (adj 906): DHA:empty #33
07-26 17:27:32.439  4779  6820 D BluetoothAdapter: STATE_ON
07-26 17:27:32.441  4779  6820 D BluetoothAdapter: STATE_ON
07-26 17:27:32.441  4779  6820 D BluetoothLeScanner: Stop Scan
07-26 17:27:32.443 10011 10033 D BtGatt.GattService: stopScan() - queue size =1
,07-26 17:27:32.443 10011 10033 D BtGatt.GattService: stopScan() - queue size =1
,07-26 17:27:32.443 10011 10059 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.google.uid.shared, msg: MESSAGE_STOP_SCAN
,07-26 17:27:32.444 10011 10031 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=5, availableSpace=46
,07-26 17:27:32.444 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:32.444 10011 10049 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-26 17:27:32.445 10011 10049 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-26 17:27:32.445 10011 10049 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
07-26 17:27:32.446 10011 10023 D BtGatt.GattService: unregisterClient() - clientIf=5
07-26 17:27:32.449  3714  4543 D MountService: getExternalStorageMountMode : 1
07-26 17:27:32.449  3714  4543 D MountService: getExternalStorageMountMode : 3
07-26 17:27:32.449  3714  4543 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.diagmonagent
07-26 17:27:32.451 10011 10031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=30
07-26 17:27:32.451 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:32.451  4779  6820 D BluetoothAdapter: STATE_ON
07-26 17:27:32.451 10011 10049 D BtGatt.ScanManager: set filter index= 5 for clientIf= 5
07-26 17:27:32.451 10011 10049 D BtGatt.ScanManager: addFilterToController: 2
07-26 17:27:32.453  4779  6820 D BluetoothAdapter: STATE_ON
07-26 17:27:32.453  4779  6820 I BeaconBle: Resetting - new scanner available: true
07-26 17:27:32.454  4779  6820 I BeaconBle: 'L' hardware scan: scan stopped, no clients
07-26 17:27:32.454  4779  6820 I BeaconBle: Scan canceled successfully.
,07-26 17:27:32.457 10011 10031 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=45
07-26 17:27:32.457 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 17:27:32.458 10011 10049 D BtGatt.ScanManager: High Rssi Filter value is = -128
,07-26 17:27:32.458 10011 10049 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-26 17:27:32.458 10011 10049 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
,07-26 17:27:32.459  5003  5003 D LauncherApplication: run: mBadgeRefreshHandler reloadBadges
,07-26 17:27:32.459  5003  5003 D Launcher.Model: reloadBadges entered.
07-26 17:27:32.462 10011 10031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=29
07-26 17:27:32.462 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:32.463 10011 10049 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-26 17:27:32.463 10011 10049 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=0 mLastConfiguredScanSetting=-2147483648
07-26 17:27:32.463 10011 10049 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 800
07-26 17:27:32.465 10011 10049 D BtGatt.ScanManager: stop scan
07-26 17:27:32.465 10011 10049 D BtGatt.ScanManager: delete FilterIndex - 3
07-26 17:27:32.466 10011 10031 D BtGatt.GattService: onScanParamSetupCompleted() status=0, clientIf=5
07-26 17:27:32.466 10011 10031 E BtGatt.ContextMap: Context not found for ID 5
07-26 17:27:32.466 10011 10031 E BtGatt.GattService: Scan app or callback is null for clientIf = 5
,07-26 17:27:32.489  3714  4543 I ActivityManager: Start proc 10193:com.sec.android.diagmonagent/1000 for broadcast com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
07-26 17:27:32.492  3714  3946 D ActivityManager: cleanUpApplicationRecord -- 9053
07-26 17:27:32.492 10193 10193 E Zygote  : v2
07-26 17:27:32.493 10193 10193 I libpersona: KNOX_SDCARD checking this for 1000
07-26 17:27:32.493 10193 10193 I libpersona: KNOX_SDCARD not a persona
07-26 17:27:32.494 10193 10193 E Zygote  : accessInfo : 0
07-26 17:27:32.494  3714  3738 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{60c9673: PendingIntentRecord{9254930 com.google.android.gms broadcastIntent}}
07-26 17:27:32.499  4779  6820 W NearbyMessages: Runnable[ScanComplete] not posted since EventLoop is destroyed
,07-26 17:27:32.502  4844  4856 D ForegroundUtils: could not check pending caller
,07-26 17:27:32.506 10193 10193 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-26 17:27:32.508 10193 10193 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.diagmonagent 
,07-26 17:27:32.513 10011 10031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=30
07-26 17:27:32.513 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:32.513 10011 10049 D BtGatt.ScanManager: delete FilterIndex - 4
,07-26 17:27:32.519 10011 10031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=31
,07-26 17:27:32.519 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 17:27:32.520 10011 10049 D BtGatt.ScanManager: delete FilterIndex - 5
,07-26 17:27:32.520 10161 10173 D BadgeProvider: query, [selection] : null
,07-26 17:27:32.525 10011 10031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,07-26 17:27:32.525 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:32.525 10011 10049 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
,07-26 17:27:32.525 10011 10049 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=0
,07-26 17:27:32.525 10011 10049 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-26 17:27:32.525  5003  5080 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
07-26 17:27:32.526  5003  5080 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
07-26 17:27:32.526  5003  5080 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
07-26 17:27:32.526  5003  5080 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
07-26 17:27:32.526  5003  5080 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
07-26 17:27:32.526  5003  5080 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
07-26 17:27:32.526  5003  5080 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.lool = 0
07-26 17:27:32.526  5003  5080 D BadgeCache: 1. updateBadgeCounts: com.wssyncmldm = 0
07-26 17:27:32.529  5003  5080 D BadgeCache: updated Badged:0
07-26 17:27:32.529  5003  5080 D BadgeCache: updateBadgeCounts:0
,07-26 17:27:32.533 10193 10193 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 17:27:32.534 10193 10193 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:32.535  3714  4938 I ActivityManager: DSS on for com.sec.android.diagmonagent and scale is 1.0
,07-26 17:27:32.554 10193 10193 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,07-26 17:27:32.569 10193 10193 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:32.590 10193 10193 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,07-26 17:27:32.635 10193 10193 E SQLiteLog: (1) no such column: currentid
,07-26 17:27:32.637 10193 10193 E DIAGMON_AGENT: [llllIIIIlllIIIlIllIl(906/lllIlIlIIIllIIlIllIl)] android.database.sqlite.SQLiteException: no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1
07-26 17:27:32.637 10193 10193 E DIAGMON_AGENT: #################################################################
07-26 17:27:32.637 10193 10193 E DIAGMON_AGENT: Error Code : 1 (SQLITE_ERROR)
07-26 17:27:32.637 10193 10193 E DIAGMON_AGENT: Caused By : SQL(query) error or missing database.
07-26 17:27:32.637 10193 10193 E DIAGMON_AGENT: 	(no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1)
07-26 17:27:32.637 10193 10193 E DIAGMON_AGENT: #################################################################
,07-26 17:27:32.674 10193 10193 E SQLiteLog: (1) table profilelist has no column named currentid
,07-26 17:27:32.675 10193 10193 E SQLiteDatabase: Error inserting number=0 len=0 profilename3=Mformation notiretrycount=0 currentid=-1 size=0 oplevel=0 serviceid= appid=0 profilename2=dm-Server notievent=0 sessionid=null profilename1=api-server status=0 uictype=0 text= holdingid=-1 sessionsavestate=0 profileindex=0 opmode= result=0 pushjobid= notiuievent=0
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: android.database.sqlite.SQLiteException: table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: #################################################################
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: Error Code : 1 (SQLITE_ERROR)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: Caused By : SQL(query) error or missing database.
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	(table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?))
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: #################################################################
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1005)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.prepare(SQLiteConnection.java:570)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.prepare(SQLiteSession.java:588)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.database.sqlite.SQLiteProgram.<init>(SQLiteProgram.java:59)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.<init>(SQLiteStatement.java:31)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1771)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1643)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:667)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:399)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:116)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:60)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1032)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5885)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap3(ActivityThread.java)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1703)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:154)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6692)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke,(Native Method)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1468)
07-26 17:27:32.675 10193 10193 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1358)
,07-26 17:27:32.715 10193 10193 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(64/onCreate)] nStatus : 0
,07-26 17:27:32.722 10193 10193 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(77/onCreate)] DiagMon DM Application Start !
,07-26 17:27:32.723 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-26 17:27:32.724  3714  4938 D WifiService: setWifiEnabled: true pid=9888, uid=10033
07-26 17:27:32.724 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-26 17:27:32.724 10193 10193 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-26 17:27:32.724 10193 10193 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
07-26 17:27:32.724  3714  4938 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-26 17:27:32.725  3714  4938 D WifiControlHistoryProvider: query
,07-26 17:27:32.730  3714  4859 D MountService: getExternalStorageMountMode : 1
07-26 17:27:32.730  3714  4859 D MountService: getExternalStorageMountMode : 3
07-26 17:27:32.730  3714  4859 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.app.RilErrorNotifier
,07-26 17:27:32.770 10207 10207 E Zygote  : v2
07-26 17:27:32.770 10207 10207 I libpersona: KNOX_SDCARD checking this for 1000
07-26 17:27:32.770 10207 10207 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:32.772 10207 10207 E Zygote  : accessInfo : 0
,07-26 17:27:32.774  3714  4859 I ActivityManager: Start proc 10207:com.sec.app.RilErrorNotifier/1000 for broadcast com.sec.app.RilErrorNotifier/.PhoneErrorReceiver
,07-26 17:27:32.776  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-26 17:27:32.782  3714  4938 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-26 17:27:32.782 10207 10207 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:32.783  3714  4938 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:32.783 10207 10207 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.app.RilErrorNotifier 
07-26 17:27:32.784  3714  4938 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-26 17:27:32.788  3714  4938 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-26 17:27:32.789  3714  4938 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-26 17:27:32.789  3714  3927 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-26 17:27:32.807 10207 10207 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:32.807 10207 10207 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:32.810  3714  4858 I ActivityManager: DSS on for com.sec.app.RilErrorNotifier and scale is 1.0
,07-26 17:27:32.837 10207 10207 W System  : ClassLoader referenced unknown path: /system/priv-app/PhoneErrService/lib/arm64
,07-26 17:27:32.857 10207 10207 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:32.863 10207 10207 I PhoneErrorReceiver: onReceive
,07-26 17:27:32.869  3714  3918 D MountService: getExternalStorageMountMode : 1
07-26 17:27:32.870  3714  3918 D MountService: getExternalStorageMountMode : 3
07-26 17:27:32.870  3714  3918 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.knox.switcher
,07-26 17:27:32.917 10220 10220 E Zygote  : v2
07-26 17:27:32.917 10220 10220 I libpersona: KNOX_SDCARD checking this for 1000
07-26 17:27:32.917 10220 10220 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:32.918 10220 10220 E Zygote  : accessInfo : 0
,07-26 17:27:32.921  3714  3918 W ActivityManager: Slow operation: 54ms so far, now at startProcess: returned from zygote!
,07-26 17:27:32.921  3714  3918 W ActivityManager: Slow operation: 54ms so far, now at startProcess: done updating battery stats
07-26 17:27:32.921  3714  3918 W ActivityManager: Slow operation: 54ms so far, now at startProcess: building log message
07-26 17:27:32.921  3714  3918 I ActivityManager: Start proc 10220:com.sec.knox.switcher/1000 for broadcast com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,07-26 17:27:32.921  3714  3918 W ActivityManager: Slow operation: 55ms so far, now at startProcess: starting to update pids map
07-26 17:27:32.921  3714  3918 W ActivityManager: Slow operation: 55ms so far, now at startProcess: done updating pids map
,07-26 17:27:32.922  3714  3918 W ActivityManager: Slow operation: 56ms so far, now at startProcess: done starting proc!
,07-26 17:27:32.928  3714  3918 I ActivityManager: KPU : put [com.samsung.android.bbc.bbcagent] : 26904 K
07-26 17:27:32.928  3714  3918 I ActivityManager: Killing 9155:com.samsung.android.bbc.bbcagent/1000 (adj 906): DHA:empty #33
,07-26 17:27:32.928 10220 10220 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:32.930 10220 10220 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.knox.switcher 
,07-26 17:27:32.951 10220 10220 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 17:27:32.952 10220 10220 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:32.954  3714 10158 I ActivityManager: DSS on for com.sec.knox.switcher and scale is 1.0
,07-26 17:27:32.961  3714  3923 D ActivityManager: cleanUpApplicationRecord -- 9155
,07-26 17:27:32.965  4844  4856 D ForegroundUtils: could not check pending caller
,07-26 17:27:32.973 10220 10220 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,07-26 17:27:32.988 10220 10220 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:32.994 10220 10220 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
07-26 17:27:32.994 10220 10220 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,07-26 17:27:32.994 10220 10220 D ShareFileProvider: ShareFileProvider | onCreate [0]
07-26 17:27:32.995 10220 10220 D ShareFileDBHelper: getInstance - ShareFileDBHelper
07-26 17:27:32.995 10220 10220 D ShareFileDBHelper: null == mDbHelperInstance - ShareFileDBHelper
07-26 17:27:32.995 10220 10220 D ShareFileDBHelper: ShareFileDBHelper - Constructor
,07-26 17:27:32.998 10220 10220 I usagelog: received in receiver
07-26 17:27:32.998 10220 10220 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-26 17:27:33.002 10220 10220 I KnoxUsageLogPro: premStatus:2
,07-26 17:27:33.009 10220 10220 I KnoxUsageLogPro: isEulaShown : false
07-26 17:27:33.009 10220 10220 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-26 17:27:33.014  3714  3918 D MountService: getExternalStorageMountMode : 1
07-26 17:27:33.014  3714  3918 D MountService: getExternalStorageMountMode : 3
07-26 17:27:33.015  3714  3918 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 5005, packageName : com.samsung.android.allshare.service.fileshare
,07-26 17:27:33.026  3298  3766 D Netd    : Iface wlan0 link down
,07-26 17:27:33.032  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, false
07-26 17:27:33.032  3714  3795 D Tethering: interfaceStatusChanged wlan0, false
,07-26 17:27:33.035  3714  4286 D wifi    : set interface wlan0 flags (DOWN)
07-26 17:27:33.036  3714  3929 D WifiNative-HAL: HAL event thread stopped successfully
,07-26 17:27:33.052 10233 10233 E Zygote  : v2
07-26 17:27:33.052 10233 10233 I libpersona: KNOX_SDCARD checking this for 5005
07-26 17:27:33.052 10233 10233 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:33.053  3714  3918 I ActivityManager: Start proc 10233:com.samsung.android.allshare.service.fileshare/5005 for broadcast com.samsung.android.allshare.service.fileshare/.FileShareBroadcastReceiver
07-26 17:27:33.053 10233 10233 E Zygote  : accessInfo : 0
,07-26 17:27:33.059  3714  3918 I ActivityManager: KPU : put [com.google.android.talk] : 36300 K
07-26 17:27:33.059  3714  3918 I ActivityManager: Killing 8848:com.google.android.talk/u0a112 (adj 906): DHA:empty #33
,07-26 17:27:33.064 10233 10233 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:33.066 10233 10233 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.allshare.service.fileshare 
,07-26 17:27:33.092 10233 10233 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:33.093 10233 10233 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:33.093  3714  4859 D ActivityManager: cleanUpApplicationRecord -- 8848
,07-26 17:27:33.095  4844  4856 D ForegroundUtils: could not check pending caller
,07-26 17:27:33.099  3714  3739 I ActivityManager: DSS on for com.samsung.android.allshare.service.fileshare and scale is 1.0
,07-26 17:27:33.136  3714  4487 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / op:PendingIntent{ff1334: PendingIntentRecord{2ad355d android broadcastIntent}}
,07-26 17:27:33.139  3714  4487 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20170727T172733 - CU:1000/CP:3714
07-26 17:27:33.139 10233 10233 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:33.149 10233 10233 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-26 17:27:33.152 10233 10233 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
,07-26 17:27:33.171 10233 10233 D FileShare: Outbound.stopDelayTimer - 
,07-26 17:27:33.184  3714  4858 I ActivityManager: KPU : put [com.facebook.system] : 27184 K
,07-26 17:27:33.184  3714  4858 I ActivityManager: Killing 9244:com.facebook.system/u0a12 (adj 906): DHA:empty #33
,07-26 17:27:33.227  3714  4541 D ActivityManager: cleanUpApplicationRecord -- 9244
07-26 17:27:33.227  5160  5160 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
07-26 17:27:33.228  4844  4855 D ForegroundUtils: could not check pending caller
,07-26 17:27:33.232  5160  8145 I iu.UploadsManager: num queued entries: 0
,07-26 17:27:33.233  5160  8145 I iu.UploadsManager: num updated entries: 0
,07-26 17:27:33.236  5160  8145 I iu.SyncManager: NEXT; no task
,07-26 17:27:33.240  3714  3929 E WifiHW  : ##################### set firmware type 0 #####################
,07-26 17:27:33.243  3714  4543 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:33.244  3298  3774 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-26 17:27:33.245  3298  3774 I WifiHW  : module is semco
,07-26 17:27:33.245  3298  3774 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-26 17:27:33.245  3298  3774 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-26 17:27:33.245  3298  3774 E WifiHW  : TEMP_FAILURE_RETRY complete
07-26 17:27:33.245  3298  3774 D SoftapController: Softap fwReload - Ok
07-26 17:27:33.247  3714  3929 E NetworkManagement: wifiFirmwareReload Error reloading wlan0 fw in STA mode: event = 200 218 Softap operation succeeded
,07-26 17:27:33.251  3298  3774 D CommandListener: Setting iface cfg
07-26 17:27:33.251  3298  3774 D CommandListener: Trying to bring down wlan0
,07-26 17:27:33.253  3298  3774 D CommandListener: Clearing all IP addresses on wlan0
,07-26 17:27:33.260  3714  3929 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-26 17:27:33.266  3714  4900 D MountService: getExternalStorageMountMode : 1
07-26 17:27:33.266  3714  4900 D MountService: getExternalStorageMountMode : 3
07-26 17:27:33.266  3714  4900 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10041, packageName : com.osp.app.signin
,07-26 17:27:33.289 10246 10246 E Zygote  : v2
07-26 17:27:33.289 10246 10246 I libpersona: KNOX_SDCARD checking this for 10041
07-26 17:27:33.289 10246 10246 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:33.290  3714  4900 I ActivityManager: Start proc 10246:com.osp.app.signin/u0a41 for broadcast com.osp.app.signin/.OspReceiver
07-26 17:27:33.290 10246 10246 E Zygote  : accessInfo : 0
,07-26 17:27:33.295  3714  4857 D WifiService: setWifiEnabled: true pid=9888, uid=10033
07-26 17:27:33.296  3714  4857 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-26 17:27:33.296  3714  4857 D WifiControlHistoryProvider: query
,07-26 17:27:33.300 10246 10246 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:33.302 10246 10246 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.osp.app.signin 
,07-26 17:27:33.303  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-26 17:27:33.303  3714  4857 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-26 17:27:33.304  3714  4857 D SecContentProvider: called from android.uid.system:1000
07-26 17:27:33.305  3714  4857 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-26 17:27:33.308  3714  4857 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-26 17:27:33.309  3714  4857 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-26 17:27:33.309  3714  3927 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-26 17:27:33.321  3714  4546 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170726T175733 - CU:10124/CP:5177
,07-26 17:27:33.328 10246 10246 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:33.329 10246 10246 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:33.331  3714  4542 I ActivityManager: DSS on for com.osp.app.signin and scale is 1.0
,07-26 17:27:33.399 10246 10246 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-26 17:27:33.402 10246 10246 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Dream/lib/arm64
,07-26 17:27:33.424 10246 10246 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:33.437 10246 10246 I SA      : [SSP] onCreated
,07-26 17:27:33.470 10246 10246 D SamsungAnalytics:1.8.22: cf feature is supported
,07-26 17:27:33.479 10246 10246 D SamsungAnalytics:1.8.22: [Tracker] Tracker start:1.8.22
,07-26 17:27:33.486 10246 10246 I SA      : LBE isSupportBixbyModel() FALSE
,07-26 17:27:33.499 10246 10246 I SA      : [TPM] There is no property file
,07-26 17:27:33.511 10246 10246 I SA      : [SCU] isHaveSA() - false
,07-26 17:27:33.520 10246 10246 I SA      : [SS] no samsung account is signed in
,07-26 17:27:33.525 10246 10246 I SA      : [TPM] getModelProperty : null
07-26 17:27:33.525 10246 10246 I SA      : [TPM] getCSCProperty : null
,07-26 17:27:33.528 10246 10246 I SA      : [SCU] isHaveSA() - false
,07-26 17:27:33.530 10246 10246 I SA      : [SCU] == networkStateCheck == false
07-26 17:27:33.530 10246 10246 I SA      : [SS] network off, couldn't connect to DIR
,07-26 17:27:33.536 10246 10246 D BixbyApi_0.1.6: Version Name:2.2.03-46
,07-26 17:27:33.540 10246 10246 I SA      : [DM] init START
,07-26 17:27:33.545 10246 10246 I SA      : [DM] This device is not a Vodafone
,07-26 17:27:33.548 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.549 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.549 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.550 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.550 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.551 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.551 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.552 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.552 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.553 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.553 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.554 10246 10246 W ResourceType: Failure getting entry for 0x7f0b0002 (t=10 e=2) (error -75)
07-26 17:27:33.554 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.555 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.555 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.556 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.556 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.556 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.557 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.557 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.558 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.558 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.559 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.559 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.560 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.560 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.561 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.561 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.561 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.562 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.562 10246 10246 W ResourceType: Failure getting entry for 0x7f0b0005 (t=10 e=5) (error -75)
,07-26 17:27:33.563 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.563 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.563 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.564 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.564 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.565 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.565 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.566 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.566 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.567 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.567 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.567 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.568 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.568 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.569 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 17:27:33.569 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.569 10246 10246 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 17:27:33.571 10246 10246 I SA      : support phone number id : true
07-26 17:27:33.571 10246 10246 I SA      : [DM] Supports Ref Jpn : true
,07-26 17:27:33.572 10246 10246 I SA      : [DM] init END
07-26 17:27:33.572 10246 10246 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
,07-26 17:27:33.579 10246 10246 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
07-26 17:27:33.579 10246 10246 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-26 17:27:33.594 10246 10246 I SA      : [SLFUCHKMGR] constructor called
,07-26 17:27:33.608 10246 10246 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-26 17:27:33.608 10246 10246 I SA      : [OR] == isSIMCardReady false ==
,07-26 17:27:33.608 10246 10246 I SA      : [SCU] == networkStateCheck == false
07-26 17:27:33.609 10246 10246 I SA      : [OR] onReceive END
,07-26 17:27:33.613  3714  3763 D MountService: getExternalStorageMountMode : 1
07-26 17:27:33.613  3714  3763 D MountService: getExternalStorageMountMode : 3
07-26 17:27:33.613  3714  3763 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.svcagent
,07-26 17:27:33.633 10269 10269 E Zygote  : v2
07-26 17:27:33.633 10269 10269 I libpersona: KNOX_SDCARD checking this for 1000
07-26 17:27:33.633 10269 10269 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:33.633 10269 10269 E Zygote  : accessInfo : 0
,07-26 17:27:33.639  3714  3763 I ActivityManager: Start proc 10269:com.samsung.android.svcagent/1000 for broadcast com.samsung.android.svcagent/com.samsung.android.service.svcagent.BootReceiver
,07-26 17:27:33.640 10269 10269 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:33.641 10269 10269 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.svcagent 
,07-26 17:27:33.643  3714  3918 I ActivityManager: KPU : put [com.google.android.apps.docs] : 41536 K
07-26 17:27:33.643  3714  3918 I ActivityManager: Killing 9259:com.google.android.apps.docs/u0a93 (adj 906): DHA:empty #33
,07-26 17:27:33.662 10269 10269 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:33.663 10269 10269 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:33.665  3714 10158 I ActivityManager: DSS on for com.samsung.android.svcagent and scale is 1.0
,07-26 17:27:33.676  3714  4938 D ActivityManager: cleanUpApplicationRecord -- 9259
,07-26 17:27:33.678  4844  4855 D ForegroundUtils: could not check pending caller
,07-26 17:27:33.684 10269 10269 W System  : ClassLoader referenced unknown path: /system/priv-app/SVCAgent/lib/arm64
,07-26 17:27:33.699 10269 10269 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:33.710 10269 10269 I SVCAgent: Ignore network change.
,07-26 17:27:33.712  3714  4542 D MountService: getExternalStorageMountMode : 1
07-26 17:27:33.712  3714  4542 D MountService: getExternalStorageMountMode : 3
07-26 17:27:33.712  3714  4542 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10064, packageName : com.samsung.android.themestore
,07-26 17:27:33.738 10282 10282 E Zygote  : v2
07-26 17:27:33.738 10282 10282 I libpersona: KNOX_SDCARD checking this for 10064
07-26 17:27:33.738 10282 10282 I libpersona: KNOX_SDCARD not a persona
07-26 17:27:33.739 10282 10282 E Zygote  : accessInfo : 0
,07-26 17:27:33.740  3714  4542 I ActivityManager: Start proc 10282:com.samsung.android.themestore/u0a64 for broadcast com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,07-26 17:27:33.745 10282 10282 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:33.746 10282 10282 I SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,07-26 17:27:33.749  3714  4542 I ActivityManager: KPU : put [com.facebook.appmanager] : 23320 K
07-26 17:27:33.749  3714  4542 I ActivityManager: Killing 9211:com.facebook.appmanager/u0a98 (adj 906): DHA:empty #33
,07-26 17:27:33.759  3244  3244 E audit   : type=1320 audit(1501082853.745:544): 
,07-26 17:27:33.766  3714  3864 D SamsungAlarmManager: Expired : 4
07-26 17:27:33.767  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T175733, SetElapsed=2101599, nowELAPSED=302051
,07-26 17:27:33.767  3714  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@9d9e000 alarm=Alarm{c9026cf type 2 when 302051 android}
,07-26 17:27:33.771 10282 10282 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:33.771 10282 10282 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:33.774  3714  3738 I ActivityManager: DSS on for com.samsung.android.themestore and scale is 1.0
,07-26 17:27:33.774  3244  3244 E audit   : type=1320 audit(1501082853.755:545): 
,07-26 17:27:33.782  3714  4858 D ActivityManager: cleanUpApplicationRecord -- 9211
,07-26 17:27:33.787  4844  4856 D ForegroundUtils: could not check pending caller
,07-26 17:27:33.794  3244  3244 E audit   : type=1320 audit(1501082853.775:546): 
,07-26 17:27:33.799 10282 10282 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-26 17:27:33.800 10282 10282 W System  : ClassLoader referenced unknown path: /system/priv-app/GalaxyThemes/lib/arm64
,07-26 17:27:33.810  3244  3244 E audit   : type=1320 audit(1501082853.795:547): 
,07-26 17:27:33.817  3714 10158 D WifiService: setWifiEnabled: true pid=9888, uid=10033
07-26 17:27:33.817  3714 10158 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-26 17:27:33.817  3714 10158 D WifiControlHistoryProvider: query
,07-26 17:27:33.819 10282 10282 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:33.825  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-26 17:27:33.825  3714 10158 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-26 17:27:33.827  3714 10158 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:33.827  3714 10158 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-26 17:27:33.832  3714 10158 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-26 17:27:33.833  3714 10158 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-26 17:27:33.833  3714  3927 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-26 17:27:33.840 10282 10282 D a       : Exist Config : false
,07-26 17:27:33.842 10282 10282 D a       : getMcc
,07-26 17:27:33.847 10282 10282 D as      : isQaMode
,07-26 17:27:33.852 10282 10282 D a       : getMnc
07-26 17:27:33.852 10282 10282 D a       : getCsc
,07-26 17:27:33.852 10282 10282 D a       : getSystemCountryCode
07-26 17:27:33.852 10282 10282 D a       : getImei
,07-26 17:27:33.856 10282 10282 D as      : getMd5HashString
,07-26 17:27:33.856 10282 10282 D as      : getSha256HashString
07-26 17:27:33.856 10282 10282 D a       : getModelName
07-26 17:27:33.857 10282 10282 D a       : getVirtualModelName
07-26 17:27:33.857 10282 10282 D a       : getAndroidSDKVersion
07-26 17:27:33.857 10282 10282 D a       : getLanguageCode
07-26 17:27:33.857 10282 10282 D a       : getCountryCode
,07-26 17:27:33.859 10282 10282 D a       : getNetworkType
,07-26 17:27:33.862 10282 10282 D w       : isSupportedAodSystemFeature
,07-26 17:27:33.864 10282 10282 D a       : getThemeFrameworkVersion
,07-26 17:27:33.868 10282 10282 D a       : isLogPrintMode
,07-26 17:27:33.871 10282 10282 D as      : isQaMode
,07-26 17:27:33.874 10282 10282 D a       : getVerName
,07-26 17:27:33.875 10282 10282 D a       : getVerCode
,07-26 17:27:33.876 10282 10282 D a       : getPackageName
07-26 17:27:33.876 10282 10282 D a       : getAutoUpgradeInterval
,07-26 17:27:33.878 10282 10282 D a       : loadCountrySearchEx
,07-26 17:27:33.881 10282 10282 D a       : com.samsung.android.themestore.g.c.b.u; class invalid for deserialization
,07-26 17:27:33.881 10282 10282 I a       : # initConfig Time : 44
07-26 17:27:33.881 10282 10282 I a       : ● MCC/NNC: /0
07-26 17:27:33.881 10282 10282 I a       : ● Model: SM-G930F_TM
07-26 17:27:33.881 10282 10282 I a       : ● MyApp Version: 2.1.56-70306
07-26 17:27:33.881 10282 10282 I a       : ● OS Version: 24
07-26 17:27:33.881 10282 10282 I a       : ● IsSupportedSView: true
,07-26 17:27:33.889 10282 10282 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,07-26 17:27:33.903 10282 10282 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,07-26 17:27:33.911  3714  3923 I ActivityManager: KPU : put [com.google.android.partnersetup] : 26920 K
07-26 17:27:33.911  3714  3923 I ActivityManager: Killing 9322:com.google.android.partnersetup/u0a23 (adj 906): DHA:empty #33
,07-26 17:27:33.920  7950  7950 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
07-26 17:27:33.921  7950  7950 E SPPClientService: [SystemStateMoniter] Current Time : 302205
,07-26 17:27:33.922  7950  7950 E SPPClientService: [SystemStateMoniter] No Connect : true
,07-26 17:27:33.940  7950 10312 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,07-26 17:27:33.959  3714  4541 D ActivityManager: cleanUpApplicationRecord -- 9322
07-26 17:27:33.959 10178 10178 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-26 17:27:33.964  3714  3929 D wifi    : set interface wlan0 flags (UP)
07-26 17:27:33.964  3714  3929 I WifiHAL : Initializing wifi
07-26 17:27:33.964  3714  3929 I WifiHAL : Creating socket
07-26 17:27:33.964  3298  3766 D Netd    : Iface wlan0 link up
,07-26 17:27:33.966  3714  3929 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-26 17:27:33.967  3714  3929 D wifi    : Did set static halHandle = 0x725b6235e0
07-26 17:27:33.967  3714  3929 D wifi    : halHandle = 0x725b6235e0, mVM = 0x7289690300, mCls = 0x102d36
07-26 17:27:33.967  3714  3929 D wifi    : array field set
,07-26 17:27:33.968  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:27:33.968  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
07-26 17:27:33.968  4844  4856 D ForegroundUtils: could not check pending caller
,07-26 17:27:33.972  3714 10314 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=491159434720
07-26 17:27:33.972  3714 10314 D wifi    : waitForHalEvents called, vm = 0x7289690300, obj = 0x102d36, env = 0x7265bfb740
07-26 17:27:33.971  3714  3929 I WifiHW  : CCMode is disabled, skip verifying wpa_supplicant
07-26 17:27:33.973  3714  3929 E WifiHW  : supplicant_name : p2p_supplicant
,07-26 17:27:33.986 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-26 17:27:33.987 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,07-26 17:27:33.987 10193 10193 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-26 17:27:33.994 10207 10207 I PhoneErrorReceiver: onReceive
,07-26 17:27:34.002 10220 10220 I usagelog: received in receiver
07-26 17:27:34.003 10220 10220 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-26 17:27:34.004 10220 10220 I KnoxUsageLogPro: premStatus:2
,07-26 17:27:34.005 10220 10220 I KnoxUsageLogPro: isEulaShown : false
07-26 17:27:34.005 10220 10220 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-26 17:27:34.019  9953  9953 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-26 17:27:34.019  9953  9953 D SecurityLogAgent: NetworkReceiver : Wifi_state is 0
,07-26 17:27:34.022  3714  4939 D MountService: getExternalStorageMountMode : 1
07-26 17:27:34.022  3714  4939 D MountService: getExternalStorageMountMode : 3
07-26 17:27:34.022  3714  4939 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10172, packageName : com.example.ThaliTestApp
,07-26 17:27:34.038 10316 10316 E Zygote  : v2
07-26 17:27:34.038 10316 10316 I libpersona: KNOX_SDCARD checking this for 10172
07-26 17:27:34.038 10316 10316 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:34.039 10316 10316 E Zygote  : accessInfo : 0
07-26 17:27:34.039  3714  4939 I ActivityManager: Start proc 10316:com.example.ThaliTestApp/u0a172 for broadcast com.example.ThaliTestApp/io.jxcore.node.ConnectivityChangeListener
,07-26 17:27:34.046 10316 10316 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:34.047 10316 10316 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.example.ThaliTestApp 
,07-26 17:27:34.051 10316 10316 I art     : Late-enabling -Xcheck:jni
,07-26 17:27:34.055 10315 10315 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 10315 | /system/bin/wpa_supplicant
07-26 17:27:34.055 10315 10315 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
,07-26 17:27:34.058 10315 10315 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-26 17:27:34.058 10315 10315 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-26 17:27:34.062 10315 10315 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x400008), vendorssid_list()
07-26 17:27:34.062 10315 10315 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-26 17:27:34.062  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10315
,07-26 17:27:34.063  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-26 17:27:34.063 10315 10315 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-26 17:27:34.063 10315 10315 I wpa_supplicant: ssSupport state is = 1
07-26 17:27:34.063 10315 10315 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
07-26 17:27:34.063  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
07-26 17:27:34.063 10315 10315 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-26 17:27:34.063  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10315
07-26 17:27:34.063  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-26 17:27:34.071 10316 10316 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:34.072 10316 10316 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:34.074  3714  4543 I ActivityManager: DSS on for com.example.ThaliTestApp and scale is 1.0
,07-26 17:27:34.075  3714  3929 D SecContentProvider: insert(), uri = 2
,07-26 17:27:34.077  3714  3929 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:34.080  3714  3929 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-26 17:27:34.082  3714  3929 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,07-26 17:27:34.085  3714  3714 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-26 17:27:34.085  3714  3714 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-26 17:27:34.086  3714  3955 I WifiHs20Service: Message received 5011
,07-26 17:27:34.087  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=2 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-26 17:27:34.090  3714  4040 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-26 17:27:34.093  3714  4040 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-26 17:27:34.096  3714  3714 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-26 17:27:34.096  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:34.096  3714  4483 D SLocation: checkWifiInfo
,07-26 17:27:34.102 10316 10316 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-26 17:27:34.106  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:34.122 10316 10316 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:34.131  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.132  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.132  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.132  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.133  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.133  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.133  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.133  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.134  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.134  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.145  4649  4649 D io_stats: !@   8,0 r 26136 2289356 w 5180 206840 d 680 73972 f 2104 2104 iot 11960 11049 th 472500 0 0 pt 0 inp 1 0 302.429
,07-26 17:27:34.175 10316 10316 D jxcore_app_log: JniHelper::setJavaVM(0xee234000), pthread_self() = -243567308
07-26 17:27:34.175 10316 10316 E JX-Cordova: JXcore wasn't initialized yet
,07-26 17:27:34.178  3714  4937 D MountService: getExternalStorageMountMode : 3
07-26 17:27:34.178  3714  4937 D MountService: getExternalStorageMountMode : 3
07-26 17:27:34.179  3714  4937 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 10173, packageName : com.rockwellautomation.AppPlatformP2P
,07-26 17:27:34.201 10331 10331 E Zygote  : v2
07-26 17:27:34.201 10331 10331 I libpersona: KNOX_SDCARD checking this for 10173
07-26 17:27:34.201 10331 10331 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:34.201  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-26 17:27:34.202  3714  4937 I ActivityManager: Start proc 10331:com.rockwellautomation.AppPlatformP2P/u0a173 for broadcast com.rockwellautomation.AppPlatformP2P/io.jxcore.node.ConnectivityChangeListener
,07-26 17:27:34.202 10331 10331 E Zygote  : accessInfo : 0
,07-26 17:27:34.208  3714  4937 I ActivityManager: KPU : put [com.samsung.android.SettingsReceiver] : 26752 K
,07-26 17:27:34.208  3714  4937 I ActivityManager: Killing 9342:com.samsung.android.SettingsReceiver/1000 (adj 906): DHA:empty #33
,07-26 17:27:34.213 10331 10331 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:34.215 10331 10331 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.rockwellautomation.AppPlatformP2P 
07-26 17:27:34.218 10331 10331 I art     : Late-enabling -Xcheck:jni
07-26 17:27:34.223  3244  3244 E audit   : type=1320 audit(1501082854.205:548): 
,07-26 17:27:34.233  3714  4542 D ActivityManager: cleanUpApplicationRecord -- 9342
,07-26 17:27:34.234  4844  4856 D ForegroundUtils: could not check pending caller
,07-26 17:27:34.238  3244  3244 E audit   : type=1320 audit(1501082854.225:549): 
,07-26 17:27:34.240 10331 10331 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 17:27:34.240 10331 10331 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:34.242  3714  4901 I ActivityManager: DSS on for com.rockwellautomation.AppPlatformP2P and scale is 1.0
,07-26 17:27:34.251 10315 10315 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,07-26 17:27:34.265  3244  3244 E audit   : type=1320 audit(1501082854.245:550): 
,07-26 17:27:34.272 10331 10331 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-26 17:27:34.282  3244  3244 E audit   : type=1320 audit(1501082854.265:551): 
,07-26 17:27:34.284 10315 10315 W wpa_supplicant: Loading system cred
,07-26 17:27:34.284 10315 10315 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-26 17:27:34.284  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10315
07-26 17:27:34.284  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-26 17:27:34.284 10315 10315 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-26 17:27:34.284 10315 10315 I wpa_supplicant: ssSupport state is = 1
07-26 17:27:34.284  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-26 17:27:34.285 10315 10315 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-26 17:27:34.285 10315 10315 I wpa_supplicant: [getIMSI]: sim_num 0
,07-26 17:27:34.290 10331 10331 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:34.306  3714  4937 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.307  3714  4937 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.307  3714  4937 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.307  3714  4937 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.307  3714  4937 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.307  3714  4937 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.307  3714  4937 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.307  3714  4937 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.308  3714  4937 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.308  3714  4937 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.337  3714  4543 D WifiService: setWifiEnabled: true pid=9888, uid=10033
07-26 17:27:34.338  3714  4543 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-26 17:27:34.338  3714  4543 D WifiControlHistoryProvider: query
,07-26 17:27:34.343  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-26 17:27:34.344  3714  4543 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-26 17:27:34.344  3714  4543 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:34.345  3714  4543 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-26 17:27:34.347 10331 10331 D jxcore_app_log: JniHelper::setJavaVM(0xee234000), pthread_self() = -243567308
07-26 17:27:34.347 10331 10331 E JX-Cordova: JXcore wasn't initialized yet
,07-26 17:27:34.351  3714  4543 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-26 17:27:34.352  3714  4543 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-26 17:27:34.353  3714  4936 I ActivityManager: KPU : put [com.samsung.android.app.mirrorlink] : 21084 K
,07-26 17:27:34.353  3714  4936 I ActivityManager: Killing 9355:com.samsung.android.app.mirrorlink/1000 (adj 906): DHA:empty #33
07-26 17:27:34.356  3714  4901 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.357  3714  4901 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.357  3714  4901 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.357  3714  4901 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.357  3714  4901 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.357  3714  4901 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.357  3714  4901 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.357  3714  4901 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.357  3714  4901 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.358  3714  4901 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.359 10315 10315 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 17:27:34.360  3298  3766 D Netd    : Iface wlan0 link up
07-26 17:27:34.361  3298  3766 D Netd    : Iface wlan0 link up
07-26 17:27:34.363  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:27:34.363  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
07-26 17:27:34.364  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:27:34.364  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
,07-26 17:27:34.372  9953  9953 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-26 17:27:34.372  9953  9953 D SecurityLogAgent: NetworkReceiver : Wifi_state is 1
,07-26 17:27:34.382  3714  3946 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.382  3714  3946 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.382  3714  3946 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.382  3714  3946 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.382  3714  3946 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.382  3714  3946 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.382  3714  3946 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.382  3714  3946 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.383  3714  3946 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.383  3714  3946 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.383  3714  3738 D ActivityManager: cleanUpApplicationRecord -- 9355
,07-26 17:27:34.388  4844  4856 D ForegroundUtils: could not check pending caller
,07-26 17:27:34.396  3714  4858 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.397  3714  4858 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.397  3714  4858 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.397  3714  4858 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.397  3714  4858 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.397  3714  4858 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.398  3714  4858 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.398  3714  4858 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.398  3714  4858 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.398  3714  4858 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.407  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.407  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.407  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.408  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.408  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.408  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.408  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.408  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.408  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.408  3714  3739 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.416  9953  9953 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-26 17:27:34.417  9953  9953 D SecurityLogAgent: NetworkReceiver : Wifi_state is 2
,07-26 17:27:34.425  3714  3918 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.426  3714  3918 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.426  3714  3918 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.426  3714  3918 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.426  3714  3918 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.426  3714  3918 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.426  3714  3918 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.426  3714  3918 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.426  3714  3918 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.426  3714  3918 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.435  3714  4542 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.435  3714  4542 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.436  3714  4542 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.436  3714  4542 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.436  3714  4542 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.436  3714  4542 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.436  3714  4542 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.436  3714  4542 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.436  3714  4542 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.436  3714  4542 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.437 10315 10315 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-26 17:27:34.437 10315 10315 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
07-26 17:27:34.438  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10315
07-26 17:27:34.438  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-26 17:27:34.438  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-26 17:27:34.438 10315 10315 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-26 17:27:34.438 10315 10315 I wpa_supplicant: ssSupport state is = 1
,07-26 17:27:34.441 10315 10315 E wpa_supplicant: nl80211: Could not configure driver mode
,07-26 17:27:34.441 10315 10315 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-26 17:27:34.441 10315 10315 E wpa_supplicant: p2p0: Failed to initialize driver interface
07-26 17:27:34.442 10315 10315 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,07-26 17:27:34.442 10315 10315 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
07-26 17:27:34.443  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10315
07-26 17:27:34.443  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-26 17:27:34.443  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-26 17:27:34.443 10315 10315 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
,07-26 17:27:34.443 10315 10315 I wpa_supplicant: ssSupport state is = 1
,07-26 17:27:34.446  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.446  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.446  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.446  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.446  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.446  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.447  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.447  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.447  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:34.447  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:34.518 10315 10315 I wpa_supplicant: rfkill: Cannot get wiphy information
,07-26 17:27:34.533 10315 10315 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,07-26 17:27:34.862  3714  4858 D WifiService: setWifiEnabled: true pid=9888, uid=10033
07-26 17:27:34.863  3714  4858 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-26 17:27:34.863  3714  4858 D WifiControlHistoryProvider: query
,07-26 17:27:34.877  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-26 17:27:34.878  3714  4858 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-26 17:27:34.880  3714  4858 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:34.882  3714  4858 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-26 17:27:34.890  3714  4858 I WifiService: Wi-Fi Sharing settings has not been accessed
07-26 17:27:34.891  3714  4858 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-26 17:27:34.935  3714  5765 D SSRM:f  : SIOP:: AP = 310, PST = 313 (W:10), CP = 254, CUR = -16, LCD = 57
,07-26 17:27:35.117  3714  3776 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303377 mStackState=3 mControllerTxTimeMs=0 mControllerTxTimePerLevelMs=[] mControllerRxTimeMs=0 mControllerIdleTimeMs=0 mControllerEnergyUsed=0 }
,07-26 17:27:35.168 10315 10315 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-26 17:27:35.173  3714  3929 I WifiConnectivityManager: User band preference: 0
,07-26 17:27:35.177  3714  3929 D WifiConfigManager: Loading config and enabling all networks 
,07-26 17:27:35.208  3714  3929 D WifiConfigStore: readNetwork skipInternetCheck
,07-26 17:27:35.238  3714  3929 D WifiConfigStore: readNetwork skipInternetCheck
,07-26 17:27:35.260  3714  3929 D WifiConfigStore: readNetwork skipInternetCheck
,07-26 17:27:35.300  3714  3929 D WifiConfigStore: readNetwork skipInternetCheck
,07-26 17:27:35.330  3714  3929 D WifiConfigStore: readNetwork skipInternetCheck
,07-26 17:27:35.370  3714  3929 D WifiConfigStore: readNetwork skipInternetCheck
,07-26 17:27:35.392  3714  3929 W WifiNetworkHistory: Upgrading network 4 to android.uid.system:1000
,07-26 17:27:35.393  3714  3929 W WifiNetworkHistory: Upgrading network 0 to android.uid.system:1000
,07-26 17:27:35.394  3714  3929 W WifiNetworkHistory: Upgrading network 1 to android.uid.system:1000
07-26 17:27:35.395  3714  3929 W WifiNetworkHistory: Upgrading network 5 to android.uid.system:1000
07-26 17:27:35.396  3714  3929 W WifiNetworkHistory: Upgrading network 2 to android.uid.system:1000
07-26 17:27:35.397  3714  3929 W WifiNetworkHistory: Upgrading network 3 to android.uid.system:1000
,07-26 17:27:35.399  3714  3929 D WifiConfigManager: loaded 0 passpoint configs
,07-26 17:27:35.402  3714  4937 D WifiService: setWifiEnabled: true pid=9888, uid=10033
07-26 17:27:35.403  3714  4937 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-26 17:27:35.404  3714  4937 D WifiControlHistoryProvider: query
,07-26 17:27:35.407  3714  3714 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
,07-26 17:27:35.408  3714  3714 D WifiHs20Service: reason: 2
,07-26 17:27:35.408  3714  3955 I WifiHs20Service: Message received 5014
07-26 17:27:35.408  3714  3955 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
07-26 17:27:35.408  3714  3955 E WifiHs20Service: The changed config is NULL
,07-26 17:27:35.408  3714  3929 D WifiNative-wlan0: callSECApiBoolean - ID [301]
07-26 17:27:35.409 10315 10315 I wpa_supplicant: HOTSPOT20_ENABLE called ON
07-26 17:27:35.415  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-26 17:27:35.416  3714  4937 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-26 17:27:35.417  3714  4937 D SecContentProvider: called from android.uid.system:1000
07-26 17:27:35.418  3714  4937 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-26 17:27:35.422  3714  4937 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-26 17:27:35.423  3714  4937 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-26 17:27:35.426  3714  3929 D WifiNative-wlan0: callSECApiInt - ID [65]
,07-26 17:27:35.433  3714  3714 D WifiController: [FCC]setFccChannel() is called !!!
07-26 17:27:35.433  3714  3714 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
07-26 17:27:35.433  3714  3714 D WifiStateMachine: setFccChannel: channel = 0
07-26 17:27:35.434  3714  3714 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-26 17:27:35.434  3714  3954 D HS20StateMachine: WIFI_STATE_ENABLED
07-26 17:27:35.434  3714  3954 D HS20StateMachine: reloadCredentialsToSupplicant
07-26 17:27:35.434  3714  3954 D WifiHs20DBHandler: getCredentialIds
,07-26 17:27:35.435  3714  3714 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,07-26 17:27:35.435  3714  3955 I WifiHs20Service: Message received 5011
,07-26 17:27:35.437  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=3 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-26 17:27:35.442  3714  4040 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-26 17:27:35.444  3714  4040 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-26 17:27:35.445  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:35.445  3714  3714 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-26 17:27:35.445  3714  4483 D SLocation: checkWifiInfo
07-26 17:27:35.445  3714  4483 W SLocation: No Active Data Connection
,07-26 17:27:35.447  3714  3929 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,07-26 17:27:35.447 10315 10315 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
,07-26 17:27:35.452 10011 10011 D A2dpService: A2dpService - WIFI_STATE_ENABLED
07-26 17:27:35.452 10011 10011 I BluetoothA2dpServiceJni: Attempting to set busy level
,07-26 17:27:35.456  9888  9888 D BluetoothAdapter: STATE_ON
,07-26 17:27:35.459  9953  9953 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-26 17:27:35.459  9953  9953 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
07-26 17:27:35.460  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 17:27:35.460  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:35.460  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:35.460  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:27:35.460  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:27:35.460  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 17:27:35.460  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-26 17:27:35.460  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 17:27:35.460  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 17:27:35.461  3714  3954 D MountService: getExternalStorageMountMode : 1
07-26 17:27:35.461  3714  3954 D MountService: getExternalStorageMountMode : 3
07-26 17:27:35.461  3714  3954 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10114, packageName : com.samsung.hs20provider
,07-26 17:27:35.464  9888  9888 D BluetoothAdapter: STATE_ON
,07-26 17:27:35.467  9888  9888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,07-26 17:27:35.484 10353 10353 E Zygote  : v2
07-26 17:27:35.484 10353 10353 I libpersona: KNOX_SDCARD checking this for 10114
07-26 17:27:35.484 10353 10353 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:35.486 10353 10353 E Zygote  : accessInfo : 0
,07-26 17:27:35.489  3714  3954 I ActivityManager: Start proc 10353:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
,07-26 17:27:35.492  3714  3929 D WifiNative-HAL: Setting external_sim to 1
,07-26 17:27:35.493  9953  9953 D SecurityLogAgent: NetworkReceiver : SendSecurityReport is off
,07-26 17:27:35.493  3714  3929 D wifi    : setting dfs flag to true, 0x72508911e0
07-26 17:27:35.494  3714  3929 D WifiStateMachine: Setting OUI to DA-A1-19
07-26 17:27:35.494  3714  3929 D wifi    : setting scan oui 0x72508911e0
07-26 17:27:35.494  3714  3929 D WifiHAL : Sending mac address OUI
07-26 17:27:35.495  3714  3929 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
07-26 17:27:35.496  3714  3929 E WifiStateMachine: SupplicantStarted - enter() isAirplaneModeEnabled !!  
07-26 17:27:35.496 10353 10353 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-26 17:27:35.496  3714  3929 D WifiCountryCode: [setCountryCodeNative] Default CSC Country Code : PL
07-26 17:27:35.498 10353 10353 I SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
07-26 17:27:35.503  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.503  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.503  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.503  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.503  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.504  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.504  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:35.504  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.504  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.504  3714  4859 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:35.518  3714  4546 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.518  3714  4546 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:35.518  3714  4546 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.518  3714  4546 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:35.518  3714  4546 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.519  3714  4546 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.519  3714  4546 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.519  3714  4546 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.519  3714  4546 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.519  3714  4546 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:35.527 10353 10353 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:35.528 10353 10353 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:35.531  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.532  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.532  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:35.532  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.532  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
,07-26 17:27:35.532  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.532  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.532  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.532  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.532  3714  4936 W NetworkIdentity: Active mobile network without subscriber!
07-26 17:27:35.533  3714  4543 I ActivityManager: DSS on for com.samsung.hs20provider and scale is 1.0
,07-26 17:27:35.544 10315 10315 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-26 17:27:35.547  3714  3929 D WifiCountryCode: Succeeded to set country code to: PL
07-26 17:27:35.547  3714  3929 D wifi    : android_net_wifi_get_firmware_version = 0x72508911e0
07-26 17:27:35.547  3714  3929 E WifiHAL : Failed to register debug response; result = -95
07-26 17:27:35.547  3714  3929 E wifi    : Fail to get Firmware version
07-26 17:27:35.547  3714  3929 D wifi    : android_net_wifi_get_driver_version = 0x72508911e0
07-26 17:27:35.547  3714  3929 E WifiHAL : Failed to register debug response; result = -95
07-26 17:27:35.547  3714  3929 E wifi    : Fail to get driver version
07-26 17:27:35.547  3714  3929 D wifi    : android_net_wifi_set_log_handler = 0x72508911e0
07-26 17:27:35.547  3714  3929 D wifi    : android_net_wifi_get_ring_buffer_status = 0x72508911e0
,07-26 17:27:35.548  3714  3929 E WifiHAL : Failed to register debug response; result = -95
07-26 17:27:35.548  3714  3929 E WifiLogger: no ring buffers found
,07-26 17:27:35.548  3714  3929 D WifiHAL : Start get packet fate command
07-26 17:27:35.548  3714  3929 D WifiHAL : createRequest Monitor packet fate request
07-26 17:27:35.548  3714  3929 E WifiHAL : Failed to register get pkt fate response; result = -95
07-26 17:27:35.548  3714  3929 E WifiLogger: Failed to start packet fate monitoring
,07-26 17:27:35.550  3714  4016 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
,07-26 17:27:35.553 10353 10353 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,07-26 17:27:35.564 10353 10353 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:35.575  3714  3925 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-26 17:27:35.577  3714  3956 I WifiScanningService: wifi driver loaded with scan capabilities: max buckets=16
,07-26 17:27:35.578  3714  3714 D RttService: SCAN_AVAILABLE : 3
07-26 17:27:35.578  3714  3929 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-26 17:27:35.578  3714  3929 I WifiConnectivityManager: Set WiFi enabled
07-26 17:27:35.578  3714  3929 E WifiStateMachine: ConnectModeState - enter !! - mIsSupportGeofence !!
07-26 17:27:35.579  3714  3714 I WifiStateMachine: initGeofence
07-26 17:27:35.579  3298  3774 D CommandListener: Setting iface cfg
,07-26 17:27:35.579  3714  3958 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-26 17:27:35.579  3298  3774 D CommandListener: Trying to bring up p2p0
07-26 17:27:35.580  3298  3766 D Netd    : Iface p2p0 link up
,07-26 17:27:35.584  3714  3925 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-26 17:27:35.585  3714  3925 D SecContentProvider: insert(), uri = 2
07-26 17:27:35.585  3714  3795 D Tethering: interfaceLinkStateChanged p2p0, true
07-26 17:27:35.585  3714  3795 D Tethering: interfaceStatusChanged p2p0, true
,07-26 17:27:35.585  3714  3929 D WifiStateMachine: Remembered scan first is enabled
,07-26 17:27:35.586  3714  3929 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@298c388
,07-26 17:27:35.587  3714  3925 D SecContentProvider: called from android.uid.system:1000
07-26 17:27:35.587  3714  3929 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
07-26 17:27:35.587  3714  3925 D WifiP2pService: P2pEnablingState
07-26 17:27:35.587  3714  3929 E wifi    : failed to get channel list : -95
07-26 17:27:35.587  3714  3929 D WifiConfigManager: getChannelsForBand(WifiScanner.WIFI_BAND_24_GHZ) is null. So set default 2.4GHz 14 channels.
07-26 17:27:35.588  3714  3925 D WifiP2pService: P2pEnablingState{ what=147457 }
07-26 17:27:35.588  3714  3925 D WifiP2pService: P2p socket connection successful
07-26 17:27:35.589  3714  3925 D WifiP2pService: P2pEnabledState
07-26 17:27:35.589  3714  3925 D SecContentProvider: insert(), uri = 2
07-26 17:27:35.589 10315 10315 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-26 17:27:35.590 10315 10315 I wpa_supplicant: P2P: Current p2p state = IDLE
07-26 17:27:35.590  3714  3925 D SecContentProvider: called from android.uid.system:1000
07-26 17:27:35.590 10353 10365 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-26 17:27:35.590 10353 10365 D HotspotProvider: CREDENTIAL
07-26 17:27:35.590 10353 10365 D HotspotProvider: No prepend tags
07-26 17:27:35.592  3714  3797 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-26 17:27:35.592  3714  3797 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-26 17:27:35.593  3714  3797 D WifiDisplayController: disconnect
07-26 17:27:35.593  3714  3797 D WifiDisplayAdapter: onFeatureStateChanged empty
07-26 17:27:35.593  3714  3797 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-26 17:27:35.593  3714  3925 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-26 17:27:35.593  3714  3959 D ConnectivityService: ignoring duplicate network state non-change
07-26 17:27:35.595 10315 10315 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-26 17:27:35.600  3714  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T172750 - CU:1000/CP:3714
07-26 17:27:35.600  3714  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172750, SetElapsed=318875, nowELAPSED=303884
,07-26 17:27:35.602 10315 10315 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,07-26 17:27:35.602  3714  3797 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
,07-26 17:27:35.604 10315 10315 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,07-26 17:27:35.612  3714  3929 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170726T172743 - CU:1000/CP:3714
07-26 17:27:35.612  3714  3929 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172743, SetElapsed=311874, nowELAPSED=303897
07-26 17:27:35.613 10233 10233 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
07-26 17:27:35.613 10233 10233 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
07-26 17:27:35.613 10233 10233 D FileShare: Outbound.stopDelayTimer - 
,07-26 17:27:35.623  3714  3929 D WifiStateMachine: setFccChannelNative: channel = 0
,07-26 17:27:35.623  3714  3929 D WifiNative-wlan0: callSECApiInt - ID [230]
,07-26 17:27:35.624  4043  4318 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,07-26 17:27:35.627  3714  3929 D WifiNative-wlan0: callSECApiVoid - ID [311]
,07-26 17:27:35.630  3714  3954 D HS20StateMachine: updateNumOfHS20Cred, numOfHS20Cred = 1
07-26 17:27:35.630  3714  3954 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
07-26 17:27:35.630  3714  3954 D HS20StateMachine: enter : DiscoveringState
,07-26 17:27:35.635  3714  3929 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-26 17:27:35.639  3714  3929 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-26 17:27:35.643  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:35.649  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:35.652  5015  5059 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 3ms lastUpdatedAfter : 44809 ms mFlush_time_threasold : 2000 mCurrentSize : 184
,07-26 17:27:35.653  3714  3714 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
,07-26 17:27:35.654  3714  3714 D SLocation: system
,07-26 17:27:35.654  3714  3714 D SLocation: startGeofence ID = 1
07-26 17:27:35.654  3714  3925 E WifiP2pService: Failed to set my phone number info into probe response
,07-26 17:27:35.659  3714  3925 D WifiNative-HAL: p2pGetDeviceAddress
,07-26 17:27:35.660  3714  3925 D WifiNative-HAL: p2pGetDeviceAddress returning 4e:66:41:a9:15:41
07-26 17:27:35.660  3714  3925 D WifiP2pService: DeviceAddress: 4e:15:41
,07-26 17:27:35.661  3714  3797 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:15:41
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  primary type: 10-0050F204-5
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  secondary type: null
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  wps: 0
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  grpcapab: 0
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  devcapab: 0
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  status: 3
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  WFD CtrlPort: 0
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  WFD MaxThroughput: 0
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  groupownerAddress: null
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  GOdeviceName: null
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  interfaceAddress: 
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  SConnectInfo : null
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  contactInfoHash : null
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  ssDevInfo : 0
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  iconIdx : 0
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  semSamsungDeviceType : 0
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  serviceData : null
07-26 17:27:35.661  3714  3797 D WifiDisplayController:  fw_invite : 0
,07-26 17:27:35.670  3714  3925 D WifiP2pService: sending p2p persistent groups changed broadcast
07-26 17:27:35.670  3714  3925 D WifiP2pService: InactiveState
,07-26 17:27:35.670  3714  3925 D WifiP2pService: InactiveState{ what=143376 }
07-26 17:27:35.671  3714  3925 D WifiP2pService: P2pEnabledState{ what=143376 }
07-26 17:27:35.671  3714  3925 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,07-26 17:27:35.687  3714  3714 D SLocation: addReceiver type4
07-26 17:27:35.687  3714  3714 D SLocation: already exsit record!
,07-26 17:27:35.718  3714  3714 D SLocation: setPendingIntent
07-26 17:27:35.718  3714  3714 D SLocation: setStatus ID = 1 / status = 3
,07-26 17:27:35.782  3714  3714 D SLocation: geofence id (1) detected : 0
,07-26 17:27:35.782  3714  3714 D WifiStateMachine: startGeofence() - id : 1
,07-26 17:27:35.788  3714  3714 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
,07-26 17:27:35.788  3714  3714 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
,07-26 17:27:35.791  4043  4318 D TelephonyProvider: query: match = 7
07-26 17:27:35.793  3714  3714 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,07-26 17:27:35.798  3714  3714 D SLocation: PendingIntent onSendFinished id:1
,07-26 17:27:35.939  9888  9983 D BluetoothAdapter: STATE_ON
,07-26 17:27:35.948  9888  9983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 17:27:35.948  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:35.948  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:35.948  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:27:35.948  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:27:35.948  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 17:27:35.948  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-26 17:27:35.948  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 17:27:35.948  9888  9983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 17:27:35.949  9888  9951 D BluetoothAdapter: enable()
,07-26 17:27:35.960 10011 10033 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-26 17:27:35.961 10011 10033 D AdapterProvider: query
,07-26 17:27:35.979 10011 10033 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@17a1f83
,07-26 17:27:35.983 10011 10033 D BluetoothAdapterService: updateEvent - already set, update
,07-26 17:27:35.984 10011 10033 W BluetoothAdapterService: updateEvent - alreadySet is true
,07-26 17:27:35.985 10011 10033 D AdapterProvider: update
,07-26 17:27:35.992 10011 10033 E BluetoothAdapterService: updateEvent - update success 1
,07-26 17:27:35.993  9888  9951 D BluetoothAdapter: enable(): BT is already enabled..!
,07-26 17:27:36.001  3714 10158 D WifiService: setWifiEnabled: true pid=9888, uid=10033
07-26 17:27:36.001  3714 10158 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-26 17:27:36.002  3714 10158 D WifiControlHistoryProvider: query
,07-26 17:27:36.010  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-26 17:27:36.011  3714 10158 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-26 17:27:36.012  3714 10158 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:36.013  3714 10158 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-26 17:27:36.017  3714 10158 I WifiService: Wi-Fi Sharing settings has not been accessed
07-26 17:27:36.018  3714 10158 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-26 17:27:36.019  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 17:27:36.019  9888  9951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 17:27:36.019  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 17:27:36.019  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-26 17:27:36.019  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-26 17:27:36.019  9888  9951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8beaab2 removed from the list
07-26 17:27:36.019  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8beaab2 removed from the list
07-26 17:27:36.020  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 17:27:36.020  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8dd1a03 removed from the list
07-26 17:27:36.020  9888  9951 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 17:27:36.020  9888  9951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 17:27:36.020  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 17:27:36.023  9888  9951 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,07-26 17:27:36.027  9888 10367 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
07-26 17:27:36.027  9888 10367 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-26 17:27:36.031  3298  3769 D EnterpriseController: netId is 0
07-26 17:27:36.031  3298  3769 D Netd    : getNetworkForDns: using netid 0 for uid 10033
07-26 17:27:36.031  3298  3769 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-26 17:27:36.035  9888 10369 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
07-26 17:27:36.035  9888 10367 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,07-26 17:27:36.038  9888 10367 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
07-26 17:27:36.038  9888 10369 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
07-26 17:27:36.038  9888 10369 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-26 17:27:36.038  9888 10367 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-26 17:27:36.039  9888 10369 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-26 17:27:36.039  9888 10367 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-26 17:27:36.040  9888 10369 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,07-26 17:27:36.041  9888 10367 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
07-26 17:27:36.041  9888 10371 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 222, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.041  9888 10371 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:36.041  9888 10371 D io.jxcore.node.StreamCopyingThread:  id: 74
07-26 17:27:36.041  9888 10372 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 223, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.041  9888 10372 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:36.041  9888 10372 D io.jxcore.node.StreamCopyingThread:  id: 75
07-26 17:27:36.042  9888 10373 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 224, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.042  9888 10373 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:36.042  9888 10373 D io.jxcore.node.StreamCopyingThread:  id: 74
,07-26 17:27:36.042  9888 10373 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 224, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.042  9888 10373 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:36.042  9888 10373 D io.jxcore.node.StreamCopyingThread:  id: 74
07-26 17:27:36.042  9888 10373 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.042  9888 10373 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:36.042  9888 10373 D io.jxcore.node.StreamCopyingThread:  id: 74
07-26 17:27:36.042  9888 10373 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-26 17:27:36.042  9888 10373 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-26 17:27:36.043  9888 10371 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 222, thread name: IncomingSocketThread/Sender): Socket closed
07-26 17:27:36.043  9888 10371 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 222, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.043  9888 10371 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:36.043  9888 10371 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,07-26 17:27:36.043  9888 10371 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-26 17:27:36.043  9888 10371 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-26 17:27:36.043  9888 10371 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 222, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.043  9888 10371 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:36.043  9888 10371 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-26 17:27:36.044  9888 10373 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 223, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread:  id: 75
,07-26 17:27:36.044  9888 10373 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-26 17:27:36.044  9888 10373 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-26 17:27:36.044  9888 10373 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread:  id: 75
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-26 17:27:36.044  9888 10373 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 224, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.044  9888 10373 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:36.044  9888 10373 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-26 17:27:36.044  9888 10372 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 223, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:36.044  9888 10372 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-26 17:27:36.045  9888 10374 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 225, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.045  9888 10374 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:36.045  9888 10374 D io.jxcore.node.StreamCopyingThread:  id: 75
07-26 17:27:36.045  9888 10374 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 225, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.045  9888 10374 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:36.045  9888 10374 D io.jxcore.node.StreamCopyingThread:  id: 75
07-26 17:27:36.045  9888 10374 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.045  9888 10374 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:36.045  9888 10374 D io.jxcore.node.StreamCopyingThread:  id: 75
07-26 17:27:36.045  9888 10374 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-26 17:27:36.045  9888 10374 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,07-26 17:27:36.047  9888 10374 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-26 17:27:36.047  9888 10374 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-26 17:27:36.047  9888 10374 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-26 17:27:36.047  9888 10374 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
07-26 17:27:36.047  9888 10374 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
07-26 17:27:36.048  9888 10374 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 225, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:36.048  9888 10374 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:36.048  9888 10374 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,07-26 17:27:36.177  3298  3766 D Netd    : Iface wlan0 link up
,07-26 17:27:36.180 10315 10315 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
07-26 17:27:36.181  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:27:36.181  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
,07-26 17:27:36.186  3714  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@41d0e48
,07-26 17:27:36.233  3714  3929 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-26 17:27:36.245  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:37.460  5160  5168 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-26 17:27:37.464  4779  4779 I BeaconBle: 'L' hardware scan: scan stopped, no clients
,07-26 17:27:37.808  3714  3739 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{2e61bf: PendingIntentRecord{e42008c com.google.android.gms broadcastIntent}}
,07-26 17:27:38.161  3714  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-26 17:27:39.147  4649  4649 D io_stats: !@   8,0 r 26199 2301360 w 5270 207764 d 687 74000 f 2121 2121 iot 12020 11117 th 476328 0 0 pt 0 inp 0 0 307.431
,07-26 17:27:41.532  9888  9951 I io.jxcore.node.IncomingSocketThreadTest: testRun
07-26 17:27:41.533  9888  9951 I !!      :  finally closed
,07-26 17:27:41.538  9888  9951 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,07-26 17:27:41.539  9888  9951 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-26 17:27:41.543  9888  9951 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
07-26 17:27:41.543  9888  9951 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-26 17:27:41.547  9888  9951 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,07-26 17:27:41.553  9888  9951 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
07-26 17:27:41.553  9888  9951 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@4137ff3 Bundle[{}]
,07-26 17:27:41.557  9888  9951 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,07-26 17:27:41.558  9888  9951 I io.jxcore.node.LifeCycleMonitor: start: OK
07-26 17:27:41.558  9888  9951 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-26 17:27:41.561  9888  9951 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
07-26 17:27:41.561  9888  9951 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-26 17:27:41.563  9888  9951 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
07-26 17:27:41.563  9888  9951 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-26 17:27:41.566  9888  9951 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,07-26 17:27:41.566  9888  9951 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-26 17:27:41.568  9888  9951 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
07-26 17:27:41.569  9888  9951 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-26 17:27:41.571  9888  9951 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,07-26 17:27:41.573  9888  9951 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,07-26 17:27:41.576  9888  9951 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,07-26 17:27:41.578  9888  9951 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,07-26 17:27:41.580  9888  9951 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,07-26 17:27:41.582  9888  9951 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,07-26 17:27:41.584  9888  9951 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,07-26 17:27:41.587  9888 10376 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
07-26 17:27:41.587  9888 10376 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-26 17:27:41.590  3298  3769 D EnterpriseController: netId is 0
07-26 17:27:41.590  3298  3769 D Netd    : getNetworkForDns: using netid 0 for uid 10033
07-26 17:27:41.590  3298  3769 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-26 17:27:41.594  9888 10378 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
07-26 17:27:41.594  9888 10378 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
07-26 17:27:41.594  9888 10378 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-26 17:27:41.594  9888 10376 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
07-26 17:27:41.594  9888 10376 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
07-26 17:27:41.594  9888 10378 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-26 17:27:41.595  9888 10376 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-26 17:27:41.595  9888 10378 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
07-26 17:27:41.595  9888 10376 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-26 17:27:41.596  9888 10376 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,07-26 17:27:41.598  9888 10381 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 230, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.598  9888 10381 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:41.598  9888 10381 D io.jxcore.node.StreamCopyingThread:  id: 77
07-26 17:27:41.598  9888 10380 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 229, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.598  9888 10380 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:41.598  9888 10380 D io.jxcore.node.StreamCopyingThread:  id: 77
07-26 17:27:41.598  9888 10382 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 231, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.598  9888 10382 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:41.598  9888 10382 D io.jxcore.node.StreamCopyingThread:  id: 78
,07-26 17:27:41.606  9888 10383 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 232, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.606  9888 10383 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:41.606  9888 10383 D io.jxcore.node.StreamCopyingThread:  id: 78
,07-26 17:27:41.607  9888 10383 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 232, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.607  9888 10383 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:41.607  9888 10383 D io.jxcore.node.StreamCopyingThread:  id: 78
07-26 17:27:41.607  9888 10383 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.607  9888 10383 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:41.607  9888 10383 D io.jxcore.node.StreamCopyingThread:  id: 78
07-26 17:27:41.607  9888 10383 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-26 17:27:41.607  9888 10383 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-26 17:27:41.607  9888 10383 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-26 17:27:41.608  9888 10383 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-26 17:27:41.608  9888 10381 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 230, thread name: IncomingSocketThread/Receiver): Broken pipe
,07-26 17:27:41.608  9888 10383 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-26 17:27:41.608  9888 10380 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 229, thread name: IncomingSocketThread/Sender): Connection reset
07-26 17:27:41.608  9888 10383 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
07-26 17:27:41.608  9888 10381 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 230, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.608  9888 10381 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:41.608  9888 10381 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 163840 and the total number of bytes written 159744
07-26 17:27:41.608  9888 10380 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 229, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.608  9888 10380 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:41.608  9888 10380 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-26 17:27:41.608  9888 10381 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: Broken pipe", this is likely due to peer having disconnected
07-26 17:27:41.608  9888 10381 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
07-26 17:27:41.608  9888 10380 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Connection reset
07-26 17:27:41.608  9888 10380 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-26 17:27:41.608  9888 10383 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 232, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.608  9888 10383 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:41.608  9888 10383 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-26 17:27:41.608  9888 10381 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 230, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.608  9888 10381 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:41.608  9888 10381 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 163840 and the total number of bytes written 159744
07-26 17:27:41.608  9888 10380 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 229, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.608  9888 10380 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-26 17:27:41.608  9888 10380 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,07-26 17:27:41.610  9888 10382 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 231, thread name: OutgoingSocketThread/Sender): Socket closed
07-26 17:27:41.610  9888 10382 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 231, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.610  9888 10382 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:41.610  9888 10382 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 16384 and the total number of bytes written 16384
07-26 17:27:41.610  9888 10382 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-26 17:27:41.610  9888 10382 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-26 17:27:41.610  9888 10382 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 231, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:27:41.610  9888 10382 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:27:41.610  9888 10382 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 16384 and the total number of bytes written 16384
,07-26 17:27:43.590  3714  3864 D SamsungAlarmManager: Expired : 4
07-26 17:27:43.591  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T175733, SetElapsed=2101598, nowELAPSED=311875
,07-26 17:27:43.591  3714  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@e6934e1 alarm=Alarm{68d13d5 type 2 when 311874 android}
,07-26 17:27:43.597  3714  3929 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 16000: mInRange : true
,07-26 17:27:43.601 10315 10315 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-26 17:27:43.601 10315 10315 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-26 17:27:43.603  3714  3929 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T172759 - CU:1000/CP:3714
07-26 17:27:43.603  3714  3929 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172759, SetElapsed=327882, nowELAPSED=311888
,07-26 17:27:43.608  3714  3929 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-26 17:27:43.609  3714  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T172758 - CU:1000/CP:3714
,07-26 17:27:43.624  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:43.655 10315 10315 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-26 17:27:43.687  3714  3878 I TLC_TIMA_PKM_initialize: initializing...
07-26 17:27:43.688  3714  3878 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
07-26 17:27:43.688  3714  3878 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
07-26 17:27:43.688  3714  3878 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
07-26 17:27:43.688  3714  3878 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
07-26 17:27:43.688  3714  3878 I TZ: mc_tlc_communication: root = 0, root_len = 1
07-26 17:27:43.688  3714  3878 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
07-26 17:27:43.688  3714  3878 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
07-26 17:27:43.688  3714  3878 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
07-26 17:27:43.688  3714  3878 I TZ: mc_tlc_communication: device_id = 0x0
07-26 17:27:43.688  3714  3878 I TZ: mc_tlc_communication: tlc_open() was called
07-26 17:27:43.688  3714  3878 I TZ: mc_tlc_communication: Opening MobiCore device
07-26 17:27:43.688  3714  3878 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,07-26 17:27:43.689  3714  3878 I TZ: mc_tlc_communication: Opening the session
,07-26 17:27:43.731  3714  3878 I TZ: mc_tlc_communication: tlc_open() succeeded
07-26 17:27:43.731  3714  3878 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,07-26 17:27:43.763  3714  3878 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,07-26 17:27:43.769  3714  3878 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,07-26 17:27:43.774  3714  3878 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,07-26 17:27:43.779  3714  3878 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-26 17:27:44.151  4649  4649 D io_stats: !@   8,0 r 26206 2302056 w 5281 207852 d 688 74004 f 2122 2122 iot 12030 11123 th 476980 0 0 pt 0 inp 0 0 312.434
,07-26 17:27:44.187  3714  3929 E WifiStateMachine: DisconnectedState  CMD_THREE_TIMES_SCAN_IN_IDLE && mScreenOn
,07-26 17:27:44.191  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=-3ms what=131308 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-26 17:27:44.967  3714  5765 D SSRM:f  : SIOP:: AP = 300, PST = 315 (W:10), CP = 253, CUR = -6, LCD = 57
,07-26 17:27:45.407  3714  3714 D UsbMonitorService: readUsbState++
,07-26 17:27:45.409  3714  3714 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-26 17:27:45.411  3714  3714 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-26 17:27:45.411  3714  3714 D UsbMonitorService: Posting Message again
,07-26 17:27:45.433  3298  3766 D Netd    : Iface wlan0 link up
,07-26 17:27:45.436 10315 10315 I wpa_supplicant: nl80211: Received scan results (50 BSSes)
,07-26 17:27:45.436  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:27:45.436  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
,07-26 17:27:45.443  3714  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@8715adb
,07-26 17:27:45.503  3714  3714 D WifiDefaultApController: checkDefaultAptoCopy: mNeedtoAddVendorAp( REQEUST_FROM_REBOOT ) general info file exists? ( false )
,07-26 17:27:45.506 10315 10315 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-26 17:27:45.506  3714  3929 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-26 17:27:45.506 10315 10315 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-26 17:27:45.518  3714  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T172800 - CU:1000/CP:3714
07-26 17:27:45.519  3714  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172800, SetElapsed=328797, nowELAPSED=313803
,07-26 17:27:45.532  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:45.537 10315 10315 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-26 17:27:45.547  3714  3929 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=4 roam=false
,07-26 17:27:45.549  3714  3929 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=4
,07-26 17:27:45.570  3714  3929 D WifiConfigStore: saveNetwork skipInternetCheck
,07-26 17:27:45.596  3714  3929 D WifiConfigStore: readNetwork skipInternetCheck
,07-26 17:27:45.621  3714 10384 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
07-26 17:27:45.621  3714 10384 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-26 17:27:45.621  3714 10384 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
,07-26 17:27:45.622  3714 10384 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-26 17:27:45.622  3714 10384 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-26 17:27:45.622  3714 10384 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-26 17:27:45.622  3714 10384 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-26 17:27:45.622  3714 10384 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-26 17:27:45.623  3714 10384 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-26 17:27:45.623  3714 10384 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
,07-26 17:27:45.623  3714 10384 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-26 17:27:45.623  3714 10384 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
,07-26 17:27:45.631  3714  3929 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=4
,07-26 17:27:45.632  3714  3714 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-26 17:27:45.632  3714  3714 D WifiHs20Service: reason: 2
07-26 17:27:45.632  3714  3955 I WifiHs20Service: Message received 5014
07-26 17:27:45.632  3714  3955 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,07-26 17:27:45.635  3714 10385 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
07-26 17:27:45.636  3714 10385 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-26 17:27:45.636  3714 10385 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-26 17:27:45.636  3714 10385 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
,07-26 17:27:45.636  3714 10385 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-26 17:27:45.637  3714 10385 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-26 17:27:45.637  3714 10385 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-26 17:27:45.637 10315 10315 I wpa_supplicant: Trying to associate with F4.E6.C2 (SSID='NG700' freq=2472 MHz)
07-26 17:27:45.637  3714 10385 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-26 17:27:45.637  3714 10385 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-26 17:27:45.637  3714 10385 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-26 17:27:45.638  3714 10385 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-26 17:27:45.638  3714 10385 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
07-26 17:27:45.639  3714  3929 D SecContentProvider: insert(), uri = 2
07-26 17:27:45.640  3714  3929 D SecContentProvider: called from android.uid.system:1000
,07-26 17:27:45.661 10315 10315 I wpa_supplicant: Scan aborted because the firmware maybe busy.
07-26 17:27:45.661 10315 10315 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
07-26 17:27:45.661 10315 10315 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,07-26 17:27:45.662  3714  3929 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-26 17:27:45.671  3714  3929 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-26 17:27:45.671  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:45.683  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:45.757  3298  3766 D Netd    : Iface wlan0 link up
,07-26 17:27:45.757  3298  3766 D Netd    : Iface wlan0 link up
,07-26 17:27:45.757  3298  3766 D Netd    : Iface wlan0 link up
,07-26 17:27:45.760  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:27:45.760  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
07-26 17:27:45.763  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:27:45.763  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
07-26 17:27:45.766  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:27:45.766  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
,07-26 17:27:45.773 10315 10315 I wpa_supplicant: Associated with F4.E6.C2
,07-26 17:27:45.776 10315 10315 I wpa_supplicant: wlan0: CTRL-EVENT-SUBNET-STATUS-UPDATE status=0
,07-26 17:27:45.780  3714  3929 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-26 17:27:45.784  3714  3929 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-26 17:27:45.792  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:45.797 10315 10315 I wpa_supplicant: WPA: Key negotiation completed with F4.E6.C2 [PTK=CCMP GTK=CCMP]
07-26 17:27:45.797 10315 10315 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.E6.C2 completed [id=4 id_str=%7B%22creatorUid%22%3A%221000%22%2C%22configKey%22%3A%22%5C%22NG700%5C%22WPA_PSK%22%7D]
07-26 17:27:45.798  3298  3766 D Netd    : Iface wlan0 link up
07-26 17:27:45.799  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 17:27:45.800  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:27:45.800  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
07-26 17:27:45.802  3714  3929 D WifiNative-wlan0: callSECApiVoid - ID [50]
,07-26 17:27:45.807  3714  3929 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@1da87ea
,07-26 17:27:45.809  3714  3714 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-26 17:27:45.810  3714  3714 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-26 17:27:45.810  3714  3955 I WifiHs20Service: Message received 5007
,07-26 17:27:45.812  3714  4016 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,07-26 17:27:45.812  3714  3929 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: mIsSupportAdvancedCaptivePortal is true
07-26 17:27:45.813  3714 10386 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-1ms what=69632 obj=com.android.internal.util.AsyncChannel@9d48089 target=com.android.internal.util.StateMachine$SmHandler }
07-26 17:27:45.813  3714 10386 D NetworkMonitor: Async - Half connection with WWSM established
07-26 17:27:45.813  3714  3929 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-26 17:27:45.814  3714  3959 D ConnectivityService: Got NetworkAgent Messenger
07-26 17:27:45.814  3714  3959 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-26 17:27:45.814  3714  3959 D ConnectivityService: NetworkAgent connected
07-26 17:27:45.814  3714  4016 D WifiWatchdogStateMachine: Async - Half connection with NetworkMonitor established
07-26 17:27:45.814  3714  4016 D WifiWatchdogStateMachine: Async - Full connection with NetworkMonitor established
07-26 17:27:45.816  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:45.818  4043  4043 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
07-26 17:27:45.821  3714  3925 D WifiP2pService: InactiveState{ what=143375 }
07-26 17:27:45.821  3714  3925 D WifiP2pService: P2pEnabledState{ what=143375 }
07-26 17:27:45.821 10011 10011 D BluetoothUtils: readSalesCode :: sales code is XEO
07-26 17:27:45.821  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-26 17:27:45.822  3714  3929 D WifiHAL : Getting APF capabilities, halHandle = 0x72508911e0
07-26 17:27:45.822  3714  3929 I WifiHAL : 
07-26 17:27:45.822  3714  3929 I WifiHAL : createRequest: APF get capabilities request
07-26 17:27:45.824  3714  3929 D WifiHAL : In SetAPFCommand::handleResponse
07-26 17:27:45.824  3714  3929 D WifiHAL : Id = 0, subcmd = 0, len = 16
07-26 17:27:45.824  3714  3929 D WifiHAL : Response recieved for get packet filter capabilities command
07-26 17:27:45.824  3714  3929 I WifiHAL : APF version is 2
07-26 17:27:45.824  3714  3929 I WifiHAL : APF max len is 2048
07-26 17:27:45.824  3714  3929 I WifiHAL : Done!
07-26 17:27:45.824  3714  3929 D WifiHAL : Getting APF capability, version = 2, max_len = 2048
07-26 17:27:45.824  3714  3929 D wifi    : APF version supported: 2
07-26 17:27:45.824  3714  3929 D wifi    : Maximum APF program size: 2048
07-26 17:27:45.830  3714  3929 D WifiStateMachine: Start Dhcp Watchdog 2
07-26 17:27:45.838 10178 10178 I [RBL] ServiceReceiver: @onReceive - rawData : null
07-26 17:27:45.840  3714  3929 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-26 17:27:45.857  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:45.863 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-26 17:27:45.864 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-26 17:27:45.864 10193 10193 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
,07-26 17:27:45.865 10193 10193 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-26 17:27:45.872  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:45.873  3714  3929 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true)
07-26 17:27:45.873  3714  3959 D ConnectivityService: ignoring duplicate network state non-change
07-26 17:27:45.874  3714  3929 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true) returned: -95
07-26 17:27:45.874  3714  3959 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
,07-26 17:27:45.874  3714  3959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-26 17:27:45.874  3714  3959 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
07-26 17:27:45.874  3714  3929 D WifiHAL : Setting APF program, halHandle = 0x72508911e0
07-26 17:27:45.874  3714  3929 I WifiHAL : 
07-26 17:27:45.874  3714  3929 I WifiHAL : createRequest: APF set program request
07-26 17:27:45.876  3714  3929 I WifiHAL : Done!
07-26 17:27:45.877  3714  3929 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-26 17:27:45.880 10207 10207 I PhoneErrorReceiver: onReceive
,07-26 17:27:45.886  3714 10387 D ApfFilter: (wlan0): begin monitoring
07-26 17:27:45.887  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 17:27:45.895 10220 10220 I usagelog: received in receiver
07-26 17:27:45.895 10220 10220 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-26 17:27:45.895 10220 10220 I KnoxUsageLogPro: premStatus:2
,07-26 17:27:45.896 10220 10220 I KnoxUsageLogPro: isEulaShown : false
07-26 17:27:45.896 10220 10220 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-26 17:27:45.899 10315 10315 I wpa_supplicant: Interworking: Fetch ANQP after connect
,07-26 17:27:45.930  3714  3934 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170726T172821 - CU:1000/CP:3714
,07-26 17:27:45.932  3714  3959 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
,07-26 17:27:45.932  3714  4016 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-26 17:27:45.933  3714  4016 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-26 17:27:45.933  3714  4016 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
,07-26 17:27:45.933  3714  4016 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-26 17:27:45.934  3714  4016 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-26 17:27:45.972  3714  3934 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170726T172821 - CU:1000/CP:3714
,07-26 17:27:46.099  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=131307 obj=start target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-26 17:27:46.099  3714  3925 D WifiP2pService: InactiveState{ what=143375 }
07-26 17:27:46.100  3714  3925 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-26 17:27:46.111  3714 10388 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170726T172748 - CU:1000/CP:3714
07-26 17:27:46.112  3714 10388 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172748, SetElapsed=316416, nowELAPSED=314396
07-26 17:27:46.113  3714 10388 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
07-26 17:27:46.113  3714 10388 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@cbd62bb
,07-26 17:27:46.116  3714 10388 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172800, SetElapsed=328797, nowELAPSED=314400
,07-26 17:27:46.121  3714 10388 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170726T172804 - CU:1000/CP:3714
,07-26 17:27:46.132  3714 10388 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170726T172748 - CU:1000/CP:3714
07-26 17:27:46.132  3714 10388 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172748, SetElapsed=316468, nowELAPSED=314417
,07-26 17:27:46.133  3714 10388 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
07-26 17:27:46.134  3714  3934 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@e1520b5
07-26 17:27:46.134  3714 10388 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@2bb4a16
,07-26 17:27:46.137  3714 10388 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172800, SetElapsed=328797, nowELAPSED=314422
07-26 17:27:46.138  3714 10388 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@b441331
,07-26 17:27:46.140  3714  3925 D WifiP2pService: InactiveState{ what=143375 }
07-26 17:27:46.141  3298  3774 D CommandListener: Setting iface cfg
07-26 17:27:46.142  3714  3925 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-26 17:27:46.148  3714  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-26 17:27:46.149  3714  3959 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-26 17:27:46.150  3714  3959 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
,07-26 17:27:46.151  3714  4016 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-26 17:27:46.151  3714  4016 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-26 17:27:46.152  3714  4016 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
,07-26 17:27:46.152  3714  4016 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-26 17:27:46.155  3714  3714 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-26 17:27:46.155  3714  4016 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-26 17:27:46.155  3714  3714 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-26 17:27:46.156  3714  3955 I WifiHs20Service: Message received 5007
07-26 17:27:46.157  3714  3929 D WifiHAL : Setting APF program, halHandle = 0x72508911e0
07-26 17:27:46.158  3714  3929 I WifiHAL : 
07-26 17:27:46.158  3714  3929 I WifiHAL : createRequest: APF set program request
07-26 17:27:46.159  3714  4016 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,07-26 17:27:46.161  3714  3934 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@8a0b4ec
07-26 17:27:46.162  3714  3929 I WifiHAL : Done!
,07-26 17:27:46.164  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:46.164  4043  4043 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
07-26 17:27:46.167  3714  3959 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
07-26 17:27:46.167  3714  3959 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-26 17:27:46.168 10011 10011 D BluetoothUtils: readSalesCode :: sales code is XEO
07-26 17:27:46.168  3714  4016 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-26 17:27:46.169  3714  3929 E WifiNative-HAL: setBssidBlacklist cmd 2 size 0
,07-26 17:27:46.169  3714  3929 D wifi    : configure BSSID black list request [4] = 0x72508911e0
07-26 17:27:46.169  3714  3929 D wifi    : Added 0 bssids
07-26 17:27:46.169  3714  3929 E WifiHAL : Failed to execute bssid blacklist request, result = -95
,07-26 17:27:46.169  3714  4016 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-26 17:27:46.169  3714  3929 D WifiStateMachine: sendConnectedState - setManualConnection: false!
07-26 17:27:46.170  3714  4016 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-26 17:27:46.170  3714  3959 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-26 17:27:46.170  3714  4016 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-26 17:27:46.174  3714  3959 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
07-26 17:27:46.174  3714  3959 D ConnectivityService: Adding iface wlan0 to network 503
07-26 17:27:46.178  3714 10388 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170726T231322 - CU:1000/CP:3714
,07-26 17:27:46.188 10178 10178 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-26 17:27:46.192  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:46.193  3714 10388 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170727T035746 - CU:1000/CP:3714
,07-26 17:27:46.195  3244  3244 E audit   : type=1320 audit(1501082866.175:552): 
,07-26 17:27:46.204  3714 10388 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170727T052746 - CU:1000/CP:3714
07-26 17:27:46.205  3714 10388 D DhcpClient: Scheduling renewal in 20735s
07-26 17:27:46.205  3714 10388 D DhcpClient: Scheduling rebind in 37799s
07-26 17:27:46.205  3714 10388 D DhcpClient: Scheduling expiry in 43199s
,07-26 17:27:46.213 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-26 17:27:46.213  3244  3244 E audit   : type=1320 audit(1501082866.195:553): 
,07-26 17:27:46.214 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-26 17:27:46.214 10193 10193 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-26 17:27:46.217  3714  3929 D SecContentProvider: insert(), uri = 2
07-26 17:27:46.217  3714  3959 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
07-26 17:27:46.219 10193 10193 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-26 17:27:46.220  3714  3929 D SecContentProvider: called from android.uid.system:1000
07-26 17:27:46.220  3714  3959 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
07-26 17:27:46.221  3714  3929 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-26 17:27:46.222  3714  3714 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-26 17:27:46.222  3714  3929 I WifiConnectivityManager: scheduleWatchdogTimer
07-26 17:27:46.223  3714  3714 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-26 17:27:46.223  3714  3714 D HS20StateMachine: SSID : "NG700"
07-26 17:27:46.223  3714  3714 D HS20StateMachine: NetId : 4
07-26 17:27:46.224  3714  3714 D HS20StateMachine: checkifOSUAP  null
07-26 17:27:46.224  3714  3959 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
07-26 17:27:46.226  3714  3714 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-26 17:27:46.226  3714  3955 I WifiHs20Service: Message received 5007
07-26 17:27:46.227  3714  3959 D ConnectivityService: Setting DNS servers for network 503 to [/192.168.1.1]
07-26 17:27:46.227  3714  4016 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-26 17:27:46.229  3298  4164 D ResolverController: DNSDBG::server[0] 192.168.1.1
07-26 17:27:46.229  3298  4164 D ResolverController: DNSDBG::netId 503 search_domain lan
07-26 17:27:46.229  3298  4164 D ResolverController: DNSDBG::netId 503 searchDomains lan
07-26 17:27:46.229  3298  4164 D ResolverController: DNSDBG::server[0] 192.168.1.1
,07-26 17:27:46.231  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:46.232  4043  4043 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-26 17:27:46.235 10011 10011 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-26 17:27:46.246  3714  3929 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T174746 - CU:1000/CP:3714
,07-26 17:27:46.247 10207 10207 I PhoneErrorReceiver: onReceive
07-26 17:27:46.249  3714  3959 V NetworkStats: updateIfacesLocked()
07-26 17:27:46.249  3714  3959 V NetworkStats: performPollLocked(flags=0x1)
07-26 17:27:46.249  3714  3959 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:46.258  3714  3959 V NetworkStats: performPollLocked() took 10ms
07-26 17:27:46.259  3714  3959 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:46.259  3714  3929 D WifiStateMachine: isFindLocationId() - Location Id : 1
07-26 17:27:46.262  3714  3929 D WifiGeofenceDBHelper: update() - 1*1501082866259
07-26 17:27:46.265 10220 10220 I usagelog: received in receiver
07-26 17:27:46.265 10220 10220 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-26 17:27:46.265 10220 10220 I KnoxUsageLogPro: premStatus:2
07-26 17:27:46.266 10220 10220 I KnoxUsageLogPro: isEulaShown : false
07-26 17:27:46.266 10220 10220 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-26 17:27:46.266  3714  3959 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-26 17:27:46.266  3714  3959 D ConnectivityService: Not required to send intent.
07-26 17:27:46.267  3714  3959 V NetworkStats: updateIfacesLocked()
07-26 17:27:46.267  3714  3959 V NetworkStats: performPollLocked(flags=0x1)
,07-26 17:27:46.267  3714  3959 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:46.271  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:46.272  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:46.275  3714  3959 V NetworkStats: performPollLocked() took 8ms
07-26 17:27:46.275  3714  3959 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 17:27:46.298 10178 10178 I [RBL] ServiceReceiver: @onReceive - rawData : null
07-26 17:27:46.298 10178 10178 W [RBL] ServiceReceiver: @onReceive - NETWORK_STATE_CHANGED_ACTION
07-26 17:27:46.301  3714  3959 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
07-26 17:27:46.301  3714 10386 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-26 17:27:46.301  3714  3959 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-26 17:27:46.301  3714 10386 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
07-26 17:27:46.302  3714  3959 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-26 17:27:46.302  3714 10386 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: register CaptivePortalReceiver
07-26 17:27:46.302  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.302  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.302  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.302  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-26 17:27:46.302  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.302  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:46.302  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.302  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.302  3714  3959 D ConnectivityService: currentScore = 0, newScore = 20
07-26 17:27:46.302  3714  3959 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
07-26 17:27:46.302  3714  3959 D ConnectivityService:    accepting network in place of null
07-26 17:27:46.302  3714  3959 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.304  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:46.304  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:46.305  4043  4043 D PhoneSwitcherNetworkRequstListener: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.305  4043  4043 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-26 17:27:46.305  4043  4043 D PhoneSwitcherNetworkRequstListener: evalRequest
07-26 17:27:46.305  4043  4043 D PhoneSwitcherNetworkRequstListener:   done
07-26 17:27:46.305  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-26 17:27:46.305  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-,26 17:27:46.305  3714  4025 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.306  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:46.306  3714  4025 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-26 17:27:46.306  3714  4025 D Ethernet: evalRequest
07-26 17:27:46.306  3714  4025 D Ethernet:   done
07-26 17:27:46.306  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.306  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:46.306  3714  3925 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.306  3714  3959 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-26 17:27:46.306  3714  3925 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 17:27:46.306  3714  3925 D WIFI_P2P: evalRequest
07-26 17:27:46.306  3714  3925 D WIFI_P2P:   done
,07-26 17:27:46.314  3714  4016 D WifiWatchdogStateMachine: Connected - Move to CaptivePortalState
,07-26 17:27:46.320  3714  4016 E WifiWatchdogStateMachine: current state: com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalState@a6ded11
,07-26 17:27:46.325  3714  4016 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-26 17:27:46.326  3244  3244 E audit   : type=1320 audit(1501082866.305:554): 
07-26 17:27:46.329  3714  4016 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,07-26 17:27:46.330  3714  4016 D WifiWatchdogStateMachine: start to check Captive portal
,07-26 17:27:46.341  3244  3244 E audit   : type=1320 audit(1501082866.325:555): 
07-26 17:27:46.341  3298  3774 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-26 17:27:46.343  3714  3929 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
,07-26 17:27:46.345 10178 10178 D [RBL] StoredRequest: @Oncreate
,07-26 17:27:46.346 10178 10178 I [RBL] GuardedSuspension: @getInstance
07-26 17:27:46.346 10178 10178 I [RBL] GuardedSuspension: GuardedSuspension
,07-26 17:27:46.349  3714  3929 D SLocation: system
07-26 17:27:46.349  3714  3929 D SLocation: startGeofence ID = 1
07-26 17:27:46.349 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-26 17:27:46.350 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-26 17:27:46.350 10193 10193 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-26 17:27:46.352 10193 10193 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 android.content.ContextWrapper.sendBroadcast:452 android.content.ContextWrapper.sendBroadcast:452 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3306 
07-26 17:27:46.353  3244  3244 E audit   : type=1320 audit(1501082866.335:556): 
,07-26 17:27:46.356 10178 10178 I [RBL] GuardedSuspension: @getInstance
07-26 17:27:46.356 10178 10178 D [RBL] RblSAccountUtil: @open
07-26 17:27:46.356 10178 10178 D [RBL] RblSAccountUtil:     - client : 1
,07-26 17:27:46.366  3244  3244 E audit   : type=1320 audit(1501082866.345:557): 
,07-26 17:27:46.366 10207 10207 I PhoneErrorReceiver: onReceive
,07-26 17:27:46.367  3298  3774 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-26 17:27:46.372  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.373  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.373  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.373  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [] ]
07-26 17:27:46.374  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.374  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:46.376  4526  4593 D GeolocationController: WIFI : onAvailable
,07-26 17:27:46.376  4526  4593 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [true]
07-26 17:27:46.376 10220 10220 I usagelog: received in receiver
07-26 17:27:46.376 10220 10220 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-26 17:27:46.376 10220 10220 I KnoxUsageLogPro: premStatus:2
,07-26 17:27:46.378 10220 10220 I KnoxUsageLogPro: isEulaShown : false
07-26 17:27:46.378 10220 10220 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-26 17:27:46.379  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.379  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [] ]
07-26 17:27:46.379  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.379  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:46.380  3714  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:46.380  3714  3959 D ConnectivityService: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
07-26 17:27:46.380  3714  3959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-26 17:27:46.381  3714  3796 D EntConnectivity: Not allowed due to - mEnabled false
07-26 17:27:46.381  4526  4612 D PdnController: handleMessage: what 105
07-26 17:27:46.382  4526  4612 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [true]
07-26 17:27:46.383  4526  4612 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [true]
07-26 17:27:46.383  4526  4612 D ResipRegiMgr: handleMessage(): 3
07-26 17:27:46.383  4526  4612 D RegiMgrBase: handleMessage: what 3
07-26 17:27:46.385  3714  3959 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
07-26 17:27:46.385  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.385  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-26 17:27:46.385  3714  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=3, legacyType=-1, [] ]
07-26 17:27:46.385  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
07-26 17:27:46.385  3714  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [] ]
07-26 17:27:46.385  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.386  3714  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.386  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.386  3714  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.386  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.386  3714  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.387  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.387  3714  3959, D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.388 10178 10178 D [RBL] RblSAccountUtil:     - DB is opened
07-26 17:27:46.388 10178 10178 D [RBL] CellDbHelper: @open
07-26 17:27:46.388 10178 10178 D [RBL] CellDbHelper:     - client : 1
07-26 17:27:46.392  3714  3929 E SLocation: id 1 is already started
07-26 17:27:46.392  3714  3929 D WifiStateMachine: startGeofence() - id : 1, ERROR !!, mResult : -5
07-26 17:27:46.392  3714  3929 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-26 17:27:46.393  3714  3796 D EntConnectivity: Not allowed due to - mEnabled false
07-26 17:27:46.393  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.393  3714  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.393  4526  4612 D RegiMgrBase: onNetworkEventChanged: new=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=true, isEpdgConnected=false]
07-26 17:27:46.394  4526  4612 D RegiMgrBase: onNetworkEventChanged: old=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=false, isEpdgConnected=false]
07-26 17:27:46.394  4526  4612 D RegiMgrBase: out of service.
07-26 17:27:46.394  4526  4612 D RegiMgrBase: onNetworkEventChanged: nTask= 0 nRegisteredTask= 0 bExistRetryTimer= false bHaveRegisteringTask= false
07-26 17:27:46.394  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:46.394  3714  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:46.394  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.395  3714  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.395  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:46.395  3714  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:46.396  3714  3714 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-26 17:27:46.396  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:46.396  3714  3714 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = false
07-26 17:27:46.396  3714  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:46.396  3714  3915 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
07-26 17:27:46.396  3714  3915 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
07-26 17:27:46.396  3714  3915 D EnterprisePremiumVpnPolicyServiceV2: run all vpn : runAllVpnService beginning
07-26 17:27:46.397  3714  3714 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
,07-26 17:27:46.397  3714  3714 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
07-26 17:27:46.398  4526  4612 D RegiMgrBase: onNetworkEventChanged: tryRegister
07-26 17:27:46.398  4526  4612 D RegiMgrBase: tryRegister:
07-26 17:27:46.396  3714  3959 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-26 17:27:46.399  3714  3714 D Tethering: Tethering got CONNECTIVITY_ACTION
07-26 17:27:46.400  3714  3961 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
07-26 17:27:46.400  3714  3961 D Tethering: MasterInitialState.processMessage what=327683
07-26 17:27:46.401  3714  3916 I KnoxVpnEngineService: vpn handle : Message received
07-26 17:27:46.401  3714  3916 I KnoxVpnEngineService: vpn handle : Message received
07-26 17:27:46.401  3714  3916 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = false
07-26 17:27:46.401  3714  3916 D KnoxVpnEngineService: run all vpn : runAllVpnService beginning
07-26 17:27:46.403  4526  4612 D RegiMgrBase: RegisterTask(s) -
07-26 17:27:46.403  4526  4612 D ResipRegiMgr: handleMessage(): 32
07-26 17:27:46.403  4526  4612 D RegiMgrBase: handleMessage: what 32
07-26 17:27:46.403  4526  4612 D RegiMgrBase: onPendingUpdateRegistration: 
07-26 17:27:46.409  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:46.410  4068  4284 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
,07-26 17:27:46.419 10178 10178 D [RBL] CellDbHelper:     - DB is opened
07-26 17:27:46.419 10178 10178 D [RBL] PolicyDbHelper: @open
07-26 17:27:46.419 10178 10178 D [RBL] PolicyDbHelper:     - client : 1
07-26 17:27:46.423  5160  5160 I CastMediaRouteProvider: Network connectivity changed
07-26 17:27:46.423  3714  3920 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
,07-26 17:27:46.423  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:46.424  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:46.424  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 17:27:46.424  3714  3920 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
07-26 17:27:46.424  3714  3920 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 17:27:46.433  3714  3920 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
07-26 17:27:46.435  3714  3714 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
07-26 17:27:46.435  3714  3714 V MARsPolicyManager: DataConnection: true
,07-26 17:27:46.437  3714  4483 D SLocation: checkWifiInfo
,07-26 17:27:46.445  3714  4040 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-26 17:27:46.446 10178 10178 D [RBL] PolicyDbHelper:     - DB is opened
07-26 17:27:46.447 10178 10398 D [RBL] StoredRequest: @onHandleIntent
,07-26 17:27:46.447  4904  4904 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-26 17:27:46.449  3714  4040 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-26 17:27:46.452  9405  9405 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
07-26 17:27:46.452  9405  9405 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
07-26 17:27:46.454  9466  9466 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@4576d41 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:46.456  9067  9067 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
07-26 17:27:46.456  9405  9405 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 2
07-26 17:27:46.456  9405  9405 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
07-26 17:27:46.457  9405  9405 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
07-26 17:27:46.459  9466  9466 I NetworkConnectivity: Network state changed: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]
07-26 17:27:46.461  9067  9067 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
07-26 17:27:46.474  9888  9888 D BluetoothAdapter: STATE_ON
07-26 17:27:46.475 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
07-26 17:27:46.476 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-26 17:27:46.477 10193 10193 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
07-26 17:27:46.479  9888  9888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 17:27:46.479  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 17:27:46.479  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 17:27:46.479  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 17:27:46.479  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 17:27:46.479  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-26 17:27:46.479  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-26 17:27:46.479  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 17:27:46.479  9888  9888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 17:27:46.480  3714  3929 D SLocation: system
07-26 17:27:46.480  3714  3929 D SLocation: startLearning ID = 1
07-26 17:27:46.480  3714  3929 D SLocation: setLearningStatus ID = 1 / status = true
07-26 17:27:46.480  3714  3929 D WifiStateMachine: ConnectedState - enter() - startLearning id : 1
07-26 17:27:46.480  3714  3929 D WifiStateMachine: ConnectedState()- id : 1,  startLearning Success !!
07-26 17:27:46.482  3714  3929 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-26 17:27:46.485 10178 10178 D [RBL] CellDbHelper: @close
,07-26 17:27:46.485 10178 10178 D [RBL] CellDbHelper:     - client : 0
07-26 17:27:46.485 10178 10178 D [RBL] CellDbHelper:     - DB is closed
07-26 17:27:46.485 10178 10178 D [RBL] PolicyDbHelper: @close
07-26 17:27:46.485 10178 10178 D [RBL] PolicyDbHelper:     - client : 0
07-26 17:27:46.486 10178 10178 D [RBL] PolicyDbHelper:     - DB is closed
07-26 17:27:46.486 10178 10178 D [RBL] RblSAccountUtil: @close
07-26 17:27:46.486 10178 10178 D [RBL] RblSAccountUtil:     - client : 0
07-26 17:27:46.486 10178 10178 D [RBL] RblSAccountUtil:     - DB is closed
07-26 17:27:46.486 10178 10178 D [RBL] StoredRequest: @onDestroy
07-26 17:27:46.487  9888  9888 D BluetoothAdapter: STATE_ON
07-26 17:27:46.489  3714  3929 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.489  3714  3929 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 17:27:46.489  3714  3929 D WIFI_UT : evalRequest
07-26 17:27:46.489  3714  3929 D WIFI_UT :   done
07-26 17:27:46.489  3714  3929 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:46.489  3714  3929 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 17:27:46.489  3714  3929 D WIFI    : evalRequest
07-26 17:27:46.489  3714  3929 D WIFI    :   done
07-26 17:27:46.493  9888  9888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
07-26 17:27:46.494  9067  9067 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
07-26 17:27:46.500  3714  3763 I ActivityManager: Waited long enough for: ServiceRecord{81a62c9 u0 com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService}
07-26 17:27:46.502  3714  4483 D SLocation: cellLocation is null
07-26 17:27:46.504  3714  3929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 17:27:46.515  9466  9466 I NetworkPolicyMonitor: Download-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
07-26 17:27:46.530  3298  3769 D EnterpriseController: netId is 0
07-26 17:27:46.530  3298  3769 D Netd    : getNetworkForDns: using netid 503 for uid 10001
07-26 17:27:46.530  3298  3769 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-26 17:27:46.559  9466  9466 I NetworkPolicyMonitor: Stream-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
07-26 17:27:46.565 10034 10396 D NetworkSecurityConfig: No Network Security Config specified, using platform default
07-26 17:27:46.575 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:46.576 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:46.590  3714  4939 D MountService: getExternalStorageMountMode : 1
07-26 17:27:46.590  3714  4939 D MountService: getExternalStorageMountMode : 3
07-26 17:27:46.590  3714  4939 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.policydm
07-26 17:27:46.590  3298  3769 D EnterpriseController: netId is 0
07-26 17:27:46.590  3298  3769 D Netd    : getNetworkForDns: using netid 503 for uid 10135
07-26 17:27:46.590  3298  3769 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-26 17:27:46.601  3714  4483 D SLocation: geofence id (1) detected : 0
07-26 17:27:46.601  9466  9466 I DevicePlayback: Got network change: mobile=falsewifi=true
07-26 17:27:46.602  9466  9466 I DevicePlayback: Connectivity restored - clearing all queued disable runnables
,07-26 17:27:46.605  3714 10158 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@1b1194c displayId=0
,07-26 17:27:46.606  3714 10158 D InputTransport: Input channel constructed: fd=459
07-26 17:27:46.606  3714 10158 D InputTransport: Input channel constructed: fd=460
,07-26 17:27:46.607  3714 10158 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
07-26 17:27:46.608  3714 10158 D InputTransport: Input channel destroyed: fd=460
,07-26 17:27:46.615  4068  4284 D InputTransport: Input channel constructed: fd=149
,07-26 17:27:46.617 10404 10404 E Zygote  : v2
07-26 17:27:46.617  4068  4284 D ViewRootImpl@24ff13d[Toast]: setView = android.widget.LinearLayout{9b87d32 V.E...... ......I. 0,0-0,0 #10204d0 android:id/toast_layout_root} touchMode=true
07-26 17:27:46.617 10404 10404 I libpersona: KNOX_SDCARD checking this for 1000
07-26 17:27:46.617 10404 10404 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:46.617 10404 10404 E Zygote  : accessInfo : 0
07-26 17:27:46.621  3714  4939 I ActivityManager: Start proc 10404:com.policydm/1000 for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider
,07-26 17:27:46.624 10404 10404 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:46.625 10404 10404 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.policydm 
07-26 17:27:46.626  3714  4901 V WindowManager: Relayout Window{8cf2eaad0 u0 Toast}: viewVisibility=0 req=755x150 WM.LayoutParams{(0,192)(wrapxwrap) gr=#51 sim=#20 ty=2005 fl=#1040088 fmt=-3 wanim=0x1030004 naviIconColor=0}
,07-26 17:27:46.630  3113  3113 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=4, Uoast
,07-26 17:27:46.631  5160  6762 W MdnsClient_Cast: #acquireLock. Multicast lock not held. Acquiring. Subtypes:"805741C9"
,07-26 17:27:46.634  3714  3929 D WifiHAL : Setting APF program, halHandle = 0x72508911e0
07-26 17:27:46.634  3714  3929 I WifiHAL : 
07-26 17:27:46.634  3714  3929 I WifiHAL : createRequest: APF set program request
,07-26 17:27:46.639  3714  3929 I WifiHAL : Done!
,07-26 17:27:46.651 10404 10404 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:46.651 10404 10404 D ActivityThread: Added TimaKeyStore provider
07-26 17:27:46.653  3714  4021 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: GW is reachable. - 222 msec.
,07-26 17:27:46.659  3714  4901 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3714 ws=WorkSource{10062} pkg=android
,07-26 17:27:46.660  3714  4901 D PowerManagerService: mDisplayReady: false
07-26 17:27:46.660  3714  3799 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-26 17:27:46.660  3714  3799 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-26 17:27:46.661  3714  3799 D DisplayPowerController: Tracking Direct to etc : 102
07-26 17:27:46.661  3714  3799 D DisplayPowerController: getFinalBrightness : Summary is 102 -> 102
,07-26 17:27:46.661  3714  3799 D DisplayPowerController: Animating brightness: target=102, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-26 17:27:46.661  3714  3799 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-26 17:27:46.661  3714  4038 D lights  : lcd : 102 +
07-26 17:27:46.661  3714  3799 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-26 17:27:46.661  3714  3799 D DisplayPowerController: getFinalBrightness : Summary is 102 -> 102
07-26 17:27:46.661  3714  3799 D DisplayPowerController: Animating brightness: target=102, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-26 17:27:46.661  3714  3799 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-26 17:27:46.662  3714  3799 D PowerManagerService: mDisplayReady: true
07-26 17:27:46.663  9466  9517 I DevicePlayback: Allowing woodstock playback due to restored connection
07-26 17:27:46.664  3714  4542 I ActivityManager: DSS on for com.policydm and scale is 1.0
07-26 17:27:46.668  3714  4038 D lights  : lcd : 102 -
07-26 17:27:46.668  3714  4038 D DisplayPowerState: Tracking!!: 102
,07-26 17:27:46.678  4068  4225 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [755x150]-format:1
,07-26 17:27:46.680  4068  4284 D ViewRootImpl@24ff13d[Toast]: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,07-26 17:27:46.701  3714  3929 I WifiScanController: location is disabled
,07-26 17:27:46.701  3714  4542 D WifiScanController: isNLPPackage:com.google.android.gms, true
07-26 17:27:46.708 10404 10404 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,07-26 17:27:46.714  3714  3909 D WindowManager: finishDrawingWindow: Window{8cf2eaad0 u0 Toast} mDrawState=DRAW_PENDING
07-26 17:27:46.716  4068  4207 D vol.MediaSessions: onQueueChanged com.google.android.music []
,07-26 17:27:46.731 10404 10404 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:46.753 10404 10404 I FOTA    : [lllIIIIIIlllIlIIIIII(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
,07-26 17:27:46.753 10404 10404 I FOTA    : [lllIIIIIIlllIlIIIIII(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,07-26 17:27:46.784 10404 10404 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,07-26 17:27:46.798 10404 10417 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
07-26 17:27:46.801 10404 10417 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-26 17:27:46.804 10404 10417 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,07-26 17:27:46.812 10404 10415 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-26 17:27:46.814 10404 10404 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(186/llIIIIlllllIIllIIllI)] try read dbString
07-26 17:27:46.815 10404 10415 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-26 17:27:46.818 10404 10415 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,07-26 17:27:46.824  3714 10158 D MountService: getExternalStorageMountMode : 1
07-26 17:27:46.824  3714 10158 D MountService: getExternalStorageMountMode : 3
07-26 17:27:46.824  3714 10158 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.soagent
,07-26 17:27:46.854  3714 10158 I ActivityManager: Start proc 10425:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
07-26 17:27:46.859 10425 10425 E Zygote  : v2
07-26 17:27:46.859 10425 10425 I libpersona: KNOX_SDCARD checking this for 1000
07-26 17:27:46.859 10425 10425 I libpersona: KNOX_SDCARD not a persona
07-26 17:27:46.860 10425 10425 E Zygote  : accessInfo : 0
07-26 17:27:46.860 10404 10404 I DBG_POLICYDM: [com.policydm.db.XDB(231/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
07-26 17:27:46.864  3714  4021 D WifiWatchdogStateMachine:  [|205]
,07-26 17:27:46.870 10425 10425 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:46.872 10425 10425 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.soagent 
,07-26 17:27:46.895 10425 10425 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:46.895 10425 10425 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:46.899  3714  4543 I ActivityManager: DSS on for com.sec.android.soagent and scale is 1.0
,07-26 17:27:46.919 10425 10425 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,07-26 17:27:46.933 10425 10425 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:46.953 10404 10404 I DBG_POLICYDM: [com.policydm.XDMService(164/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,07-26 17:27:46.963 10404 10404 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(455/IIIIIIlIIIllllllIlII)] xdbGetFUMOStatus : 0
,07-26 17:27:46.964  3714  4543 D MountService: getExternalStorageMountMode : 1
07-26 17:27:46.964  3714  4543 D MountService: getExternalStorageMountMode : 3
,07-26 17:27:46.964  3714  4543 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10134, packageName : com.sec.android.app.sbrowser
07-26 17:27:46.965 10404 10404 I DBG_POLICYDM: [com.policydm.XDMService(588/llIlIllllllllllllllI)] get NotibarState : 0
,07-26 17:27:46.983 10443 10443 E Zygote  : v2
07-26 17:27:46.983 10443 10443 I libpersona: KNOX_SDCARD checking this for 10134
07-26 17:27:46.983 10443 10443 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:46.983 10443 10443 E Zygote  : isSdpEnabledProcess - SDP enabled
07-26 17:27:46.983  3714  4543 I ActivityManager: Start proc 10443:com.sec.android.app.sbrowser:CustomLogger/u0a134 for content provider com.sec.android.app.sbrowser/.logging.CustomLoggingProvider
07-26 17:27:46.984 10443 10443 E Zygote  : accessInfo : 64
07-26 17:27:46.984 10443 10443 E Zygote  : isSdpEnabledProcess - SDP enabled
07-26 17:27:46.984 10443 10443 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10134 / [uid]: 10134
,07-26 17:27:46.990 10443 10443 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:46.991 10443 10443 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser:CustomLogger 
,07-26 17:27:47.013 10443 10443 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:47.013 10443 10443 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:47.015  3714  3918 I ActivityManager: DSS on for com.sec.android.app.sbrowser and scale is 1.0
,07-26 17:27:47.039 10443 10443 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_5.0/lib/arm
,07-26 17:27:47.056 10443 10443 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:47.067 10443 10443 I cr_ApplicationStatus: initialize application : com.sec.android.app.sbrowser.SBrowserApplication@bd7fc7b
,07-26 17:27:47.072 10443 10443 D ReflectField: Cannot load field: SDL_INT
,07-26 17:27:47.072 10443 10443 E ReflectField: Incorrect type : Fallback exception
07-26 17:27:47.072 10443 10443 D ReflectField: Cannot load field: KEYCODE_EMAIL
07-26 17:27:47.072 10443 10443 E ReflectField: Incorrect type : Fallback exception
,07-26 17:27:47.083  3714  3918 D MountService: getExternalStorageMountMode : 1
07-26 17:27:47.084  3714  3918 D MountService: getExternalStorageMountMode : 3
,07-26 17:27:47.084  3714  3918 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.wssyncmldm
,07-26 17:27:47.092  9888  9951 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,07-26 17:27:47.094  9888  9951 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,07-26 17:27:47.095  9888  9951 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,07-26 17:27:47.107 10458 10458 E Zygote  : v2
,07-26 17:27:47.107 10458 10458 I libpersona: KNOX_SDCARD checking this for 1000
07-26 17:27:47.107 10458 10458 I libpersona: KNOX_SDCARD not a persona
,07-26 17:27:47.108 10458 10458 E Zygote  : accessInfo : 0
07-26 17:27:47.110  3714  3918 I ActivityManager: Start proc 10458:com.wssyncmldm/1000 for content provider com.wssyncmldm/com.samsung.android.app.fotaclient.log.MasterLogProvider
,07-26 17:27:47.118  3714  4020 D WifiWatchdogStateMachine.QualitySocketHandler: response code: 204
07-26 17:27:47.119 10458 10458 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-26 17:27:47.120  3714  4020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiWatchdogStateMachine$QualitySocketHandler.handleMessage:4711 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:154 android.os.HandlerThread.run:61 
,07-26 17:27:47.121 10458 10458 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.wssyncmldm 
,07-26 17:27:47.123  3714  4016 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
,07-26 17:27:47.124  3714 10386 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-26 17:27:47.124  3714 10386 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: MaybeNotifyState{ when=-1ms what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-26 17:27:47.124  3714 10386 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-1ms what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-26 17:27:47.124  3714 10386 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: CMD_ACCEPT_UNVALIDATED_WIFI
07-26 17:27:47.124  3714  3959 D ConnectivityService: NetworkMonitor.CMD_ACCEPT_UNVALIDATED_WIFI network
07-26 17:27:47.125  3714  3959 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-26 17:27:47.125  3714  3959 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-26 17:27:47.125  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.125  3714  3714 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
07-26 17:27:47.125  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.125  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.125  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-26 17:27:47.125  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 17:27:47.125  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:47.126  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 17:27:47.126  3714  3959 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-26 17:27:47.126  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-26 17:27:47.126  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.126  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:47.126  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.126  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:47.126  3714 10386 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=151655 target=com.android.internal.util.StateMachine$SmHandler }
07-26 17:27:47.126  3714  3959 D ConnectivityService: sending new Min Network Score(100): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.126  3714 10386 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: RESULT_VALID
07-26 17:27:47.126  3714 10386 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
07-26 17:27:47.127  3714  3959 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-26 17:27:47.127  3714  3959 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-26 17:27:47.127  3714  3959 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation passed
07-26 17:27:47.128  3714  3959 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-26 17:27:47.128  3714  3959 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-26 17:27:47.128  3714  3959 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-26 17:27:47.128  3714  4025 D Ethernet: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.128  3714  4025 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-26 17:27:47.128  3714  4025 D Ethernet: evalRequest
07-26 17:27:47.128  3714  4025 D Ethernet:   done
07-26 17:27:47.129  4043  4043 D PhoneSwitcherNetworkRequstListener: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.129  3714  3925 D WIFI_P2P: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.129  3714  3925 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 17:27:47.129  4043  4043 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-26 17:27:47.129 , 3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.129  3714  3925 D WIFI_P2P: evalRequest
07-26 17:27:47.129  4043  4043 D PhoneSwitcherNetworkRequstListener: evalRequest
07-26 17:27:47.129  4043  4043 D PhoneSwitcherNetworkRequstListener:   done
07-26 17:27:47.129  3714  3925 D WIFI_P2P:   done
07-26 17:27:47.129  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.129  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.129 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:47.129  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-26 17:27:47.129  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.129  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:47.130  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.130  3714  3959 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-26 17:27:47.130  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-26 17:27:47.130 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:47.130  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.130  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:47.130  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.130  3714  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:47.130  3714  3959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-26 17:27:47.130  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.130  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-26 17:27:47.131  3714  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [] ]
07-26 17:27:47.131  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
07-26 17:27:47.132  3714  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [] ]
07-26 17:27:47.133  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.133  3714  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.134  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacy,Type=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.134  3714  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.134  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.135  3714  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.136  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.137  3714  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.137  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.138  3714  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.138  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:47.138  3714  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:47.139  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.139  3714  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.140  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:47.140  3714  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:47.141  3714  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:47.141  3714  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 17:27:47.141  3714  3959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-26 17:27:47.148  3714  3929 D WIFI_UT : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.149  3714  3929 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 17:27:47.149  3714  3929 D WIFI_UT : evalRequest
07-26 17:27:47.149  3714  3929 D WIFI_UT :   done
07-26 17:27:47.149  3714  3929 D WIFI    : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 17:27:47.149  3714  3929 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 17:27:47.149  3714  3929 D WIFI    : evalRequest
07-26 17:27:47.149  3714  3929 D WIFI    :   releaseNetworkFor
07-26 17:27:47.151  4068  4284 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-26 17:27:47.152 10458 10458 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 17:27:47.152 10458 10458 D ActivityThread: Added TimaKeyStore provider
07-26 17:27:47.153  3714  3929 D WifiConfigManager: update usableInternet : true
07-26 17:27:47.154  3714 10471 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
07-26 17:27:47.154  3714 10471 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-26 17:27:47.154  3714 10471 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-26 17:27:47.154  3714 10471 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-26 17:27:47.155  3714 10471 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-26 17:27:47.155  3714  4542 I ActivityManager: DSS on for com.wssyncmldm and scale is 1.0
07-26 17:27:47.155  3714 10471 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-26 17:27:47.155  3714 10471 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-26 17:27:47.155  3714 10471 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-26 17:27:47.155  3714 10471 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-26 17:27:47.155  3714 10471 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-26 17:27:47.156  3714 10471 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-26 17:27:47.156  3714 10471 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
07-26 17:27:47.160  4068  4284 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
07-26 17:27:47.176 10458 10458 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm64
07-26 17:27:47.179  3714  3929 D WifiConfigStore: saveNetwork skipInternetCheck
07-26 17:27:47.194 10458 10458 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-26 17:27:47.197  3714  3929 D WifiConfigStore: readNetwork skipInternetCheck
07-26 17:27:47.201 10458 10458 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(96/onCreate)] 
,07-26 17:27:47.210  3714 10472 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
07-26 17:27:47.210  3714 10472 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-26 17:27:47.210  3714 10472 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-26 17:27:47.211  3714 10472 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-26 17:27:47.211  3714 10472 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-26 17:27:47.212  3714 10472 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-26 17:27:47.212  3714 10472 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-26 17:27:47.212  3714 10472 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-26 17:27:47.213  3714 10472 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-26 17:27:47.213  3714 10472 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-26 17:27:47.213  3714 10472 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-26 17:27:47.213  3714 10472 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
07-26 17:27:47.217  3714  3714 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-26 17:27:47.217  3714  3714 D WifiHs20Service: reason: 2
07-26 17:27:47.218  3714  3955 I WifiHs20Service: Message received 5014
07-26 17:27:47.218  3714  3955 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,07-26 17:27:47.262 10458 10458 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(422/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-26 17:27:47.285  3714  3738 I ActivityManager: KPU : put [com.samsung.android.themecenter] : 26668 K
07-26 17:27:47.285  3714  3738 I ActivityManager: Killing 9392:com.samsung.android.themecenter/1000 (adj 906): DHA:empty #33
07-26 17:27:47.286  3714  3738 I ActivityManager: KPU : put [com.samsung.android.sm.devicesecurity] : 27532 K
07-26 17:27:47.286  3714  3738 I ActivityManager: Killing 7095:com.samsung.android.sm.devicesecurity/5012 (adj 906): DHA:empty #33
07-26 17:27:47.287  3714  3738 I ActivityManager: KPU : put [com.samsung.android.scloud] : 28536 K
07-26 17:27:47.287  3714  3738 I ActivityManager: Killing 9370:com.samsung.android.scloud/5009 (adj 906): DHA:empty #33
,07-26 17:27:47.336  5160  5160 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-26 17:27:47.338  3298  3769 D EnterpriseController: netId is 0
07-26 17:27:47.338  3298  3769 D Netd    : getNetworkForDns: using netid 503 for uid 10019
07-26 17:27:47.338  3298  3769 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-26 17:27:47.340  5160  8145 I iu.UploadsManager: num queued entries: 0
07-26 17:27:47.341  5160  8145 I iu.UploadsManager: num updated entries: 0
07-26 17:27:47.343  5160  8145 I iu.SyncManager: NEXT; no task
,07-26 17:27:47.373  3714  3959 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,07-26 17:27:47.376 10246 10246 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
07-26 17:27:47.377 10246 10246 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? ]
07-26 17:27:47.377 10246 10246 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-26 17:27:47.397 10246 10246 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-26 17:27:47.397 10246 10246 I SA      : [OR] == isSIMCardReady false ==
07-26 17:27:47.398 10246 10246 I SA      : [SCU] == networkStateCheck == true
07-26 17:27:47.399 10246 10246 I SA      : [DM] getCountryCodeFromCSC : PL
07-26 17:27:47.399 10246 10246 I SA      : isChinaCountryCode : false
07-26 17:27:47.399 10246 10246 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-26 17:27:47.399 10246 10246 I SA      : [OR] == networkStateCheck true ==
07-26 17:27:47.419  3714  3918 D ActivityManager: cleanUpApplicationRecord -- 9392
07-26 17:27:47.420  4844  4855 D ForegroundUtils: could not check pending caller
,07-26 17:27:47.430  3714  3878 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-26 17:27:47.430  3714  3878 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-26 17:27:47.434  3714  4018 D WifiWatchdogStateMachine:  [|204] []
,07-26 17:27:47.438 10246 10246 I SA      : [OR] GetMyCountryZoneTask
,07-26 17:27:47.439 10246 10246 I SA      : [OR] onReceive END
07-26 17:27:47.440  3714  3739 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170726T175747 - CU:10124/CP:5177
07-26 17:27:47.441  3714  4487 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / op:PendingIntent{ff1334: PendingIntentRecord{2ad355d android broadcastIntent}}
07-26 17:27:47.442  3714  3923 D ActivityManager: cleanUpApplicationRecord -- 7095
07-26 17:27:47.446  4844  4856 D ForegroundUtils: could not check pending caller
07-26 17:27:47.449  3714  3909 D ActivityManager: cleanUpApplicationRecord -- 9370
,07-26 17:27:47.452 10458 10458 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(297/lllIlIlIIIllIIlIllIl)] Voice : true
,07-26 17:27:47.455 10458 10458 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(298/lllIlIlIIIllIIlIllIl)] SMS : true
,07-26 17:27:47.457  4844  4855 D ForegroundUtils: could not check pending caller
07-26 17:27:47.458 10458 10458 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(299/lllIlIlIIIllIIlIllIl)] isDataOnly : false
07-26 17:27:47.458  3714  4487 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20170727T172747 - CU:1000/CP:3714
,07-26 17:27:47.481 10269 10269 I SVCAgent: Ignore network change.
,07-26 17:27:47.488  3714  4446 E Watchdog: !@Sync 10 [26_lip_17_27_47.488]
,07-26 17:27:47.495 10458 10458 I FOTA_AGENT: [IIIlIlIIIllIIIIllIlI(645/IllIlIIIIlIIlIIIllIl)] bootTime: 1501082573721
,07-26 17:27:47.500 10282 10282 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,07-26 17:27:47.506 10246 10479 I SA      : [SRS] prepareGetMyCountryZone
,07-26 17:27:47.517  7950  7950 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
07-26 17:27:47.517  7950  7950 E SPPClientService: [SystemStateMoniter] Current Time : 315801
07-26 17:27:47.518  7950  7950 E SPPClientService: [SystemStateMoniter] No Connect : false
,07-26 17:27:47.526  3714  3714 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
,07-26 17:27:47.527  3714  3714 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
07-26 17:27:47.529  3714  3714 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,07-26 17:27:47.532  3714  4546 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{57eac6f: PendingIntentRecord{7835d27 com.google.android.gms broadcastIntent}}
,07-26 17:27:47.532 10246 10479 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-26 17:27:47.534 10246 10479 I SA      : [SSP] query invoked
07-26 17:27:47.534  3714  3714 D SLocation: PendingIntent onSendFinished id:1
07-26 17:27:47.536 10458 10458 I FOTA_AGENT: [IIIlIlIIIllIIIIllIlI(638/lllIlIlIIIllIIlIllIl)] bootTime: 1501082573721, savedBootTime: 1500000484534
,07-26 17:27:47.544 10246 10479 I SA      : [TPMU] GetMccFromDB : null
,07-26 17:27:47.544 10246 10479 I SA      : [SCU] getMccFromPreferece mcc = 260
07-26 17:27:47.544 10246 10479 I SA      : [LBE] isSupportCheckDomainRegion : true
07-26 17:27:47.545 10246 10479 I SA      : [TPM] isNoProxy(default) : true
,07-26 17:27:47.548 10246 10479 D NetworkSecurityConfig: No Network Security Config specified, using platform default
07-26 17:27:47.549 10458 10458 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3131/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,07-26 17:27:47.561 10458 10458 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3184/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,07-26 17:27:47.581 10458 10458 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3237/IllIlIIIIlIIlIIIllIl)] xdmdbsqlGetNotiSaveState : 0
,07-26 17:27:47.602 10458 10458 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3386/llllllIllIlIlllIIlIl)] xdmdbsqlGetFumoInitType : 0
,07-26 17:27:47.607 10458 10458 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(93/onCreate)] DMApplication NOT Start !
,07-26 17:27:47.622  4779  6616 E NetworkScheduler: Unable to resolve correct action against com.google.android.gms/.auth.be.cron.AuthCronService for user #0 to instantiate callback. Not executing task.
,07-26 17:27:47.642  3714  3946 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20170726T173657 - CU:10019/CP:4779
,07-26 17:27:47.651  3714  3763 D MountService: getExternalStorageMountMode : 1
07-26 17:27:47.651  3714  3763 D MountService: getExternalStorageMountMode : 3
,07-26 17:27:47.651  3714  3763 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10112, packageName : com.google.android.talk
,07-26 17:27:47.670 10487 10487 E Zygote  : v2
,07-26 17:27:47.670 10487 10487 I libpersona: KNOX_SDCARD checking this for 10112
07-26 17:27:47.670 10487 10487 I libpersona: KNOX_SDCARD not a persona
07-26 17:27:47.671 10487 10487 E Zygote  : accessInfo : 0
,07-26 17:27:47.679  3714  3763 I ActivityManager: Start proc 10487:com.google.android.talk/u0a112 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.broadcastreceiver.GcmStateReceiver
,07-26 17:27:47.681 10487 10487 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-26 17:27:47.684 10487 10487 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,07-26 17:27:47.697 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:47.697 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:47.703  3244  3244 E audit   : type=1320 audit(1501082867.685:558): 
,07-26 17:27:47.718  3244  3244 E audit   : type=1320 audit(1501082867.705:559): 
,07-26 17:27:47.723 10487 10487 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 17:27:47.724 10487 10487 D ActivityThread: Added TimaKeyStore provider
,07-26 17:27:47.729  3714  3946 I ActivityManager: DSS on for com.google.android.talk and scale is 1.0
,07-26 17:27:47.735  3244  3244 E audit   : type=1320 audit(1501082867.715:560): 
,07-26 17:27:47.748  3244  3244 E audit   : type=1320 audit(1501082867.735:561): 
07-26 17:27:47.758  3714  4938 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{427e568: PendingIntentRecord{6bcff04 com.google.android.gms broadcastIntent}}
,07-26 17:27:47.766  3714  3946 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20170726T173657 - CU:10019/CP:4779
,07-26 17:27:47.768 10487 10487 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-26 17:27:47.771 10487 10487 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,07-26 17:27:47.781  4779  6616 E NetworkScheduler: Unable to resolve correct action against com.google.android.gms/.playlog.store.VacuumService for user #0 to instantiate callback. Not executing task.
,07-26 17:27:47.792 10487 10487 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-26 17:27:47.805  4779  6616 E NetworkScheduler: Unable to resolve correct action against com.google.android.gms/.playlog.uploader.UploaderService for user #0 to instantiate callback. Not executing task.
,07-26 17:27:47.827  4779  6616 E NetworkScheduler: Unable to resolve correct action against com.google.android.gms/.tapandpay.tapreporting.TapInfoUploadService for user #0 to instantiate callback. Not executing task.
,07-26 17:27:47.860  4779  6616 E NetworkScheduler: Unable to resolve correct action against com.google.android.gms/.tapandpay.tapreporting.TapInfoUploadService for user #0 to instantiate callback. Not executing task.
,07-26 17:27:47.945  3714  4939 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170726T182332 - CU:10019/CP:4779
,07-26 17:27:47.998  3714  4936 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{849f014: PendingIntentRecord{7835d27 com.google.android.gms broadcastIntent}}
,07-26 17:27:48.017  3714  4543 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170726T182332 - CU:10019/CP:4779
,07-26 17:27:48.028  4779 10486 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-26 17:27:48.039  4779 10486 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-26 17:27:48.057  3714  4859 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-26 17:27:48.058 10487 10487 D BabelGcmRegistration: GcmRegistration: Checking GCM registration
,07-26 17:27:48.068 10487 10487 I Babel_telephony: TeleModule.onApplicationCreate
,07-26 17:27:48.071 10487 10514 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-26 17:27:48.071 10487 10514 I Babel_SMS: MmsConfig.loadMmsSettings
07-26 17:27:48.072 10487 10514 E TelephonyManager: getCustomerPath : /system/csc/customer.xml file exist
,07-26 17:27:48.072 10487 10514 E TelephonyManager: getCustomerPath : /system/csc/customer.xml file exist
,07-26 17:27:48.073 10487 10514 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: userAgent=SAMSUNG-ANDROID-MMS/uaprof, uaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
07-26 17:27:48.073 10487 10514 I Babel_SMS: MmsConfig.loadFromDatabase
,07-26 17:27:48.076 10487 10487 I Babel_App: Startup - clean
,07-26 17:27:48.083  3714  4900 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10112
,07-26 17:27:48.084  3714  4936 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10112
07-26 17:27:48.084 10487 10514 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-26 17:27:48.084 10487 10514 I Babel_SMS: MmsConfig.loadFromResources
07-26 17:27:48.084  3714  4936 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10112
07-26 17:27:48.085 10487 10514 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-26 17:27:48.085 10487 10514 I Babel_SMS: MmsConfig.loadMmsSettings: userAgent=SAMSUNG-ANDROID-MMS/uaprof, uaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
07-26 17:27:48.086  3714  4936 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10112
07-26 17:27:48.087  3714 10158 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10112
,07-26 17:27:48.100  9888  9951 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
07-26 17:27:48.101  9888  9951 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
07-26 17:27:48.102  9888  9951 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
07-26 17:27:48.102  9888  9951 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 240)
07-26 17:27:48.104  9888  9951 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
07-26 17:27:48.104  9888  9951 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
07-26 17:27:48.104  9888  9951 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 241)
07-26 17:27:48.105  9888  9951 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,07-26 17:27:48.107  9888  9951 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,07-26 17:27:48.108  4779 10486 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:48.109  4779 10486 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:48.109  3298  3769 D EnterpriseController: netId is 0
07-26 17:27:48.109  3298  3769 D Netd    : getNetworkForDns: using netid 503 for uid 10019
07-26 17:27:48.109  3298  3769 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-26 17:27:48.110  9888  9951 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,07-26 17:27:48.112  9888  9951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 17:27:48.112  9888  9951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30d535f added. We now have 2 listener(s)
07-26 17:27:48.112  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30d535f added. We now have 3 listener(s)
,07-26 17:27:48.112  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 17:27:48.115  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-26 17:27:48.116  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 17:27:48.116  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:48.116  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 17:27:48.116  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68da1ac added. We now have 4 listener(s)
07-26 17:27:48.116  9888  9951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 17:27:48.117  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 17:27:48.122  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:48.126  9888  9951 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,07-26 17:27:48.128  9888  9951 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,07-26 17:27:48.128  9888  9951 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
07-26 17:27:48.128  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,07-26 17:27:48.132  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-26 17:27:48.136  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
,07-26 17:27:48.136  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:48.136  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.137  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-26 17:27:48.140  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:48.140  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:48.141  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.141  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-26 17:27:48.141  9888  9951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-26 17:27:48.141  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-26 17:27:48.141  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 17:27:48.144  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-26 17:27:48.144  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-26 17:27:48.144  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-26 17:27:48.144  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,07-26 17:27:48.144  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-26 17:27:48.144  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-26 17:27:48.144  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 17:27:48.144  9888 10521 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-26 17:27:48.145  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 17:27:48.145  9888  9888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-26 17:27:48.147  9888 10521 D BluetoothSocket: bindListen(): myUserId = 0
07-26 17:27:48.147  9888 10521 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 17:27:48.151  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-26 17:27:48.151  9888  9951 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 17:27:48.151  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 17:27:48.153  9888 10521 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-26 17:27:48.153  9888 10521 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@e0cde0a, port: 6, type: 1, local socket address: null, socket type: 0
,07-26 17:27:48.155  3714  3946 D CryptdConnector: SND -> {21 cryptfs getpwtype}
,07-26 17:27:48.156  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:48.156  3098  3146 D VoldCryptCmdListener: cryptfs getpwtype
07-26 17:27:48.157  3714  3891 D CryptdConnector: RCV <- {213 21 default}
07-26 17:27:48.159  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:48.160  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:48.162  9888  9951 D BluetoothAdapter: isSecureModeEnabled
07-26 17:27:48.163 10011 10033 D BtConfig.SecureMode: isSecureModeOn:false
07-26 17:27:48.163  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.164  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 17:27:48.165  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:48.166  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:48.166  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 17:27:48.166  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 17:27:48.166  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,07-26 17:27:48.170  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:48.173  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.173  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.173  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,07-26 17:27:48.173  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-26 17:27:48.173  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "35d3e8aa-16e9-4ee5-85be-d6766e758699", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-26 17:27:48.173  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E 94 4A 3E
07-26 17:27:48.173  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:48.174  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:48.174  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.174  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.174  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-26 17:27:48.174  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:48.174  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.174  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.175  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.176  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:48.178  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:48.178  9888  9951 D BluetoothAdapter: isSecureModeEnabled
07-26 17:27:48.178 10011 10032 D BtConfig.SecureMode: isSecureModeOn:false
07-26 17:27:48.179  9888  9951 D BluetoothLeAdvertiser: start advertising
07-26 17:27:48.180  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:48.186 10011 10022 D BtGatt.GattService: registerClient() - UUID=eba75165-e7d3-406b-b672-15af916c3f81
,07-26 17:27:48.198 10246 10479 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
07-26 17:27:48.199 10246 10479 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-26 17:27:48.201 10246 10479 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,07-26 17:27:48.205 10246 10479 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:48.205 10246 10479 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:48.208  3298  3769 D EnterpriseController: netId is 0
07-26 17:27:48.208  3298  3769 D Netd    : getNetworkForDns: using netid 503 for uid 10041
,07-26 17:27:48.208  3298  3769 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-26 17:27:48.222 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:48.222 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:48.290 10011 10031 D BtGatt.GattService: onClientRegistered() - UUID=eba75165-e7d3-406b-b672-15af916c3f81, clientIf=5, status=0
,07-26 17:27:48.291  9888  9900 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-26 17:27:48.294 10011 10032 E BtGatt.ContextMap: Context not found for ID 5
,07-26 17:27:48.295 10011 10059 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-26 17:27:48.295 10011 10048 D BtGatt.AdvertiseManager: message : 0
,07-26 17:27:48.299 10011 10048 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-26 17:27:48.299 10011 10048 D BtGatt.AdvertiseManager: size of list is =0
,07-26 17:27:48.303 10011 10048 D BtGatt.AdvertiseManager: starting advertising
,07-26 17:27:48.305 10011 10048 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-26 17:27:48.306 10011 10065 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-26 17:27:48.319 10011 10031 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-26 17:27:48.321 10011 10048 D BtGatt.AdvertiseManager: starting multi advertising
,07-26 17:27:48.325 10011 10031 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-26 17:27:48.325 10011 10048 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-26 17:27:48.325 10011 10048 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-26 17:27:48.326 10011 10048 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-26 17:27:48.326 10011 10048 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-26 17:27:48.326  9888  9899 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-26 17:27:48.328  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.328  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.328  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-26 17:27:48.329  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.329  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.330  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.330  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.331  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.331  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-26 17:27:48.332  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-26 17:27:48.333  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.335  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.335  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.336  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.337  9888  9888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-26 17:27:48.338  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.338  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:48.338  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-26 17:27:48.339  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.339  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.340  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:48.340  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.340  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-26 17:27:48.340  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-26 17:27:48.341  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.341  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.341  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.342  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.342  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-26 17:27:48.346  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,07-26 17:27:48.346  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
07-26 17:27:48.347  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.347  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.348  9888  9888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-26 17:27:48.373  3714  3918 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.384  3714 10158 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.395  3714  4859 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.408  3714  3739 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.419  3714  4939 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.429  3714  4543 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.440  3714  3909 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.450  3714  4937 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.461  3714  4858 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.473  3714  3923 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.484  3714  3918 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.498  3714 10158 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.510  3714  4859 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.526  3714  3739 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.546  4068  4284 D ViewRootImpl@24ff13d[Toast]: dispatchDetachedFromWindow
,07-26 17:27:48.553  3714  4858 D InputTransport: Input channel destroyed: fd=459
07-26 17:27:48.554  3714  4858 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3714) eventTime = 316838
07-26 17:27:48.554  3714  4858 D PowerManagerService: [s] UserActivityState : 4 -> 1
07-26 17:27:48.555  3714  4858 D PowerManagerService: [api] release WakeLock SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3714, ws=WorkSource{10062}) (uid=1000, pid=3714, ws=WorkSource{10062}, pkg=android, elapsedTime=1895) (0x0)
07-26 17:27:48.555  3714  4858 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3714, ws=WorkSource{10062}) (uid=1000, pid=3714, ws=WorkSource{10062}, pkg=android, elapsedTime=1895)
,07-26 17:27:48.558  4068  4284 D InputTransport: Input channel destroyed: fd=149
,07-26 17:27:48.562  4779 10486 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:48.563  4779 10486 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:48.701  4779 10486 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-26 17:27:48.706  3714  4857 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-26 17:27:48.723  4779 10486 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:48.723  4779 10486 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:48.762 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:48.763 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:48.839  9888  9951 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,07-26 17:27:48.840  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
07-26 17:27:48.840  9888  9951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-26 17:27:48.840  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-26 17:27:48.841  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-26 17:27:48.841  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-26 17:27:48.842  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 17:27:48.842  9888 10521 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-26 17:27:48.842  9888 10521 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-26 17:27:48.842  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-26 17:27:48.842  9888 10521 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-26 17:27:48.842  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,07-26 17:27:48.843  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,07-26 17:27:48.843  9888  9888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-26 17:27:48.843  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 17:27:48.843  9888  9888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-26 17:27:48.843  9888  9888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-26 17:27:48.844  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.844  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-26 17:27:48.845  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-26 17:27:48.846  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.847  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.848  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.850  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.856  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:48.860  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:48.861  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-26 17:27:48.863  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:48.865  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:48.865  9888  9951 D BluetoothLeScanner: could not find callback wrapper
07-26 17:27:48.865  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-26 17:27:48.866  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.867  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.867  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.868  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-26 17:27:48.868  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.873  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:48.875  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:48.875  9888  9951 D BluetoothLeAdvertiser: stop advertising
,07-26 17:27:48.877 10011 10022 E BtGatt.ContextMap: Context not found for ID 5
,07-26 17:27:48.878 10011 10048 D BtGatt.AdvertiseManager: message : 1
07-26 17:27:48.878 10011 10059 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-26 17:27:48.879 10011 10048 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-26 17:27:48.880 10011 10048 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-26 17:27:48.883 10011 10048 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-26 17:27:48.891  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-26 17:27:48.892  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
07-26 17:27:48.892  3714  3929 D WifiStateMachine: User moved, open or psk 24GHz, currentRssi = -40, mQnsUpperRssiThreshold = 200
,07-26 17:27:48.892 10011 10031 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,07-26 17:27:48.893 10011 10031 D BtGatt.GattService: Client app is not null!
07-26 17:27:48.894  3714  3929 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@298c388
07-26 17:27:48.894  9888  9900 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
07-26 17:27:48.895  3714  3929 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
07-26 17:27:48.896 10011 10032 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-26 17:27:48.898  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-26 17:27:48.899  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.899  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-26 17:27:48.899  3714  3929 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170726T172751 - CU:1000/CP:3714
07-26 17:27:48.899  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.899  3714  3929 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172751, SetElapsed=319882, nowELAPSED=317184
07-26 17:27:48.900  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.900  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.901  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 17:27:48.901  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 17:27:48.902  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 17:27:48.904  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.907  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.907  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-26 17:27:48.907  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:48.908  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:48.908  9888  9888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 17:27:48.909  9888  9888 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
07-26 17:27:48.909  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 17:27:48.909  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-26 17:27:48.909  9888  9888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,07-26 17:27:48.910  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,07-26 17:27:48.911  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.911  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-26 17:27:48.911  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-26 17:27:48.911  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.912  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,07-26 17:27:48.912  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-26 17:27:48.912  9888  9888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-26 17:27:48.919 10246 10479 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 718
,07-26 17:27:48.964  4779 10486 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-26 17:27:48.985 10246 10479 I SA      : [ODM] saveOpenData( GEO_IP, EU )
07-26 17:27:48.986 10246 10479 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,07-26 17:27:48.995 10246 10479 I SA      : [OCP]  Cursor is not null
,07-26 17:27:49.012 10246 10479 I SA      : [OCP] update openData : EU
,07-26 17:27:49.015 10246 10479 I SA      : [TPMU] getNetworkMcc : 
07-26 17:27:49.017  3714  3946 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170726T182332 - CU:10019/CP:4779
07-26 17:27:49.019 10246 10479 I SA      : [SRS] prepareGetMyCountryZone
,07-26 17:27:49.028 10246 10479 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-26 17:27:49.028 10246 10479 I SA      : [SSP] query invoked
,07-26 17:27:49.030  3714  4938 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{1a4c2b0: PendingIntentRecord{7835d27 com.google.android.gms broadcastIntent}}
,07-26 17:27:49.033 10246 10479 I SA      : [TPMU] GetMccFromDB : null
07-26 17:27:49.033 10246 10479 I SA      : [SCU] getMccFromPreferece mcc = 260
07-26 17:27:49.033 10246 10479 I SA      : [LBE] isSupportCheckDomainRegion : true
,07-26 17:27:49.033 10246 10479 I SA      : [TPM] isNoProxy(default) : true
,07-26 17:27:49.036 10246 10479 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
07-26 17:27:49.036 10246 10479 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-26 17:27:49.040 10246 10479 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,07-26 17:27:49.040 10246 10479 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:49.041 10246 10479 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:49.050  3714  3739 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170726T182332 - CU:10019/CP:4779
,07-26 17:27:49.091  3714  3797 I WindowManager: Destroying surface Surface(name=Toast) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementInner:499 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementLoop:274 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacement:222 com.android.server.wm.WindowManagerService$H.handleMessage:9166 android.os.Handler.dispatchMessage:102 
,07-26 17:27:49.092  3113  3896 I SurfaceFlinger: id=17 Removed Uoast (5/5)
07-26 17:27:49.092  3113  4622 I SurfaceFlinger: id=17 Removed Uoast (-2/5)
,07-26 17:27:49.157  4649  4649 D io_stats: !@   8,0 r 26220 2302548 w 5547 211212 d 730 74180 f 2230 2230 iot 12250 11250 th 469412 0 0 pt 0 inp 0 0 317.440
,07-26 17:27:49.275 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:49.276 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:49.414  9888  9888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-26 17:27:49.679 10246 10479 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 639
,07-26 17:27:49.683 10246 10479 I SA      : [ODM] saveOpenData( GEO_IP, EU )
07-26 17:27:49.684 10246 10479 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,07-26 17:27:49.690 10246 10479 I SA      : [OCP]  Cursor is not null
,07-26 17:27:49.699 10246 10479 I SA      : [OCP] update openData : EU
,07-26 17:27:49.708 10246 10479 I SA      : [TPMU] getNetworkMcc : 
,07-26 17:27:49.712 10246 10479 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 675
,07-26 17:27:49.712 10246 10479 I SA_HTTPURLCONNECTION: [RC New] Execute end
07-26 17:27:49.713 10246 10479 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 1513
07-26 17:27:49.713 10246 10479 I SA_HTTPURLCONNECTION: [RC New] Execute end
07-26 17:27:49.714 10246 10246 I SA      : [OR] GetMyCountryZoneTask mcc = null
07-26 17:27:49.714 10246 10246 I SA      : [OR] GetMyCountryZoneTask Fail
,07-26 17:27:49.778 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:49.779 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:50.145  3714  4543 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170726T183338 - CU:10007/CP:4860
,07-26 17:27:50.428 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:50.429 10034 10396 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:50.849  5015  5059 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-26 17:27:50.849  5015  5059 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-26 17:27:50.849  5015  5059 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({system=1, android.process.acore=1})  ]
,07-26 17:27:50.861  5015  5059 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 11ms lastUpdatedAfter : 15209 ms mFlush_time_threasold : 2000 mCurrentSize : 267
,07-26 17:27:51.042  3714  4938 I ActivityManager: KPU : put [com.samsung.svoice.sync] : 21052 K
07-26 17:27:51.042  3714  4938 I ActivityManager: Killing 9424:com.samsung.svoice.sync/u0a40 (adj 906): DHA:empty #33
,07-26 17:27:51.087  3714  4937 D ActivityManager: cleanUpApplicationRecord -- 9424
,07-26 17:27:51.088  4844  4855 D ForegroundUtils: could not check pending caller
,07-26 17:27:51.598  3714  3864 D SamsungAlarmManager: Expired : 4
,07-26 17:27:51.599  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172800, SetElapsed=328797, nowELAPSED=319883
07-26 17:27:51.599  3714  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@26005f3 alarm=Alarm{edd0ae type 2 when 319882 android}
,07-26 17:27:51.603  3714  3929 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
,07-26 17:27:51.609  3714  3929 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170726T172759 - CU:1000/CP:3714
07-26 17:27:51.610  3714  3929 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172759, SetElapsed=327889, nowELAPSED=319895
,07-26 17:27:51.920  9888  9951 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,07-26 17:27:51.921  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 17:27:51.922  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 17:27:51.922  9888  9951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-26 17:27:51.922  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 17:27:51.922  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 17:27:51.922  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 17:27:51.924  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:51.924  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:27:51.935  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-26 17:27:51.935  9888  9951 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 17:27:51.936  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-26 17:27:51.940  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:51.942  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:51.944  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:51.949  9888  9951 D BluetoothAdapter: isSecureModeEnabled
,07-26 17:27:51.949 10011 10023 D BtConfig.SecureMode: isSecureModeOn:false
07-26 17:27:51.950  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:51.950  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 17:27:51.952  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:51.953  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:51.953  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 17:27:51.954  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 17:27:51.954  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,07-26 17:27:51.957  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:51.958  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:51.962  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:51.963  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:51.965  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:51.966  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-26 17:27:51.966  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-26 17:27:51.966  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 64731
07-26 17:27:51.967  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=64731, mManufacturerData=null, mManufacturerDataMask=null]
07-26 17:27:51.967  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:51.968  9888  9951 D BluetoothLeScanner: Start Scan
,07-26 17:27:51.969  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:51.970  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:51.972  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:51.974  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:51.976 10011 10022 D BtGatt.GattService: registerClient() - UUID=3e5ea8ad-04a3-4e95-9f9e-1299fb2e200c
,07-26 17:27:52.079 10011 10031 D BtGatt.GattService: onClientRegistered() - UUID=3e5ea8ad-04a3-4e95-9f9e-1299fb2e200c, clientIf=5, status=0
,07-26 17:27:52.079  9888  9899 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
,07-26 17:27:52.080 10011 10032 D BtGatt.GattService: start scan with filters
07-26 17:27:52.082 10011 10032 D BtGatt.GattService: getScanSettings
,07-26 17:27:52.083 10011 10032 D BtGatt.GattService: Is it foreground application = true
07-26 17:27:52.083 10011 10032 D BtGatt.GattService: not a background application
,07-26 17:27:52.090 10011 10059 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
07-26 17:27:52.090 10011 10059 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:52.090  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
07-26 17:27:52.090 10011 10049 D BtGatt.ScanManager: handling starting scan
07-26 17:27:52.090  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:52.090  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-26 17:27:52.091  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:52.091 10011 10049 D BluetoothAdapter: STATE_ON
07-26 17:27:52.092  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-26 17:27:52.092  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:52.093 10011 10049 D BluetoothAdapter: STATE_ON
,07-26 17:27:52.093  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:52.093  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
07-26 17:27:52.093  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-26 17:27:52.093  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-26 17:27:52.094  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
07-26 17:27:52.094  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-26 17:27:52.094  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-26 17:27:52.094  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:52.094  9888  9951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,07-26 17:27:52.102  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:52.102  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-26 17:27:52.102  9888  9888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-26 17:27:52.102  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:52.103 10011 10031 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-26 17:27:52.103 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 17:27:52.104 10011 10049 D BtGatt.ScanManager: set filter index= 6 for clientIf= 5
07-26 17:27:52.104 10011 10049 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-26 17:27:52.104 10011 10049 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-26 17:27:52.104 10011 10049 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
,07-26 17:27:52.105  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:52.114 10011 10031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
07-26 17:27:52.114 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:52.115 10011 10049 D BtGatt.ScanManager: Starting BLE batch scan
07-26 17:27:52.115 10011 10049 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-26 17:27:52.126 10011 10031 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-26 17:27:52.126 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 17:27:52.133 10011 10031 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-26 17:27:52.134 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 17:27:52.135  3714 10158 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{74406b: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
,07-26 17:27:52.149  3714  4543 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170726T172752 - CU:1002/CP:10011
07-26 17:27:52.149  3714  4543 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172753, SetElapsed=321423, nowELAPSED=320434
,07-26 17:27:52.555  3714  3799 D PowerManagerService: [s] UserActivityState : 1 -> 4
07-26 17:27:52.555  3714  3799 D PowerManagerService: mDisplayReady: false
07-26 17:27:52.555  3714  3799 I PowerManagerService: [PWL] On : 0 (320840 ms ago)
07-26 17:27:52.555  3714  3799 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
07-26 17:27:52.556  3714  3799 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-26 17:27:52.556  3714  3799 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-26 17:27:52.556  3714  3799 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-26 17:27:52.556  3714  3799 D DisplayPowerController: Animating brightness: target=57, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-26 17:27:52.557  3714  3799 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-26 17:27:52.558  3714  3799 D PowerManagerService: mDisplayReady: true
,07-26 17:27:52.565  3714  4038 D lights  : lcd : 91 +
,07-26 17:27:52.572  3714  4038 D lights  : lcd : 91 -
,07-26 17:27:52.581  3714  4038 D lights  : lcd : 58 +
,07-26 17:27:52.583  3714  4038 D lights  : lcd : 58 -
,07-26 17:27:52.598  3714  3799 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-26 17:27:52.598  3714  4038 D lights  : lcd : 57 +
07-26 17:27:52.598  3714  3799 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-26 17:27:52.598  3714  3799 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-26 17:27:52.598  3714  3799 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-26 17:27:52.600  3714  4038 D lights  : lcd : 57 -
,07-26 17:27:52.604  9888  9888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
07-26 17:27:52.605  9888  9888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 17:27:52.605  9888  9888 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-26 17:27:53.142  3714  3864 D SamsungAlarmManager: Expired : 4
,07-26 17:27:53.143  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172759, SetElapsed=327889, nowELAPSED=321427
07-26 17:27:53.144  3714  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{ae237c8 type 2 when 320923 com.android.bluetooth}
,07-26 17:27:53.151 10011 10011 D BtGatt.ScanManager: awakened up at time 321435
07-26 17:27:53.154 10011 10049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-26 17:27:53.169  3714  4938 I ActivityManager: KPU : put [com.sec.android.widgetapp.samsungapps] : 26684 K
07-26 17:27:53.169  3714  4938 I ActivityManager: Killing 9536:com.sec.android.widgetapp.samsungapps/u0a105 (adj 906): DHA:empty #33
,07-26 17:27:53.175  3714  4938 I ActivityManager: KPU : put [com.sec.android.app.sbrowser] : 21628 K
,07-26 17:27:53.175  3714  4938 I ActivityManager: Killing 9480:com.sec.android.app.sbrowser/u0a134 (adj 906): DHA:empty #33
07-26 17:27:53.187 10011 10031 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-26 17:27:53.187 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:53.188 10011 10031 D BtGatt.GattService: current time is 321472222655
07-26 17:27:53.188 10011 10031 D BtGatt.GattService: Batch record : [52, -48, 117, -85, -113, 99, 1, -128, -57, 6, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-26 17:27:53.191 10011 10031 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-26 17:27:53.192 10011 10031 D ScanRecord: parseFromBytes
07-26 17:27:53.194  3714  4543 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{c00e061: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
07-26 17:27:53.194  9888  9900 D ScanRecord: parseFromBytes
,07-26 17:27:53.196  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=63:8F:AB:75:D0:34, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-57, mTimestampNanos=321173019847}
07-26 17:27:53.198  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-26 17:27:53.198  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-26 17:27:53.204  3714  4859 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170726T172753 - CU:1002/CP:10011
07-26 17:27:53.205  3714  4859 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172754, SetElapsed=322479, nowELAPSED=321489
,07-26 17:27:53.228  3714  3923 D ActivityManager: cleanUpApplicationRecord -- 9480
,07-26 17:27:53.230  4844  4855 D ForegroundUtils: could not check pending caller
,07-26 17:27:53.240  3714  4858 D ActivityManager: cleanUpApplicationRecord -- 9536
,07-26 17:27:53.241  4844  4856 D ForegroundUtils: could not check pending caller
,07-26 17:27:54.163  4649  4649 D io_stats: !@   8,0 r 26220 2302548 w 5604 211928 d 736 74204 f 2238 2238 iot 12260 11268 th 473948 0 0 pt 0 inp 0 0 322.446
,07-26 17:27:54.195  3714  3864 D SamsungAlarmManager: Expired : 4
,07-26 17:27:54.196  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172759, SetElapsed=327889, nowELAPSED=322480
07-26 17:27:54.197  3714  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{cc34786 type 2 when 321978 com.android.bluetooth}
,07-26 17:27:54.203 10011 10011 D BtGatt.ScanManager: awakened up at time 322487
,07-26 17:27:54.205 10011 10049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-26 17:27:54.230 10011 10031 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-26 17:27:54.230 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:54.230 10011 10031 D BtGatt.GattService: current time is 322515110000
07-26 17:27:54.230 10011 10031 D BtGatt.GattService: Batch record : [52, -48, 117, -85, -113, 99, 1, -128, -56, 6, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-26 17:27:54.231 10011 10031 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-26 17:27:54.231 10011 10031 D ScanRecord: parseFromBytes
07-26 17:27:54.232  3714  4937 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{6947847: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
07-26 17:27:54.233  9888  9899 D ScanRecord: parseFromBytes
07-26 17:27:54.234  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=63:8F:AB:75:D0:34, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-56, mTimestampNanos=322215398115}
,07-26 17:27:54.236  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-26 17:27:54.237  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-26 17:27:54.249  3714  4541 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170726T172754 - CU:1002/CP:10011
07-26 17:27:54.249  3714  4541 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172755, SetElapsed=323518, nowELAPSED=322533
,07-26 17:27:54.947  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:54.948  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:27:54.999  3714  5765 D SSRM:f  : SIOP:: AP = 300, PST = 313 (W:10), CP = 253, CUR = -6, LCD = 57
,07-26 17:27:55.106  9888  9951 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
07-26 17:27:55.107  9888  9951 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
07-26 17:27:55.107  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,07-26 17:27:55.107  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-26 17:27:55.111  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:55.111  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
,07-26 17:27:55.112  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.112  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-26 17:27:55.115  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-26 17:27:55.115  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
,07-26 17:27:55.116  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.116  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
07-26 17:27:55.116  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 64731
07-26 17:27:55.116  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
07-26 17:27:55.116  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
07-26 17:27:55.116  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
07-26 17:27:55.116  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
07-26 17:27:55.116  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
07-26 17:27:55.116  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
07-26 17:27:55.116  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
07-26 17:27:55.116  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.116  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
,07-26 17:27:55.117  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.117  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.118  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 17:27:55.118  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 17:27:55.118  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.119  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:55.119  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:55.121  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:55.122  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:55.123 10011 10088 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
07-26 17:27:55.124  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-26 17:27:55.124 10011 10049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-26 17:27:55.125  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:55.129  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:55.129  9888  9951 D BluetoothLeScanner: Stop Scan
,07-26 17:27:55.131 10011 10022 D BtGatt.GattService: stopScan() - queue size =1
,07-26 17:27:55.132 10011 10022 D BtGatt.GattService: stopScan() - queue size =1
07-26 17:27:55.132 10011 10059 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
07-26 17:27:55.134 10011 10022 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-26 17:27:55.135  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 17:27:55.136  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.136  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-26 17:27:55.136 10011 10031 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-26 17:27:55.136  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.137 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:55.137  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 17:27:55.137 10011 10031 D BtGatt.GattService: current time is 323421574461
07-26 17:27:55.137 10011 10031 D BtGatt.GattService: Batch record : [52, -48, 117, -85, -113, 99, 1, -128, -52, 3, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-26 17:27:55.137  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.137 10011 10031 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-26 17:27:55.137 10011 10031 D ScanRecord: parseFromBytes
07-26 17:27:55.137  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.138  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-26 17:27:55.138 10011 10031 E BtGatt.ContextMap: Context not found for ID 5
07-26 17:27:55.138  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-26 17:27:55.138  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 64731
07-26 17:27:55.138  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=64731, mManufacturerData=null, mManufacturerDataMask=null]
07-26 17:27:55.138  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.138  9888  9951 D BluetoothLeScanner: Start Scan
07-26 17:27:55.139  3714  4546 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{7c70874: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
07-26 17:27:55.143  3714  3725 I art     : Background sticky concurrent mark sweep GC freed 220202(12MB) AllocSpace objects, 35(748KB) LOS objects, 26% free, 41MB/56MB, paused 3.264ms total 144.006ms
07-26 17:27:55.143  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:55.145  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:55.147  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:55.149  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:55.155 10011 10023 D BtGatt.GattService: registerClient() - UUID=238a9f3e-3a65-4d80-87db-1a5e532e8317
07-26 17:27:55.157  3714  4546 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172759, SetElapsed=327889, nowELAPSED=323442
,07-26 17:27:55.169  3714 10158 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170726T172755 - CU:1002/CP:10011
07-26 17:27:55.169  3714 10158 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172756, SetElapsed=324443, nowELAPSED=323453
,07-26 17:27:55.170 10011 10049 D BtGatt.ScanManager: filter size is 1
07-26 17:27:55.170 10011 10049 D BtGatt.ScanManager: delete FilterIndex - 6
,07-26 17:27:55.175 10011 10031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,07-26 17:27:55.175 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:55.176 10011 10049 D BtGatt.ScanManager: stopping BLe Batch
,07-26 17:27:55.181 10011 10031 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-26 17:27:55.181 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:55.181 10011 10049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-26 17:27:55.186 10011 10031 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-26 17:27:55.186 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 17:27:55.187  3714  3946 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{20a219d: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
07-26 17:27:55.188  3714  3946 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172759, SetElapsed=327889, nowELAPSED=323473
,07-26 17:27:55.189  3714  4900 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{fc5612: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
,07-26 17:27:55.258 10011 10031 D BtGatt.GattService: onClientRegistered() - UUID=238a9f3e-3a65-4d80-87db-1a5e532e8317, clientIf=5, status=0
,07-26 17:27:55.260  9888  9899 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
07-26 17:27:55.261 10011 10022 D BtGatt.GattService: start scan with filters
,07-26 17:27:55.265 10011 10022 D BtGatt.GattService: getScanSettings
,07-26 17:27:55.268 10011 10022 D BtGatt.GattService: Is it foreground application = true
,07-26 17:27:55.268 10011 10022 D BtGatt.GattService: not a background application
,07-26 17:27:55.281 10011 10059 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
07-26 17:27:55.281 10011 10059 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b1f6bdc
07-26 17:27:55.281  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
07-26 17:27:55.282  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.282 10011 10049 D BtGatt.ScanManager: handling starting scan
07-26 17:27:55.283  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-26 17:27:55.284  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.284 10011 10049 D BluetoothAdapter: STATE_ON
07-26 17:27:55.285  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.285  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:55.286  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:55.286  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-26 17:27:55.286  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
07-26 17:27:55.286 10011 10049 D BluetoothAdapter: STATE_ON
07-26 17:27:55.286  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
07-26 17:27:55.287  9888  9951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-26 17:27:55.287  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-26 17:27:55.287  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 17:27:55.287  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-26 17:27:55.288  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-26 17:27:55.290  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-26 17:27:55.292  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-26 17:27:55.293  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-26 17:27:55.293  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-26 17:27:55.293  9888 10543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-26 17:27:55.293  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-26 17:27:55.294  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,07-26 17:27:55.296  9888  9888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-26 17:27:55.301  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-26 17:27:55.302 10011 10031 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-26 17:27:55.302  9888  9951 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 17:27:55.302 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 17:27:55.304 10011 10049 D BtGatt.ScanManager: set filter index= 7 for clientIf= 5
,07-26 17:27:55.304 10011 10049 D BtGatt.ScanManager: High Rssi Filter value is = -128
,07-26 17:27:55.308  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:55.311 10011 10049 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-26 17:27:55.311  9888 10543 D BluetoothSocket: bindListen(): myUserId = 0
07-26 17:27:55.312  9888 10543 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 17:27:55.312 10011 10049 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
07-26 17:27:55.312  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:55.324  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:55.324 10011 10031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,07-26 17:27:55.324 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:55.325 10011 10049 D BtGatt.ScanManager: Starting BLE batch scan
07-26 17:27:55.325 10011 10049 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-26 17:27:55.327  9888 10543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-26 17:27:55.327  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:55.327  9888 10543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@ab07a44, port: 6, type: 1, local socket address: null, socket type: 0
,07-26 17:27:55.337  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:55.338 10011 10031 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-26 17:27:55.338 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 17:27:55.343  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:55.343  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.344  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.344  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-26 17:27:55.344  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,07-26 17:27:55.345  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "35d3e8aa-16e9-4ee5-85be-d6766e758699", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-26 17:27:55.345  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E 94 4A 3E
07-26 17:27:55.346  9888  9951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:55.346  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:55.346  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.347 10011 10031 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-26 17:27:55.347 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 17:27:55.347  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.347  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-26 17:27:55.347  3714  3739 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{19651e3: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
07-26 17:27:55.348  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-26 17:27:55.348  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.349  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.350  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[35d3e8aa-16e9-4ee5-85be-d6766e758699], mManufacturerSpecificData={}, mServiceData={35d3e8aa-16e9-4ee5-85be-d6766e758699=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:55.352  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:55.353  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:55.353  9888  9951 D BluetoothAdapter: isSecureModeEnabled
07-26 17:27:55.354 10011 10088 D BtConfig.SecureMode: isSecureModeOn:false
07-26 17:27:55.354  9888  9951 D BluetoothLeAdvertiser: start advertising
,07-26 17:27:55.356  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:55.357  3714  4938 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170726T172755 - CU:1002/CP:10011
07-26 17:27:55.358  3714  4938 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172756, SetElapsed=324633, nowELAPSED=323642
,07-26 17:27:55.362 10011 10032 D BtGatt.GattService: registerClient() - UUID=fd1015ae-f1b9-42e1-9719-03c4063ba1fd
,07-26 17:27:55.465 10011 10031 D BtGatt.GattService: onClientRegistered() - UUID=fd1015ae-f1b9-42e1-9719-03c4063ba1fd, clientIf=6, status=0
,07-26 17:27:55.465  9888  9900 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,07-26 17:27:55.467 10011 10088 E BtGatt.ContextMap: Context not found for ID 6
07-26 17:27:55.468 10011 10048 D BtGatt.AdvertiseManager: message : 0
,07-26 17:27:55.468 10011 10059 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-26 17:27:55.469 10011 10048 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-26 17:27:55.469 10011 10048 D BtGatt.AdvertiseManager: size of list is =0
,07-26 17:27:55.473 10011 10048 D BtGatt.AdvertiseManager: starting advertising
,07-26 17:27:55.476 10011 10048 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-26 17:27:55.479 10011 10065 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-26 17:27:55.497 10011 10031 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,07-26 17:27:55.500 10011 10048 D BtGatt.AdvertiseManager: starting multi advertising
,07-26 17:27:55.507 10011 10031 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,07-26 17:27:55.507 10011 10048 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-26 17:27:55.507 10011 10048 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-26 17:27:55.508 10011 10048 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
07-26 17:27:55.508 10011 10048 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
07-26 17:27:55.508  9888  9899 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-26 17:27:55.509  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.510  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.510  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-26 17:27:55.511  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:55.512  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.512  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:55.513  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.514  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:55.514  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.515  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:55.516  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.516  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
07-26 17:27:55.516  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
07-26 17:27:55.516  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-26 17:27:55.519  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-26 17:27:55.520  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:55.525  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:55.525  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:55.526  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:55.527  9888  9888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-26 17:27:55.528  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-26 17:27:55.529  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:55.529  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-26 17:27:55.529  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-26 17:27:55.530  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-26 17:27:55.531  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:55.531  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:55.531  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
07-26 17:27:55.531  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,07-26 17:27:55.532  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-26 17:27:55.533  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-26 17:27:55.533  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-26 17:27:55.534  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-26 17:27:55.534  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-26 17:27:55.540  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-26 17:27:55.540  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
07-26 17:27:55.541  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,07-26 17:27:55.542  9888  9888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-26 17:27:55.542  9888  9888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,07-26 17:27:56.043  9888  9888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
07-26 17:27:56.044  9888  9888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-26 17:27:56.044  9888  9888 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-26 17:27:56.234  3714 10547 D WifiMHD::s: req(2):1, 7, 1
,07-26 17:27:56.237  3714 10547 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 17:27:56.238  3714 10547 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:27:56.240  3298  3769 D EnterpriseController: netId is 0
07-26 17:27:56.240  3298  3769 D Netd    : getNetworkForDns: using netid 503 for uid 1000
07-26 17:27:56.240  3298  3769 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-26 17:27:56.349  3714  3864 D SamsungAlarmManager: Expired : 4
,07-26 17:27:56.350  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172759, SetElapsed=327889, nowELAPSED=324634
07-26 17:27:56.351  3714  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{f6c3a99 type 2 when 324132 com.android.bluetooth}
,07-26 17:27:56.356 10011 10011 D BtGatt.ScanManager: awakened up at time 324641
,07-26 17:27:56.359 10011 10049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-26 17:27:56.371  3714  3739 I ActivityManager: KPU : put [com.wssnps] : 26636 K
07-26 17:27:56.371  3714  3739 I ActivityManager: Killing 9559:com.wssnps/1000 (adj 906): DHA:empty #33
,07-26 17:27:56.382 10011 10031 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-26 17:27:56.382 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:56.382 10011 10031 D BtGatt.GattService: current time is 324666987537
07-26 17:27:56.382 10011 10031 D BtGatt.GattService: Batch record : [52, -48, 117, -85, -113, 99, 1, -128, -56, 19, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-26 17:27:56.383 10011 10031 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-26 17:27:56.383 10011 10031 D ScanRecord: parseFromBytes
07-26 17:27:56.383  3714  4858 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{645c15e: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
,07-26 17:27:56.384  9888  9900 D ScanRecord: parseFromBytes
,07-26 17:27:56.385  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=63:8F:AB:75:D0:34, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-56, mTimestampNanos=323717185229}
07-26 17:27:56.386  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-26 17:27:56.387  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-26 17:27:56.394  3714  3946 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170726T172756 - CU:1002/CP:10011
,07-26 17:27:56.394  3714  3946 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172757, SetElapsed=325669, nowELAPSED=324679
,07-26 17:27:56.407  3714  4859 D ActivityManager: cleanUpApplicationRecord -- 9559
,07-26 17:27:56.409  4844  4855 D ForegroundUtils: could not check pending caller
,07-26 17:27:56.417  3714  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-26 17:27:57.385  3714  3864 D SamsungAlarmManager: Expired : 4
,07-26 17:27:57.386  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172759, SetElapsed=327889, nowELAPSED=325670
07-26 17:27:57.387  3714  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{952293f type 2 when 325168 com.android.bluetooth}
,07-26 17:27:57.393 10011 10011 D BtGatt.ScanManager: awakened up at time 325677
,07-26 17:27:57.395 10011 10049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-26 17:27:57.421 10011 10031 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-26 17:27:57.421 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:57.421 10011 10031 D BtGatt.GattService: current time is 325706153459
07-26 17:27:57.421 10011 10031 D BtGatt.GattService: Batch record : [52, -48, 117, -85, -113, 99, 1, -128, -57, 9, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
,07-26 17:27:57.422 10011 10031 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-26 17:27:57.423 10011 10031 D ScanRecord: parseFromBytes
07-26 17:27:57.423  3714  4543 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{646f20c: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
,07-26 17:27:57.424  9888  9899 D ScanRecord: parseFromBytes
07-26 17:27:57.426  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=63:8F:AB:75:D0:34, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-57, mTimestampNanos=325256444459}
,07-26 17:27:57.427  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-26 17:27:57.428  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-26 17:27:57.439  3714  3739 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170726T172757 - CU:1002/CP:10011
07-26 17:27:57.439  3714  3739 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172758, SetElapsed=326709, nowELAPSED=325724
,07-26 17:27:57.490  3714  4018 D WifiWatchdogStateMachine:  [|215] []
,07-26 17:27:57.978  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:27:57.978  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -41
,07-26 17:27:58.181  3714  4858 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-26 17:27:58.182  3714  4858 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-26 17:27:58.182  3714  4858 D BatteryService: online:4, current avg:-4, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-26 17:27:58.183  3714  3714 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-26 17:27:58.193  3714  3714 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-26 17:27:58.193  3714  3714 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-26 17:27:58.197  3714  3714 D GameManagerService: new battery level: 100
,07-26 17:27:58.204  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-26 17:27:58.204  4068  4068 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-26 17:27:58.212  4068  4068 D PowerUI : priorPlugType = 2 mPlugType =  2
07-26 17:27:58.218  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
07-26 17:27:58.219  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-26 17:27:58.239  4068  4068 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-26 17:27:58.241 10011 10011 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-26 17:27:58.242 10011 10068 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-26 17:27:58.425  3714  3864 D SamsungAlarmManager: Expired : 4
,07-26 17:27:58.426  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172759, SetElapsed=327889, nowELAPSED=326711
07-26 17:27:58.427  3714  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{b3ce755 type 2 when 326208 com.android.bluetooth}
,07-26 17:27:58.433 10011 10011 D BtGatt.ScanManager: awakened up at time 326717
,07-26 17:27:58.435 10011 10049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-26 17:27:58.460 10011 10031 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,07-26 17:27:58.461 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:58.461 10011 10031 D BtGatt.GattService: current time is 326745624266
07-26 17:27:58.461 10011 10031 D BtGatt.GattService: Batch record : [52, -48, 117, -85, -113, 99, 1, -128, -54, 6, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-26 17:27:58.462 10011 10031 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-26 17:27:58.462 10011 10031 D ScanRecord: parseFromBytes
07-26 17:27:58.462  3714  3738 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{828956a: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
,07-26 17:27:58.463  9888  9900 D ScanRecord: parseFromBytes
07-26 17:27:58.465  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=63:8F:AB:75:D0:34, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=326445919266}
,07-26 17:27:58.467  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-26 17:27:58.467  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-26 17:27:58.478  3714  4543 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170726T172758 - CU:1002/CP:10011
07-26 17:27:58.479  3714  4543 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172759, SetElapsed=327749, nowELAPSED=326763
,07-26 17:27:58.533  9888  9951 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,07-26 17:27:58.534  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 17:27:58.535  9888  9951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,07-26 17:27:58.535  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-26 17:27:58.535  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-26 17:27:58.536  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 17:27:58.536  9888 10543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-26 17:27:58.536  9888 10543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-26 17:27:58.536  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-26 17:27:58.536  9888 10543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-26 17:27:58.537  9888  9951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-26 17:27:58.537  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 17:27:58.537  9888  9951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30d535f removed from the list
07-26 17:27:58.537  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30d535f removed from the list
07-26 17:27:58.537  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 17:27:58.538  9888  9951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 17:27:58.539  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:58.539  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-26 17:27:58.539  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-26 17:27:58.540  9888  9888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-26 17:27:58.541  9888  9888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-26 17:27:58.541  9888  9888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-26 17:27:58.541  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:58.542  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:58.543  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:58.543  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-26 17:27:58.543  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:58.545  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:58.547  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:58.547 10011 10032 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
07-26 17:27:58.548  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-26 17:27:58.549 10011 10049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-26 17:27:58.550  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:58.554  9888  9951 D BluetoothAdapter: STATE_ON
07-26 17:27:58.554  9888  9951 D BluetoothLeScanner: Stop Scan
,07-26 17:27:58.555 10011 10031 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-26 17:27:58.555 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:58.555 10011 10023 D BtGatt.GattService: stopScan() - queue size =1
07-26 17:27:58.555 10011 10023 D BtGatt.GattService: stopScan() - queue size =1
07-26 17:27:58.556 10011 10059 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
07-26 17:27:58.556  3714  4937 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{ca1a5b: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
07-26 17:27:58.557 10011 10032 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-26 17:27:58.557  3714  4937 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172759, SetElapsed=327889, nowELAPSED=326842
,07-26 17:27:58.558  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 17:27:58.559  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:58.559  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-26 17:27:58.560  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:58.560  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:58.561  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:58.561  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-26 17:27:58.561  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:58.563  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:58.565  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:27:58.565  9888  9951 D BluetoothLeAdvertiser: stop advertising
,07-26 17:27:58.566  3714 10158 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170726T172759 - CU:1002/CP:10011
07-26 17:27:58.567 10011 10033 E BtGatt.ContextMap: Context not found for ID 6
07-26 17:27:58.567 10011 10048 D BtGatt.AdvertiseManager: message : 1
,07-26 17:27:58.567 10011 10059 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-26 17:27:58.568 10011 10049 D BtGatt.ScanManager: filter size is 1
07-26 17:27:58.568 10011 10049 D BtGatt.ScanManager: delete FilterIndex - 7
07-26 17:27:58.568 10011 10048 D BtGatt.AdvertiseManager: stop advertise for client =  6
07-26 17:27:58.568 10011 10048 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
07-26 17:27:58.571 10011 10048 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-26 17:27:58.573 10011 10031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
07-26 17:27:58.573 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:58.574 10011 10049 D BtGatt.ScanManager: stopping BLe Batch
,07-26 17:27:58.579 10011 10031 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
07-26 17:27:58.579 10011 10031 D BtGatt.GattService: Client app is not null!
,07-26 17:27:58.579  9888  9900 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-26 17:27:58.580 10011 10023 D BtGatt.GattService: unregisterClient() - clientIf=6
07-26 17:27:58.582  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-26 17:27:58.583  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:58.584 10011 10031 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-26 17:27:58.584 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:58.584 10011 10049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-26 17:27:58.584  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-26 17:27:58.586  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:58.589  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:58.589  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:58.589  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 17:27:58.590 10011 10031 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-26 17:27:58.591 10011 10031 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 17:27:58.591  9888  9951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 17:27:58.591  3714  4546 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{77722f8: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
,07-26 17:27:58.594  3714  3923 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10011 / op:PendingIntent{e31a3d1: PendingIntentRecord{6e75b9b com.android.bluetooth broadcastIntent}}
,07-26 17:27:58.594  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 17:27:58.595  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:58.598  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:58.598  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-26 17:27:58.598  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-26 17:27:58.599  9888  9951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-26 17:27:58.599  9888  9951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68da1ac removed from the list
07-26 17:27:58.599  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 17:27:58.599  9888  9951 D io.jxcore.node.ConnectivityMonitor: stop
07-26 17:27:58.599  9888  9888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 17:27:58.599  9888  9951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 17:27:58.599  9888  9951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 17:27:58.600  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,07-26 17:27:58.600  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:58.601  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-26 17:27:58.601  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
07-26 17:27:58.601  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-26 17:27:58.601  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-26 17:27:58.602  9888  9951 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
07-26 17:27:58.602  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-26 17:27:58.602  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-26 17:27:58.602  9888  9888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-26 17:27:58.602  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-26 17:27:58.603  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-26 17:27:58.603  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-26 17:27:58.603  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 17:27:58.603  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-26 17:27:58.603  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-26 17:27:58.603  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-26 17:27:58.603  9888  9951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-26 17:27:58.603  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-26 17:27:58.604  9888  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-26 17:27:58.604  9888  9888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 17:27:58.605  9888  9951 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
07-26 17:27:58.605  9888  9893 I art     : Do partial code cache collection, code=18KB, data=31KB
,07-26 17:27:58.607  9888  9893 I art     : After code cache collection, code=17KB, data=29KB
07-26 17:27:58.607  9888  9893 I art     : Increasing code cache capacity to 128KB
,07-26 17:27:58.609  9888  9951 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,07-26 17:27:58.611  9888  9951 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,07-26 17:27:58.613  9888  9951 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,07-26 17:27:58.614  9888  9951 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,07-26 17:27:58.616  9888  9951 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,07-26 17:27:58.618  9888  9951 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,07-26 17:27:58.619  9888  9951 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,07-26 17:27:59.105  9888  9888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-26 17:27:59.169  4649  4649 D io_stats: !@   8,0 r 26220 2302548 w 5631 212296 d 741 74224 f 2244 2244 iot 12260 11279 th 474996 0 0 pt 0 inp 0 0 327.451
,07-26 17:27:59.605  3714  3864 D SamsungAlarmManager: Expired : 4
,07-26 17:27:59.606  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172800, SetElapsed=328797, nowELAPSED=327890
07-26 17:27:59.607  3714  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@f6b0e4f alarm=Alarm{fb29e36 type 2 when 327889 android}
07-26 17:27:59.610  3714  3929 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 16000: mInRange : true
,07-26 17:27:59.617  3714  3929 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T172815 - CU:1000/CP:3714
,07-26 17:28:00.001  3714  3864 D SamsungAlarmManager: Expired : 8
,07-26 17:28:00.002  3714  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{17776a4 type 3 when 328285 android}
,07-26 17:28:00.011  3714  3714 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170726T172859 - CU:1000/CP:3714
,07-26 17:28:00.015  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-26 17:28:00.016  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#start
,07-26 17:28:00.016  4068  4068 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-26 17:28:00.036  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#end
07-26 17:28:00.036  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-26 17:28:00.038  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-26 17:28:00.047  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-26 17:28:00.049  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:28:00.053  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
07-26 17:28:00.055  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:28:00.077  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-26 17:28:00.079  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:28:00.080  4068  4068 V hong    : mid yDiff = 438
,07-26 17:28:00.081  4068  4068 V hong    : mid yDiff = 438
07-26 17:28:00.082  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
,07-26 17:28:00.082  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-26 17:28:00.093  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-26 17:28:00.095  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:28:00.106  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-26 17:28:00.108  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:28:00.123  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-26 17:28:00.127  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-26 17:28:00.131  5128  5128 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-26 17:28:00.135  5128  5128 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-26 17:28:00.143  5128  5128 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-26 17:28:00.153  5128  5128 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-26 17:28:00.154  5128  5128 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-26 17:28:00.155  5128  5128 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-26 17:28:00.156  5128  5128 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,07-26 17:28:00.157  5128  5128 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-26 17:28:00.167  5128  5128 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-26 17:28:00.169  5128  5128 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C5B5B7C29AF99E6CE15828BE2E6B30941E777ABCB13BDD1D2360E555E3570AD2381EBA8D4349FC9D422595CBB2B9D4D6E]}
07-26 17:28:00.170  5128  5128 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-26 17:28:00.513  3714  3864 D SamsungAlarmManager: Expired : 4
07-26 17:28:00.514  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172815, SetElapsed=343896, nowELAPSED=328798
,07-26 17:28:00.514  3714  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@2549978 alarm=Alarm{cdbac0d type 2 when 328797 android}
07-26 17:28:00.515  3714  3956 E SupplicantWifiScannerImpl: Timed out waiting for scan result from supplicant
,07-26 17:28:00.521 10315 10315 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-26 17:28:00.522 10315 10315 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-26 17:28:00.534  3714  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T172815 - CU:1000/CP:3714
,07-26 17:28:00.541 10315 10315 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-26 17:28:00.626  9888  9951 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,07-26 17:28:00.754  9888 10550 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 254, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:00.754  9888 10550 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:00.754  9888 10550 D io.jxcore.node.StreamCopyingThread:  id: 83
,07-26 17:28:00.994  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:00.994  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -41
,07-26 17:28:01.544  9888 10550 W !!      : call onHalfStreamCopied
07-26 17:28:01.545  9888 10550 I testCopyDataAndClose: closing input stream
,07-26 17:28:01.567  3714  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 254, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread:  id: 83
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread:  id: 83
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 254, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:02.220  9888 10550 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,07-26 17:28:03.189  3714  4901 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10112
,07-26 17:28:03.198 10487 10487 I Babel_ConcService: Binding ConcurrentService
,07-26 17:28:03.234 10487 10552 I Babel_ConcService: Scheduling delay with GcmNetworkManager of 244723 s for task fstaccount_reg_renewal_25878_3 and tag network_connectivity_wakeup:persisted
,07-26 17:28:03.242  3714  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
07-26 17:28:03.243 10487 10553 I Babel_ConcService: Acquired partial wake lock to keep ConcurrentService alive
,07-26 17:28:03.246 10487 10553 I Babel_ConcService: Released partial wake lock as ConcurrentService became idle
,07-26 17:28:03.247 10487 10555 I Babel_ConcService: Acquired partial wake lock to keep ConcurrentService alive
07-26 17:28:03.249 10487 10554 I Babel_ConcService: Released partial wake lock as ConcurrentService became idle
,07-26 17:28:03.265 10487 10556 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
07-26 17:28:03.265 10487 10552 I Babel_ConcService: Scheduling delay with GcmNetworkManager of 3599 s for task fvzDB_CLEANUP_331459_1 and tag timed_wakeup
,07-26 17:28:03.269 10487 10557 I Babel_ConcService: Acquired partial wake lock to keep ConcurrentService alive
07-26 17:28:03.270 10487 10557 I Babel_ConcService: Released partial wake lock as ConcurrentService became idle
,07-26 17:28:03.289  3714  4541 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{7484572: PendingIntentRecord{7835d27 com.google.android.gms broadcastIntent}}
,07-26 17:28:03.302  3714  4546 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170726T182332 - CU:10019/CP:4779
,07-26 17:28:03.349  3714  3739 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4779 / op:PendingIntent{71a7dc3: PendingIntentRecord{7835d27 com.google.android.gms broadcastIntent}}
,07-26 17:28:03.360  3714  4938 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170726T182717 - CU:10019/CP:4779
,07-26 17:28:03.620  9888  9951 I StreamCopyingThreadTest: Starting test: testCopyBigData
,07-26 17:28:03.650  9888 10558 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 257, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:03.650  9888 10558 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:03.650  9888 10558 D io.jxcore.node.StreamCopyingThread:  id: 85
,07-26 17:28:04.010  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:04.010  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -41
,07-26 17:28:04.173  4649  4649 D io_stats: !@   8,0 r 26220 2302548 w 5655 212560 d 744 74236 f 2256 2256 iot 12270 11291 th 473764 0 0 pt 0 inp 0 0 332.456
,07-26 17:28:04.539  3298  3766 D Netd    : Iface wlan0 link up
,07-26 17:28:04.541 10315 10315 I wpa_supplicant: nl80211: Received scan results (20 BSSes)
07-26 17:28:04.542  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:28:04.542  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
,07-26 17:28:04.547  3714  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@70267c2
,07-26 17:28:05.032  3714  5765 D SSRM:f  : SIOP:: AP = 340, PST = 315 (W:6), CP = 253, CUR = -108, LCD = 57
,07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 257, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread:  id: 85
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread:  id: 85
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 257, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:05.092  9888 10558 D io.jxcore.node.StreamCopyingThread:  id: 85 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,07-26 17:28:05.098  3714  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-26 17:28:05.111  3714  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-26 17:28:05.125  3714  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-26 17:28:05.134  3714  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-26 17:28:05.142  3714  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-26 17:28:05.628  3714  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-26 17:28:06.014  3714  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-26 17:28:06.462  9888  9951 I StreamCopyingThreadTest: Starting test: testRunNotify
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 259, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread:  id: 86
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 259, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread:  id: 86
,07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread:  id: 86
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 259, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:06.463  9888 10559 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
07-26 17:28:06.463  9888  9951 I StreamCopyingThreadTest: Starting test: testSetBufferSize
07-26 17:28:06.463  9888  9951 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-26 17:28:06.464  9888  9951 I StreamCopyingThreadTest: Starting test: testRunWithException
,07-26 17:28:06.464  9888 10560 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 263, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:06.464  9888 10560 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:06.464  9888 10560 D io.jxcore.node.StreamCopyingThread:  id: 89
07-26 17:28:06.464  9888 10560 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 263, thread name: My test thread name): Test exception.
07-26 17:28:06.464  9888 10560 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 263, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:06.464  9888 10560 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:06.464  9888 10560 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
07-26 17:28:06.464  9888 10560 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
07-26 17:28:06.464  9888 10560 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 263, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-26 17:28:06.464  9888 10560 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-26 17:28:06.464  9888 10560 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
07-26 17:28:06.465  9888  9951 I jxcore-log: 2017-07-26 15:28:06 - DEBUG UnitTest_app: 'Running unit tests'
07-26 17:28:06.465  9888  9951 I jxcore-log: 
07-26 17:28:06.465  9888  9951 I jxcore-log: *Native tests were executed*
07-26 17:28:06.465  9888  9951 I jxcore-log: 
07-26 17:28:06.465  9888  9951 I jxcore-log: Total number of executed tests:  78
07-26 17:28:06.465  9888  9951 I jxcore-log: 
07-26 17:28:06.465  9888  9951 I jxcore-log: Number of passed tests:  76
07-26 17:28:06.465  9888  9951 I jxcore-log: 
07-26 17:28:06.465  9888  9951 I jxcore-log: Number of failed tests:  0
07-26 17:28:06.465  9888  9951 I jxcore-log: 
07-26 17:28:06.465  9888  9951 I jxcore-log: Number of ignored tests:  2
07-26 17:28:06.465  9888  9951 I jxcore-log: 
07-26 17:28:06.466  9888  9951 I jxcore-log: Total duration:  48161
07-26 17:28:06.466  9888  9951 I jxcore-log: 
07-26 17:28:06.466  9888  9951 I jxcore-log: 2017-07-26 15:28:06 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G930F''
07-26 17:28:06.466  9888  9951 I jxcore-log: 
07-26 17:28:06.466  9888  9951 I jxcore-log: 2017-07-26 15:28:06 - WARN testUtils: 'myNameCallback not set!'
07-26 17:28:06.466  9888  9951 I jxcore-log: 
,07-26 17:28:07.035  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:07.035  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:07.922  9888  9951 I jxcore-log: 2017-07-26 15:28:07 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
07-26 17:28:07.922  9888  9951 I jxcore-log: 
,07-26 17:28:07.927  9888  9951 I jxcore-log: 2017-07-26 15:28:07 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
07-26 17:28:07.927  9888  9951 I jxcore-log: 
,07-26 17:28:07.936  9888  9951 I jxcore-log: 2017-07-26 15:28:07 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
07-26 17:28:07.936  9888  9951 I jxcore-log: 
,07-26 17:28:08.092  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
07-26 17:28:08.092  9888  9951 I jxcore-log: 
,07-26 17:28:08.122  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
07-26 17:28:08.122  9888  9951 I jxcore-log: 
,07-26 17:28:08.130  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testTests.js'
07-26 17:28:08.130  9888  9951 I jxcore-log: 
,07-26 17:28:08.167  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testUsn.js'
07-26 17:28:08.167  9888  9951 I jxcore-log: 
,07-26 17:28:08.190  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
07-26 17:28:08.190  9888  9951 I jxcore-log: 
,07-26 17:28:08.194  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
07-26 17:28:08.194  9888  9951 I jxcore-log: 
,07-26 17:28:08.239  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
07-26 17:28:08.239  9888  9951 I jxcore-log: 
,07-26 17:28:08.242  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
07-26 17:28:08.242  9888  9951 I jxcore-log: 
,07-26 17:28:08.245  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
07-26 17:28:08.245  9888  9951 I jxcore-log: 
,07-26 17:28:08.249  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
07-26 17:28:08.249  9888  9951 I jxcore-log: 
,07-26 17:28:08.565  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
07-26 17:28:08.565  9888  9951 I jxcore-log: 
,07-26 17:28:08.570  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
07-26 17:28:08.570  9888  9951 I jxcore-log: 
,07-26 17:28:08.634  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testHttp.js'
07-26 17:28:08.634  9888  9951 I jxcore-log: 
,07-26 17:28:08.637  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
07-26 17:28:08.637  9888  9951 I jxcore-log: 
,07-26 17:28:08.655  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
07-26 17:28:08.655  9888  9951 I jxcore-log: 
,07-26 17:28:08.659  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
07-26 17:28:08.659  9888  9951 I jxcore-log: 
,07-26 17:28:08.691  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
07-26 17:28:08.691  9888  9951 I jxcore-log: 
,07-26 17:28:08.713  3714  3738 I ActivityManager: KPU : put [com.sec.android.app.shealth] : 25864 K
07-26 17:28:08.713  3714  3738 I ActivityManager: Killing 9524:com.sec.android.app.shealth/u0a36 (adj 906): DHA:empty #33
,07-26 17:28:08.734  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
07-26 17:28:08.734  9888  9951 I jxcore-log: 
,07-26 17:28:08.754  3714  3739 D ActivityManager: cleanUpApplicationRecord -- 9524
,07-26 17:28:08.756  4844  4856 D ForegroundUtils: could not check pending caller
,07-26 17:28:08.767  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
07-26 17:28:08.767  9888  9951 I jxcore-log: 
,07-26 17:28:08.795  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
07-26 17:28:08.795  9888  9951 I jxcore-log: 
,07-26 17:28:08.804  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
07-26 17:28:08.804  9888  9951 I jxcore-log: 
,07-26 17:28:08.850  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
07-26 17:28:08.850  9888  9951 I jxcore-log: 
,07-26 17:28:08.879  9888  9951 I jxcore-log: 2017-07-26 15:28:08 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
07-26 17:28:08.879  9888  9951 I jxcore-log: 
,07-26 17:28:09.180  4649  4649 D io_stats: !@   8,0 r 26220 2302548 w 5674 212696 d 744 74236 f 2257 2257 iot 12270 11293 th 470004 0 0 pt 0 inp 0 0 337.463
,07-26 17:28:09.505  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
07-26 17:28:09.505  9888  9951 I jxcore-log: 
,07-26 17:28:09.531  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
07-26 17:28:09.531  9888  9951 I jxcore-log: 
,07-26 17:28:09.536  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
07-26 17:28:09.536  9888  9951 I jxcore-log: 
,07-26 17:28:09.540  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
07-26 17:28:09.540  9888  9951 I jxcore-log: 
,07-26 17:28:09.559  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
07-26 17:28:09.559  9888  9951 I jxcore-log: 
,07-26 17:28:09.578  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
07-26 17:28:09.578  9888  9951 I jxcore-log: 
,07-26 17:28:09.592  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
07-26 17:28:09.592  9888  9951 I jxcore-log: 
,07-26 17:28:09.599  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
07-26 17:28:09.599  9888  9951 I jxcore-log: 
,07-26 17:28:09.607  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
07-26 17:28:09.607  9888  9951 I jxcore-log: 
,07-26 17:28:09.616  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
07-26 17:28:09.616  9888  9951 I jxcore-log: 
,07-26 17:28:09.632  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
07-26 17:28:09.632  9888  9951 I jxcore-log: 
,07-26 17:28:09.646  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
07-26 17:28:09.646  9888  9951 I jxcore-log: 
,07-26 17:28:09.652  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
07-26 17:28:09.652  9888  9951 I jxcore-log: 
,07-26 17:28:09.816  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
07-26 17:28:09.816  9888  9951 I jxcore-log: 
,07-26 17:28:09.891  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
07-26 17:28:09.891  9888  9951 I jxcore-log: 
,07-26 17:28:09.904  9888  9951 D BluetoothAdapter: STATE_ON
,07-26 17:28:09.909  9888  9951 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-26 17:28:09.910  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO testUtils: 'BLE multiple advertisement supported'
07-26 17:28:09.910  9888  9951 I jxcore-log: 
,07-26 17:28:09.912  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - DEBUG UnitTest_app: 'Unit Test app is loaded'
07-26 17:28:09.912  9888  9951 I jxcore-log: 
,07-26 17:28:09.919  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-26 17:28:09.919  9888  9951 I jxcore-log: 
,07-26 17:28:09.919  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-26 17:28:09.919  9888  9951 I jxcore-log: 
07-26 17:28:09.920  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-26 17:28:09.920  9888  9951 I jxcore-log: 
07-26 17:28:09.920  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-26 17:28:09.920  9888  9951 I jxcore-log: 
07-26 17:28:09.920  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-26 17:28:09.920  9888  9951 I jxcore-log: 
07-26 17:28:09.920  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-26 17:28:09.920  9888  9951 I jxcore-log: 
,07-26 17:28:09.921  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-26 17:28:09.921  9888  9951 I jxcore-log: 
07-26 17:28:09.921  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-26 17:28:09.921  9888  9951 I jxcore-log: 
,07-26 17:28:09.921  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-26 17:28:09.921  9888  9951 I jxcore-log: 
07-26 17:28:09.921  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-26 17:28:09.921  9888  9951 I jxcore-log: 
07-26 17:28:09.921  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-26 17:28:09.921  9888  9951 I jxcore-log: 
07-26 17:28:09.922  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-26 17:28:09.922  9888  9951 I jxcore-log: 
,07-26 17:28:09.931  9888  9888 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
07-26 17:28:09.932  9888  9888 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,07-26 17:28:09.952  9888  9951 I jxcore-log: 2017-07-26 15:28:09 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
07-26 17:28:09.952  9888  9951 I jxcore-log: 
,07-26 17:28:10.014  9888  9951 I jxcore-log: 2017-07-26 15:28:10 - DEBUG CoordinatedClient: 'connected to the test server'
07-26 17:28:10.014  9888  9951 I jxcore-log: 
,07-26 17:28:10.047  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:10.047  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:10.189  9888  9951 I jxcore-log: 2017-07-26 15:28:10 - DEBUG CoordinatedClient: 'device disconnected from the test server'
07-26 17:28:10.189  9888  9951 I jxcore-log: 
,07-26 17:28:12.200  9888  9951 I jxcore-log: 2017-07-26 15:28:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:28:12.200  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:28:12.200  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:28:12.200  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:28:12.200  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:28:12.200  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:28:12.200  9888  9951 I jxcore-log: 
,07-26 17:28:12.204  9888  9951 I jxcore-log: 2017-07-26 15:28:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:28:12.204  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:28:12.204  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:28:12.204  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:28:12.204  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:28:12.204  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:28:12.204  9888  9951 I jxcore-log: 
,07-26 17:28:13.081  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:13.081  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:14.189  4649  4649 D io_stats: !@   8,0 r 26224 2302820 w 5677 212708 d 744 74236 f 2257 2257 iot 12270 11295 th 470732 0 0 pt 0 inp 0 0 342.468
,07-26 17:28:15.028  9888  9951 I jxcore-log: 2017-07-26 15:28:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:28:15.028  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:28:15.028  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:28:15.028  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:28:15.028  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:28:15.028  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:28:15.028  9888  9951 I jxcore-log: 
,07-26 17:28:15.034  9888  9951 I jxcore-log: 2017-07-26 15:28:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:28:15.034  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:28:15.034  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:28:15.034  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:28:15.034  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:28:15.034  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:28:15.034  9888  9951 I jxcore-log: 
,07-26 17:28:15.050  3714  5765 D SSRM:f  : SIOP:: AP = 340, PST = 315 (W:6), CP = 264, CUR = -111, LCD = 57
,07-26 17:28:15.412  3714  3714 D UsbMonitorService: readUsbState++
,07-26 17:28:15.414  3714  3714 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-26 17:28:15.416  3714  3714 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-26 17:28:15.416  3714  3714 D UsbMonitorService: Posting Message again
,07-26 17:28:15.612  3714  3864 D SamsungAlarmManager: Expired : 4
07-26 17:28:15.613  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T173657, SetElapsed=866043, nowELAPSED=343897
,07-26 17:28:15.614  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170726T172859, SetElapsed=388284, nowELAPSED=343898
,07-26 17:28:15.614  3714  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@f060137 alarm=Alarm{8c6f979 type 2 when 343896 android}
,07-26 17:28:15.618  3714  3929 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 32000: mInRange : true
07-26 17:28:15.622 10315 10315 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-26 17:28:15.622 10315 10315 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-26 17:28:15.629  3714  3929 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T172847 - CU:1000/CP:3714
07-26 17:28:15.634  3714  3929 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172847, SetElapsed=375903, nowELAPSED=343918
,07-26 17:28:15.642  3714  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T172830 - CU:1000/CP:3714
07-26 17:28:15.642  3714  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172830, SetElapsed=358913, nowELAPSED=343926
,07-26 17:28:15.643 10315 10315 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-26 17:28:16.104  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:16.104  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:16.794  3714  3739 I ActivityManager: KPU : put [com.sec.android.service.health] : 18136 K
07-26 17:28:16.794  3714  3739 I ActivityManager: Killing 9600:com.sec.android.service.health/u0a24 (adj 906): DHA:empty #33
,07-26 17:28:16.829  3714  4936 D ActivityManager: cleanUpApplicationRecord -- 9600
,07-26 17:28:16.834  4844  4856 D ForegroundUtils: could not check pending caller
,07-26 17:28:16.886  5015  5059 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 3ms lastUpdatedAfter : 26024 ms mFlush_time_threasold : 2000 mCurrentSize : 229
,07-26 17:28:16.930  5160 10571 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-26 17:28:16.965  5160  6762 I Icing   : App usage reports: 1
,07-26 17:28:16.968  5160  6762 I Icing   : Usage reports 1 indexed 0 rejected 0 imm upload false
,07-26 17:28:17.013  5160  6762 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-26 17:28:17.051  5160  6762 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-26 17:28:17.086  5160  6762 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-26 17:28:17.120  5160  6762 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-26 17:28:17.153  5160  6762 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-26 17:28:17.183  5160  6762 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-26 17:28:17.490  3714  4446 E Watchdog: !@Sync 11 [26_lip_17_28_17.489]
,07-26 17:28:18.069  3714  4542 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gSCM@ACs
,07-26 17:28:18.070  3714  4542 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gSCM@ACs
,07-26 17:28:18.083  3714  4542 I Telecom : com.android.server.telecom.PhoneAccountRegistrar: SimCallManager queried, returning: null: TSI.gSCM@ACs
,07-26 17:28:18.101 10487 10487 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-26 17:28:18.135 10487 10487 W Babel   : BAM#gBA: invalid account id: -1
,07-26 17:28:18.136 10487 10487 W Babel   : BAM#gBA: invalid account id: -1
07-26 17:28:18.137 10487 10487 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-26 17:28:18.155  3714  3909 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gSCM@AC0
07-26 17:28:18.155  3714  3909 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gSCM@AC0
,07-26 17:28:18.162  3714  3909 I Telecom : com.android.server.telecom.PhoneAccountRegistrar: SimCallManager queried, returning: null: TSI.gSCM@AC0
,07-26 17:28:19.127  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:19.128  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:19.194  4649  4649 D io_stats: !@   8,0 r 26224 2302820 w 5714 213380 d 753 74272 f 2276 2276 iot 12310 11327 th 471288 0 0 pt 0 inp 0 0 347.477
,07-26 17:28:19.626  3298  3766 D Netd    : Iface wlan0 link up
,07-26 17:28:19.628 10315 10315 I wpa_supplicant: nl80211: Received scan results (24 BSSes)
,07-26 17:28:19.629  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
,07-26 17:28:19.630  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
,07-26 17:28:19.634  3714  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@1d331f
,07-26 17:28:19.637  3714  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172847, SetElapsed=375903, nowELAPSED=347921
,07-26 17:28:20.910  5015  5059 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 4023 ms mFlush_time_threasold : 2000 mCurrentSize : 232
,07-26 17:28:22.160  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-26 17:28:22.160  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:23.556  9888  9951 I jxcore-log: 2017-07-26 15:28:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:28:23.556  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:28:23.556  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:28:23.556  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:28:23.556  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:28:23.556  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:28:23.556  9888  9951 I jxcore-log: 
,07-26 17:28:23.560  9888  9951 I jxcore-log: 2017-07-26 15:28:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:28:23.560  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:28:23.560  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:28:23.560  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:28:23.560  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:28:23.560  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:28:23.560  9888  9951 I jxcore-log: 
,07-26 17:28:24.201  4649  4649 D io_stats: !@   8,0 r 26224 2302820 w 5750 213672 d 755 74280 f 2278 2278 iot 12320 11334 th 471924 0 0 pt 0 inp 0 0 352.484
,07-26 17:28:25.072  3714  5765 D SSRM:f  : SIOP:: AP = 310, PST = 316 (W:14), CP = 261, CUR = -42, LCD = 57
,07-26 17:28:25.188  9067  9097 I PlayCommon: [776] com.google.android.play.a.g.e(932): Preparing logs for uploading
,07-26 17:28:25.194  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:25.194  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:25.220  9067  9097 W PlayCommon: [776] com.google.android.play.a.g.a(1239): No account for auth token provided
,07-26 17:28:25.221  9067  9097 I PlayCommon: [776] com.google.android.play.a.g.a(1035): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-26 17:28:25.226  9067  9097 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,07-26 17:28:25.234  9067  9097 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:28:25.234  9067  9097 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 17:28:25.238  3298  3769 D EnterpriseController: netId is 0
07-26 17:28:25.238  3298  3769 D Netd    : getNetworkForDns: using netid 503 for uid 10032
07-26 17:28:25.238  3298  3769 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-26 17:28:25.537  9067  9097 I PlayCommon: [776] com.google.android.play.a.g.a(1113): Successfully uploaded logs.
,07-26 17:28:28.253  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:28.253  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:28.256  3714  3909 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-26 17:28:29.207  4649  4649 D io_stats: !@   8,0 r 26225 2302824 w 5757 213768 d 759 74296 f 2280 2280 iot 12320 11339 th 471628 0 0 pt 0 inp 0 0 357.489
,07-26 17:28:31.277  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:31.278  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:33.596  9888  9951 I jxcore-log: 2017-07-26 15:28:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:28:33.596  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:28:33.596  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:28:33.596  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:28:33.596  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:28:33.596  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:28:33.596  9888  9951 I jxcore-log: 
,07-26 17:28:33.600  9888  9951 I jxcore-log: 2017-07-26 15:28:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:28:33.600  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:28:33.600  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:28:33.600  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:28:33.600  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:28:33.600  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:28:33.600  9888  9951 I jxcore-log: 
,07-26 17:28:34.213  4649  4649 D io_stats: !@   8,0 r 26225 2302824 w 5779 214016 d 763 74312 f 2285 2285 iot 12320 11346 th 472040 0 0 pt 0 inp 0 0 362.496
,07-26 17:28:34.311  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:34.311  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:35.099  3714  5765 D SSRM:f  : SIOP:: AP = 300, PST = 312 (W:14), CP = 257, CUR = -17, LCD = 57
,07-26 17:28:37.343  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:37.344  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:39.226  4649  4649 D io_stats: !@   8,0 r 26225 2302824 w 5794 214128 d 764 74316 f 2286 2286 iot 12320 11349 th 473428 0 0 pt 0 inp 0 0 367.508
,07-26 17:28:40.378  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:40.378  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:43.410  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:43.410  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:43.651  9888  9951 I jxcore-log: 2017-07-26 15:28:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:28:43.651  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:28:43.651  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:28:43.651  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:28:43.651  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:28:43.651  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:28:43.651  9888  9951 I jxcore-log: 
,07-26 17:28:43.658  9888  9951 I jxcore-log: 2017-07-26 15:28:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:28:43.658  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:28:43.658  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:28:43.658  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:28:43.658  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:28:43.658  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:28:43.658  9888  9951 I jxcore-log: 
,07-26 17:28:45.128  3714  5765 D SSRM:f  : SIOP:: AP = 290, PST = 311 (W:14), CP = 254, CUR = -6, LCD = 57
,07-26 17:28:45.417  3714  3714 D UsbMonitorService: readUsbState++
,07-26 17:28:45.419  3714  3714 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-26 17:28:45.420  3714  3714 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-26 17:28:45.420  3714  3714 D UsbMonitorService: Posting Message again
,07-26 17:28:46.433  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:46.434  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:47.492  3714  4446 E Watchdog: !@Sync 12 [26_lip_17_28_47.491]
,07-26 17:28:47.619  3714  3864 D SamsungAlarmManager: Expired : 4
,07-26 17:28:47.620  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T173657, SetElapsed=866043, nowELAPSED=375904
07-26 17:28:47.620  3714  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@95146be alarm=Alarm{8badb6e type 2 when 375903 android}
,07-26 17:28:47.624  3714  3929 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 64000: mInRange : true
,07-26 17:28:47.628 10315 10315 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-26 17:28:47.629 10315 10315 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-26 17:28:47.638  3714  3929 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T172951 - CU:1000/CP:3714
07-26 17:28:47.639  3714  3929 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172951, SetElapsed=439912, nowELAPSED=375923
,07-26 17:28:47.646 10315 10315 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-26 17:28:47.649  3714  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T172902 - CU:1000/CP:3714
,07-26 17:28:47.650  3714  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172902, SetElapsed=390918, nowELAPSED=375934
,07-26 17:28:49.454  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:49.455  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:50.962  5015  5059 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-26 17:28:50.962  5015  5059 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-26 17:28:50.962  5015  5059 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1, com.google.android.gms=2})  ]
,07-26 17:28:50.969  5015  5059 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 30059 ms mFlush_time_threasold : 2000 mCurrentSize : 283
,07-26 17:28:51.624  3298  3766 D Netd    : Iface wlan0 link up
,07-26 17:28:51.626 10315 10315 I wpa_supplicant: nl80211: Received scan results (25 BSSes)
07-26 17:28:51.628  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:28:51.628  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
,07-26 17:28:51.632  3714  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@81c429c
07-26 17:28:51.635  3714  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T172951, SetElapsed=439912, nowELAPSED=379920
,07-26 17:28:51.686  3714  4021 D WifiWatchdogStateMachine:  [|212]
,07-26 17:28:51.850  3714  4020 D WifiWatchdogStateMachine.QualitySocketHandler: response code: 204
,07-26 17:28:51.852  3714  4020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiWatchdogStateMachine$QualitySocketHandler.handleMessage:4711 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:154 android.os.HandlerThread.run:61 
,07-26 17:28:52.488  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:52.489  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:52.560  3714  3799 I PowerManagerService: [PWL] On : 0 (380844 ms ago)
07-26 17:28:52.560  3714  3799 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-26 17:28:53.688  9888  9951 I jxcore-log: 2017-07-26 15:28:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:28:53.688  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:28:53.688  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:28:53.688  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:28:53.688  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:28:53.688  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:28:53.688  9888  9951 I jxcore-log: 
,07-26 17:28:53.692  9888  9951 I jxcore-log: 2017-07-26 15:28:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:28:53.692  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:28:53.692  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:28:53.692  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:28:53.692  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:28:53.692  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:28:53.692  9888  9951 I jxcore-log: 
,07-26 17:28:54.242  4649  4649 D io_stats: !@   8,0 r 26225 2302824 w 5804 214248 d 765 74320 f 2288 2288 iot 12320 11352 th 473468 0 0 pt 0 inp 0 0 382.525
,07-26 17:28:55.155  3714  5765 D SSRM:f  : SIOP:: AP = 290, PST = 310 (W:14), CP = 251, LCD = 57
,07-26 17:28:55.522  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:55.522  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:57.706  3714  4018 D WifiWatchdogStateMachine:  [|216] []
,07-26 17:28:58.310  3714  4543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-26 17:28:58.311  3714  4543 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-26 17:28:58.312  3714  4543 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
,07-26 17:28:58.312  3714  3714 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-26 17:28:58.323  3714  3714 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-26 17:28:58.323  3714  3714 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-26 17:28:58.327  3714  3714 D GameManagerService: new battery level: 100
,07-26 17:28:58.333  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-26 17:28:58.334  4068  4068 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-26 17:28:58.340  4068  4068 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-26 17:28:58.351  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-26 17:28:58.352  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-26 17:28:58.375 10011 10011 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-26 17:28:58.376 10011 10068 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-26 17:28:58.386  4068  4068 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-26 17:28:58.557  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:28:58.557  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:28:59.248  4649  4649 D io_stats: !@   8,0 r 26225 2302824 w 5808 214300 d 766 74324 f 2290 2290 iot 12320 11354 th 473544 0 0 pt 0 inp 0 0 387.530
,07-26 17:29:00.000  3714  3864 D SamsungAlarmManager: Expired : 8
,07-26 17:29:00.001  3714  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{63d407a type 3 when 388284 android}
,07-26 17:29:00.010  3714  3714 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170726T173000 - CU:1000/CP:3714
,07-26 17:29:00.014  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-26 17:29:00.015  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#start
,07-26 17:29:00.016  4068  4068 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-26 17:29:00.044  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#end
07-26 17:29:00.045  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-26 17:29:00.048  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-26 17:29:00.067  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-26 17:29:00.071  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:29:00.077  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-26 17:29:00.083  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:29:00.098  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
07-26 17:29:00.100  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
07-26 17:29:00.101  4068  4068 V hong    : mid yDiff = 438
07-26 17:29:00.102  4068  4068 V hong    : mid yDiff = 438
,07-26 17:29:00.103  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
,07-26 17:29:00.103  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-26 17:29:00.110  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
07-26 17:29:00.112  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:29:00.127  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-26 17:29:00.129  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-26 17:29:00.144  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-26 17:29:00.148  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-26 17:29:00.153  5128  5128 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-26 17:29:00.155  5128  5128 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-26 17:29:00.159  5128  5128 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-26 17:29:00.164  5128  5128 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-26 17:29:00.165  5128  5128 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-26 17:29:00.167  5128  5128 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-26 17:29:00.168  5128  5128 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,07-26 17:29:00.169  5128  5128 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-26 17:29:00.174  5128  5128 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-26 17:29:00.175  5128  5128 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C5B5B7C29AF99E6CE15828BE2E6B30941E244B73EB4FE910232A39757019BF907EAE4C8C447EF372C842F70B88AB0BD32]}
,07-26 17:29:00.176  5128  5128 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-26 17:29:01.584  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:01.584  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:03.727  9888  9951 I jxcore-log: 2017-07-26 15:29:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:29:03.727  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:29:03.727  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:29:03.727  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:29:03.727  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:29:03.727  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:29:03.727  9888  9951 I jxcore-log: 
,07-26 17:29:03.732  9888  9951 I jxcore-log: 2017-07-26 15:29:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:29:03.732  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:29:03.732  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:29:03.732  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:29:03.732  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:29:03.732  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:29:03.732  9888  9951 I jxcore-log: 
,07-26 17:29:04.253  4649  4649 D io_stats: !@   8,0 r 26225 2302824 w 5816 214344 d 766 74324 f 2291 2291 iot 12320 11356 th 473396 0 0 pt 0 inp 0 0 392.536
,07-26 17:29:04.619  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:04.619  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:05.188  3714  5765 D SSRM:f  : SIOP:: AP = 290, PST = 307 (W:14), CP = 250, LCD = 57
,07-26 17:29:07.653  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:07.653  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:10.687  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:10.687  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:13.721  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:13.721  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:13.761  9888  9951 I jxcore-log: 2017-07-26 15:29:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:29:13.761  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:29:13.761  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:29:13.761  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:29:13.761  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:29:13.761  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:29:13.761  9888  9951 I jxcore-log: 
,07-26 17:29:13.764  9888  9951 I jxcore-log: 2017-07-26 15:29:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:29:13.764  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:29:13.764  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:29:13.764  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:29:13.764  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:29:13.764  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:29:13.764  9888  9951 I jxcore-log: 
,07-26 17:29:15.214  3714  5765 D SSRM:f  : SIOP:: AP = 290, PST = 303 (W:14), CP = 249, LCD = 57
,07-26 17:29:15.422  3714  3714 D UsbMonitorService: readUsbState++
,07-26 17:29:15.423  3714  3714 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-26 17:29:15.425  3714  3714 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-26 17:29:15.425  3714  3714 D UsbMonitorService: Posting Message again
,07-26 17:29:16.746  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:16.746  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:17.493  3714  4446 E Watchdog: !@Sync 13 [26_lip_17_29_17.493]
,07-26 17:29:19.778  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:19.778  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:19.859  9756  9785 V NativeCrypto: SSL shutdown failed: ssl=0x727bf53380: I/O error during system call, Software caused connection abort
,07-26 17:29:20.859  4779  7705 V NativeCrypto: SSL shutdown failed: ssl=0x7265b3d900: I/O error during system call, Software caused connection abort
,07-26 17:29:22.812  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:22.813  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:23.795  9888  9951 I jxcore-log: 2017-07-26 15:29:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:29:23.795  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:29:23.795  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:29:23.795  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:29:23.795  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:29:23.795  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:29:23.795  9888  9951 I jxcore-log: 
,07-26 17:29:23.798  9888  9951 I jxcore-log: 2017-07-26 15:29:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:29:23.798  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:29:23.798  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:29:23.798  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:29:23.798  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:29:23.798  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:29:23.798  9888  9951 I jxcore-log: 
,07-26 17:29:25.240  3714  5765 D SSRM:f  : SIOP:: AP = 290, PST = 302 (W:14), CP = 248, LCD = 57
,07-26 17:29:25.846  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:25.846  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:28.366  3714 10158 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-26 17:29:28.368  3714 10158 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-26 17:29:28.368  3714 10158 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-26 17:29:28.368  3714  3714 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-26 17:29:28.380  3714  3714 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-26 17:29:28.380  3714  3714 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-26 17:29:28.385  3714  3714 D GameManagerService: new battery level: 100
,07-26 17:29:28.390  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-26 17:29:28.391  4068  4068 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-26 17:29:28.398  4068  4068 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-26 17:29:28.409  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-26 17:29:28.409  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-26 17:29:28.415  4068  4068 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-26 17:29:28.431 10011 10011 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-26 17:29:28.432 10011 10068 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-26 17:29:28.868  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:28.869  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:29.278  4649  4649 D io_stats: !@   8,0 r 26225 2302824 w 5818 214352 d 766 74324 f 2292 2292 iot 12320 11357 th 473432 0 0 pt 0 inp 0 0 417.561
,07-26 17:29:31.897  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:31.897  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:33.852  9888  9951 I jxcore-log: 2017-07-26 15:29:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:29:33.852  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:29:33.852  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:29:33.852  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:29:33.852  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:29:33.852  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:29:33.852  9888  9951 I jxcore-log: 
,07-26 17:29:33.858  9888  9951 I jxcore-log: 2017-07-26 15:29:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:29:33.858  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:29:33.858  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:29:33.858  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:29:33.858  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:29:33.858  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:29:33.858  9888  9951 I jxcore-log: 
,07-26 17:29:34.931  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:34.931  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:35.270  3714  5765 D SSRM:f  : SIOP:: AP = 290, PST = 300 (W:14), CP = 248, LCD = 57
,07-26 17:29:37.980  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:37.980  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:39.288  4649  4649 D io_stats: !@   8,0 r 26225 2302824 w 5820 214368 d 766 74324 f 2293 2293 iot 12320 11358 th 473348 0 0 pt 0 inp 0 0 427.571
,07-26 17:29:41.007  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:41.007  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:43.888  9888  9951 I jxcore-log: 2017-07-26 15:29:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:29:43.888  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:29:43.888  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:29:43.888  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:29:43.888  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:29:43.888  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:29:43.888  9888  9951 I jxcore-log: 
,07-26 17:29:43.892  9888  9951 I jxcore-log: 2017-07-26 15:29:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:29:43.892  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:29:43.892  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:29:43.892  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:29:43.892  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:29:43.892  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:29:43.892  9888  9951 I jxcore-log: 
,07-26 17:29:44.028  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:44.028  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:45.299  3714  5765 D SSRM:f  : SIOP:: AP = 290, PST = 299 (W:14), CP = 247, LCD = 57
,07-26 17:29:45.426  3714  3714 D UsbMonitorService: readUsbState++
,07-26 17:29:45.428  3714  3714 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-26 17:29:45.429  3714  3714 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
,07-26 17:29:45.430  3714  3714 D UsbMonitorService: Posting Message again
,07-26 17:29:47.052  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:47.052  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:47.495  3714  4446 E Watchdog: !@Sync 14 [26_lip_17_29_47.494]
,07-26 17:29:50.086  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:50.087  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:51.039  5015  5059 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-26 17:29:51.039  5015  5059 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-26 17:29:51.039  5015  5059 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-26 17:29:51.049  5015  5059 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 8ms lastUpdatedAfter : 60080 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-26 17:29:51.628  3714  3864 D SamsungAlarmManager: Expired : 4
,07-26 17:29:51.629  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T173657, SetElapsed=866043, nowELAPSED=439913
07-26 17:29:51.629  3714  3864 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170726T173000, SetElapsed=448285, nowELAPSED=439914
,07-26 17:29:51.630  3714  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@b7f220f alarm=Alarm{24eea46 type 2 when 439912 android}
07-26 17:29:51.634  3714  3929 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
,07-26 17:29:51.637 10315 10315 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-26 17:29:51.638 10315 10315 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-26 17:29:51.643  3714  3929 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T173159 - CU:1000/CP:3714
,07-26 17:29:51.644  3714  3929 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T173159, SetElapsed=567920, nowELAPSED=439929
,07-26 17:29:51.649  3714  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170726T173006 - CU:1000/CP:3714
07-26 17:29:51.649 10315 10315 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-26 17:29:51.650  3714  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T173006, SetElapsed=454925, nowELAPSED=439934
,07-26 17:29:53.108  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:53.109  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-26 17:29:53.947  9888  9951 I jxcore-log: 2017-07-26 15:29:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:29:53.947  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:29:53.947  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:29:53.947  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:29:53.947  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:29:53.947  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:29:53.947  9888  9951 I jxcore-log: 
,07-26 17:29:53.954  9888  9951 I jxcore-log: 2017-07-26 15:29:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-26 17:29:53.954  9888  9951 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-26 17:29:53.954  9888  9951 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-26 17:29:53.954  9888  9951 I jxcore-log: emit@events.js:82:1
07-26 17:29:53.954  9888  9951 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-26 17:29:53.954  9888  9951 I jxcore-log: emit@events.js:82:1''
07-26 17:29:53.954  9888  9951 I jxcore-log: 
,07-26 17:29:54.303  4649  4649 D io_stats: !@   8,0 r 26225 2302824 w 5824 214456 d 767 74328 f 2295 2295 iot 12340 11360 th 473172 0 0 pt 0 inp 0 0 442.586
,07-26 17:29:55.326  3714  5765 D SSRM:f  : SIOP:: AP = 290, PST = 297 (W:14), CP = 247, LCD = 57
,07-26 17:29:55.650  3298  3766 D Netd    : Iface wlan0 link up
,07-26 17:29:55.653 10315 10315 I wpa_supplicant: nl80211: Received scan results (18 BSSes)
07-26 17:29:55.654  3714  3795 D Tethering: interfaceLinkStateChanged wlan0, true
07-26 17:29:55.654  3714  3795 D Tethering: interfaceStatusChanged wlan0, true
,07-26 17:29:55.659  3714  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3714 / listener:android.app.AlarmManager$ListenerWrapper@b744934
07-26 17:29:55.661  3714  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170726T173159, SetElapsed=567920, nowELAPSED=443946
,07-26 17:29:56.142  3714  3929 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-26 17:29:56.142  3714  3929 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40

```
