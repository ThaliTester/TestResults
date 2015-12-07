#### Test 50242285e707819_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
E/SMD     (  289): DCD OFF
,D/AndroidRuntime( 5279): 
D/AndroidRuntime( 5279): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5279): CheckJNI is OFF
D/AndroidRuntime( 5279): readGMSProperty: start
D/AndroidRuntime( 5279): readGMSProperty: already setted!!
D/AndroidRuntime( 5279): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5279): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5279): readGMSProperty: end
D/AndroidRuntime( 5279): addProductProperty: start
E/AffinityControl( 5279): AffinityControl: registerfunction enter
D/AndroidRuntime( 5279): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5292 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1479
D/AndroidRuntime( 5279): Shutting down VM
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, iello
E/Zygote  ( 5292): MountEmulatedStorage()
E/Zygote  ( 5292): v2
I/libpersona( 5292): KNOX_SDCARD checking this for 10345
I/libpersona( 5292): KNOX_SDCARD not a persona
I/SELinux ( 5292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5292): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
I/art     (  306): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 687us total 25.467ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.871ms
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 699us total 18.038ms
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/TimaKeyStoreProvider( 5292): TimaSignature is unavailable
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/ActivityThread( 5292): Added TimaKeyStore provider
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1019): Display changed displayId=0
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1479): updateVisibility : ActivityRecord{6244726 token=android.os.BinderProxy@b1f77f4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1479): onTrimMemory. Level: 20
I/WebViewFactory( 5292): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5292): Time to load native libraries: 1 ms (timestamps 6231-6232)
I/LibraryLoader( 5292): Expected native library version number "",actual native library version number ""
,W/art     ( 5279): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 5292): Binding Chromium to main looper Looper (main, tid 1) {e5f208f}
I/LibraryLoader( 5292): Expected native library version number "",actual native library version number ""
I/chromium( 5292): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5292): Initializing chromium process, singleProcess=true
,W/art     ( 5292): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 5292): ApplicationContext is null in ApplicationStatus
,W/chromium( 5292): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5292): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5292): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5292): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5292): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5292): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5292): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5292): Local Branch: 
I/Adreno-EGL( 5292): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5292): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5292):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5292): 980193544: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5292): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5292): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5292): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5292): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5292): CordovaWebView is running on device made by: samsung
,W/art     ( 5292): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5292): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5292): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{35ffe9b7 u0 com.example.hello/.MainActivity t19}
,W/chromium( 5292): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/PhoneWindow( 5292): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5292): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 5292,
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5292): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5292): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5292): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5292): Enabling debug mode 0
,V/ActivityThread( 5292): updateVisibility : ActivityRecord{214bb411 token=android.os.BinderProxy@2857209b {com.example.hello/com.example.hello.MainActivity}} show : true,
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 5292): showStatusIcon on inactive InputConnection
,I/Timeline( 5292): Timeline: Activity_idle id: android.os.BinderProxy@2857209b time:86788
,I/ActivityManager( 1019): Displayed Component not be shown by security: +648ms (total +766ms)
,W/ActivityManager( 1019): mDVFSHelper.release()
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{35ffe9b7 u0 com.example.hello/.MainActivity t19} time:86792
,I/SurfaceFlinger(  258): id=11 Removed iello (7/9)
,I/SurfaceFlinger(  258): id=11 Removed iello (-2/9)
,I/SamsungIME( 1754): getCurrentCandidateView
,W/BindingManager( 5292): Cannot call determinedVisibility() - never saw a connection for the pid: 5292,
,D/SamsungIME( 1754): Dismiss ExpandCandiate
,I/SamsungIME( 1754): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1754): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1754): KeybaordView init() : load resources
,I/chromium( 5292): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/SamsungIME( 1754): getCurrentKeyboard,
I/SamsungIME( 1754): getTextKeyboard
,D/SamsungIME( 1754): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5292): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5292): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5292): JniHelper::setJavaVM(0xb7d5a448), pthread_self() = -1205082720
,D/JX-Cordova( 5292): jxcore cordova android initializing
,W/jxcore-log( 5292): Initializing JXcore engine,
W/jxcore-log( 5292): JXcore engine is ready
,W/jxcore-log( 5292): Starting JXcore engine
,E/audit   ( 1818): type=1400 msg=audit(1449498975.827:203): avc:  denied  { ioctl } for  pid=5292 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1818):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1818): type=1300 msg=audit(1449498975.827:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=beacad58 items=0 ppid=306 ppcomm=main pid=5292 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1818): type=1320 msg=audit(1449498975.827:203): 
,W/jxcore-log( 5292): Platform android
W/jxcore-log( 5292): 
W/jxcore-log( 5292): Process ARCH arm
W/jxcore-log( 5292): 
,I/jxcore-log( 5292): JXcore Cordova bridge is ready!,
I/jxcore-log( 5292): 
W/jxcore-log( 5292): JXcore engine is started
,E/jxcore-log( 5292): >> samsung-SM-A300FU
E/jxcore-log( 5292): 
,I/jxcore-log( 5292): Total memory 1451114496
I/jxcore-log( 5292): 
,I/jxcore-log( 5292): Free memory 22962176
I/jxcore-log( 5292): 
I/jxcore-log( 5292): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5292): 
,I/jxcore-log( 5292): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5292): 
,I/jxcore-log( 5292): userPath [ 'www' ]
I/jxcore-log( 5292): 
,I/jxcore-log( 5292): Size 540 960
I/jxcore-log( 5292): 
,I/jxcore-log( 5292): Screen Brightness 160
I/jxcore-log( 5292): 
,E/jxcore-log( 5292): Dummy Error Log.
E/jxcore-log( 5292): 
,I/jxcore-log( 5292): getBuffer is called!!!!
I/jxcore-log( 5292): 
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,D/BluetoothAdapter( 5292): disable()
,E/BluetoothManagerService( 1019): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1019): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1019): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1019): mCursor = null
,D/WifiService( 1019): setWifiEnabled: false pid=5292, uid=10345
,D/SettingsProvider( 1019): name = wifi_on
,I/jxcore-log( 5292): ****TEST TOOK:  5058  ms ****
I/jxcore-log( 5292): 
,I/jxcore-log( 5292): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5292): 
,D/AndroidRuntime( 5345): 
D/AndroidRuntime( 5345): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5345): CheckJNI is OFF,
D/AndroidRuntime( 5345): readGMSProperty: start
D/AndroidRuntime( 5345): readGMSProperty: already setted!!,
D/AndroidRuntime( 5345): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5345): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5345): readGMSProperty: end
D/AndroidRuntime( 5345): addProductProperty: start
,E/AffinityControl( 5345): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5345): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PackageManager( 1019): START PACKAGE DELETE: observer{6231913}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER,
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:0
,D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
,D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1019): !@killApplicatoin: 10345, uninstall pkg
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 5292:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1019): Skipping PackageSetting{3c6d8c67 com.test.thalitest/10338} due to missing metadata
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{35ffe9b7 u0 com.example.hello/.MainActivity t19}
,E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1019): Focus left window: 5292
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1019): Focused application released
,E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3737): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 680us total 28.395ms
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1754): mOCRHelper is null
,I/art     ( 4121): Explicit concurrent mark sweep GC freed 22638(1677KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.763ms total 52.891ms
,I/KLMS-2.5.123: ( 3480): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 07 15:36:21 GMT+01:00 2015
,D/RegisteredServicesCache( 1441): empty dynamic service
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 62868(3MB) AllocSpace objects, 24(498KB) LOS objects, 33% free, 23MB/35MB, paused 2.280ms total 172.238ms
,I/art     ( 1019): WaitForGcToComplete blocked for 168.730ms for cause Explicit
,D/RCPManagerService( 1019): PackageReceiver onReceive()
,I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10345
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10345
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
D/TaskPersister( 1019): removeObsoleteFile: deleting file=19_task.xml
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 13132(734KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.649ms total 175.058ms
,I/art     ( 1019): WaitForGcToComplete blocked for 306.605ms for cause Explicit
,D/PackageManager( 1019): delete codoeFile: 
,D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
I/AASA_removePackage( 1019): UID=10345 Target=com.example.hello
,D/PackageManager( 1019): result of delete: 1{6231913}
,D/AndroidRuntime( 5345): Shutting down VM
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 4689(248KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.105ms total 138.532ms
,W/GeofencerStateMachine( 1656): Ignoring removeGeofence because network location is disabled.
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3480): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1019): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1019): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
,I/splitIntent( 1019): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3480): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3480): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3480): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3480): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3480): KLMSIntentService(): PACKAGE_REMOVED
,E/Zygote  ( 5358): MountEmulatedStorage()
E/Zygote  ( 5358): v2
I/libpersona( 5358): KNOX_SDCARD checking this for 10090
I/libpersona( 5358): KNOX_SDCARD not a persona
,I/SELinux ( 5358): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5358): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5358 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 5358): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3480): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3480): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/TimaKeyStoreProvider( 5358): TimaSignature is unavailable
,D/ActivityThread( 5358): Added TimaKeyStore provider
,D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1019): no available spell checker services found
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 5358): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5358): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5358): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3480): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15121( 5358): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3480): KLMSIntentService(): onDestroy()
,D/elm:15121( 5358): ElmAgentService : onCreate()
D/elm:15121( 5358): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 5358): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5358): MDMBridge.getInstance()
D/elm:15121( 5358): MDMBridge.getAllLicenseInfoFromSDK()
,W/art     ( 5345): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/elm:15121( 5358): MDMBridge.getAllLicenseInfoFromSDK()
,I/PCWCLIENTTRACE_PushUtil( 5062): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5062): sales region : global,
I/PCWCLIENTTRACE_PushUtil( 5062): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5062): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5135): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5135): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/PackagesMonitor( 4362): PackagesMonitor onReceive :com.example.hello
,D/elm:15121( 5358): ElmAgentService : onDestroy().
,E/SQLiteLog( 1526): (10) POSIX Error : 9 SQLite Error : 3850,
E/SQLiteLog( 1526): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/DatabaseUtils( 1526): Writing exception to parcel
E/DatabaseUtils( 1526): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 1526): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 1526): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DatabaseUtils( 1526): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 1526): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 1526): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DatabaseUtils( 1526): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DatabaseUtils( 1526): 	at com.sec.android.provider.logsprovider.LogsProvider.delete(LogsProvider.java:3550)
E/DatabaseUtils( 1526): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
E/DatabaseUtils( 1526): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
E/DatabaseUtils( 1526): 	at android.os.Binder.execTransact(Binder.java:461)
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/AndroidRuntime( 1641): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 1641): Process: android.process.acore, PID: 1641
E/AndroidRuntime( 1641): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1641): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 1641): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 1641): 	at android.content.ContentProviderProxy.delete(ContentProviderNative.java:543)
E/AndroidRuntime( 1641): 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
E/AndroidRuntime( 1641): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:476)
E/AndroidRuntime( 1641): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime( 1641): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
E/AndroidRuntime( 1641): 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
E/AndroidRuntime( 1641): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 1641): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 1641): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1641): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 1641): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname android.process.acore
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/Process ( 1641): Sending signal. PID: 1641 SIG: 9
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1019): clearDefaults: com.example.hello
I/CrashAnrDetector( 1019): onPackageRemoved : com.example.hello
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.,FileNotFoundException: /data/system/dropbox/drop159.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1019): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1019): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1019): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1019): 	... 5 more
W/FileUtils( 4362): Failed to chmod(/data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,D/Mms/FreeMessageStatusReceiver( 4223): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1019): enable value -1,
I/TactileAssist( 1019): internal enable value -1
I/TactileAssist( 1019): intensity value -1
I/TactileAssist( 1019): saveAppList value true
,I/TactileAssist( 1019): List of disabled apps :
D/Mms/FreeMessageReceiverService( 4223): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4223): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/ActivityManager( 1019): Killing 4296:com.google.android.music:main/u0a108 (adj 15): empty #31

```
