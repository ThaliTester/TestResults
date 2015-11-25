#### Test 503880194bce128_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SQLiteLog( 1675): (10) POSIX Error : 11 SQLite Error : 3850
E/SMD     (  290): DCD OFF
I/ServiceManager(  317): Waiting for service AtCmdFwd...
W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,--------- beginning of system
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/AndroidRuntime( 5262): 
D/AndroidRuntime( 5262): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5262): CheckJNI is OFF
D/AndroidRuntime( 5262): readGMSProperty: start
D/AndroidRuntime( 5262): readGMSProperty: already setted!!
D/AndroidRuntime( 5262): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5262): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5262): readGMSProperty: end
D/AndroidRuntime( 5262): addProductProperty: start
E/AffinityControl( 5262): AffinityControl: registerfunction enter
D/AndroidRuntime( 5262): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5274): MountEmulatedStorage()
E/Zygote  ( 5274): v2
I/libpersona( 5274): KNOX_SDCARD checking this for 10345
I/libpersona( 5274): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5274 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1016): Focused application set to: xxxx
I/SELinux ( 5274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/InputDispatcher( 1016): Focus left window: 1474
D/AndroidRuntime( 5262): Shutting down VM
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, iello
I/SELinux ( 5274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5274): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5274): TimaSignature is unavailable
D/ActivityThread( 5274): Added TimaKeyStore provider
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1016): Display changed displayId=0
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1474): updateVisibility : ActivityRecord{fae2fa0 token=android.os.BinderProxy@a30cefe {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1474): onTrimMemory. Level: 20
I/WebViewFactory( 5274): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5274): Time to load native libraries: 1 ms (timestamps 4337-4338)
I/LibraryLoader( 5274): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5274): Binding Chromium to main looper Looper (main, tid 1) {28967b41}
I/LibraryLoader( 5274): Expected native library version number "",actual native library version number ""
I/chromium( 5274): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5274): Initializing chromium process, singleProcess=true
W/art     ( 5274): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5274): ApplicationContext is null in ApplicationStatus
W/art     ( 5262): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/chromium( 5274): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5274): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5274): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5274): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5274): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5274): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5274): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5274): Local Branch: 
I/Adreno-EGL( 5274): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5274): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5274):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5274): 990985586: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5274): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5274): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5274): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5274): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5274): CordovaWebView is running on device made by: samsung
,W/art     ( 5274): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5274): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1016): Activity pause timeout for ActivityRecord{1f5c347b u0 com.example.hello/.MainActivity t19}
,D/OpenGLRenderer( 5274): Render dirty regions requested: true
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,W/chromium( 5274): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5274): updateVisibility : ActivityRecord{fbdf5b3 token=android.os.BinderProxy@2fbc0ced {com.example.hello/com.example.hello.MainActivity}} show : true,
,D/PhoneWindow( 5274): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null,
D/PhoneWindow( 5274): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1016): Focus entered window: 5274
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5274): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5274): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5274): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5274): Enabling debug mode 0
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1787): getCurrentCandidateView
,W/IInputConnectionWrapper( 5274): showStatusIcon on inactive InputConnection
,I/Timeline( 5274): Timeline: Activity_idle id: android.os.BinderProxy@2fbc0ced time:84887
,D/SamsungIME( 1787): Dismiss ExpandCandiate
,I/ActivityManager( 1016): Displayed Component not be shown by security: +707ms (total +773ms)
,W/ActivityManager( 1016): mDVFSHelper.release()
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{1f5c347b u0 com.example.hello/.MainActivity t19} time:84951
,I/SurfaceFlinger(  259): id=11 Removed iello (7/9)
,I/SurfaceFlinger(  259): id=11 Removed iello (-2/9)
,I/SamsungIME( 1787): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1787): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1787): KeybaordView init() : load resources
,I/SamsungIME( 1787): getCurrentKeyboard
,I/SamsungIME( 1787): getTextKeyboard
,W/BindingManager( 5274): Cannot call determinedVisibility() - never saw a connection for the pid: 5274
,D/SamsungIME( 1787): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/chromium( 5274): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/SMD     (  290): DCD OFF
,D/JsMessageQueue( 5274): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5274): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5274): JniHelper::setJavaVM(0xb77d8448), pthread_self() = -1210903976
,D/JX-Cordova( 5274): jxcore cordova android initializing
,W/jxcore-log( 5274): Initializing JXcore engine
W/jxcore-log( 5274): JXcore engine is ready
,W/jxcore-log( 5274): Starting JXcore engine
,E/audit   ( 1786): type=1400 msg=audit(1448461032.965:203): avc:  denied  { ioctl } for  pid=5274 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1786):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1786): type=1300 msg=audit(1448461032.965:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bed2cd58 items=0 ppid=308 ppcomm=main pid=5274 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1786): type=1320 msg=audit(1448461032.965:203): 
,W/jxcore-log( 5274): Platform android
W/jxcore-log( 5274): 
W/jxcore-log( 5274): Process ARCH arm
W/jxcore-log( 5274): 
,I/jxcore-log( 5274): JXcore Cordova bridge is ready!
I/jxcore-log( 5274): 
,W/jxcore-log( 5274): JXcore engine is started
,E/jxcore-log( 5274): >> samsung-SM-A300FU
E/jxcore-log( 5274): 
,I/jxcore-log( 5274): Total memory 1451114496
I/jxcore-log( 5274): 
,I/jxcore-log( 5274): Free memory 27127808
I/jxcore-log( 5274): 
,I/jxcore-log( 5274): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5274): 
I/jxcore-log( 5274): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5274): 
,I/jxcore-log( 5274): userPath [ 'www' ]
I/jxcore-log( 5274): 
,I/jxcore-log( 5274): Size 540 960
I/jxcore-log( 5274): 
,I/jxcore-log( 5274): Screen Brightness 160
I/jxcore-log( 5274): 
,E/jxcore-log( 5274): Dummy Error Log.
E/jxcore-log( 5274): 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,I/jxcore-log( 5274): getBuffer is called!!!!
I/jxcore-log( 5274): 
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BluetoothAdapter( 5274): disable()
,E/BluetoothManagerService( 1016): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1016): mCursor = null
,D/WifiService( 1016): setWifiEnabled: false pid=5274, uid=10345
,D/SettingsProvider( 1016): name = wifi_on
,I/jxcore-log( 5274): ****TEST TOOK:  5062  ms ****
I/jxcore-log( 5274): 
,I/jxcore-log( 5274): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5274): 
,D/SSRM:n  ( 1016): SIOP:: AP = 320,
,D/AndroidRuntime( 5324): ,
D/AndroidRuntime( 5324): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5324): CheckJNI is OFF,
D/AndroidRuntime( 5324): readGMSProperty: start
D/AndroidRuntime( 5324): readGMSProperty: already setted!!
D/AndroidRuntime( 5324): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5324): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5324): readGMSProperty: end,
D/AndroidRuntime( 5324): addProductProperty: start
,E/SMD     (  290): DCD OFF,
,E/AffinityControl( 5324): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5324): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1016): START PACKAGE DELETE: observer{1069256205}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER,
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1016): deletePackage- pkg:com.example.hello, edmuserId:0,
D/PackageManagerService( 1016): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1016): !@killApplicatoin: 10345, uninstall pkg,
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1016): Killing 5274:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1016): Skipping PackageSetting{ce64c59 com.test.thalitest/10338} due to missing metadata
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{1f5c347b u0 com.example.hello/.MainActivity t19}
,E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1016): Focus left window: 5274
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1016): Focused application released
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager( 1016): Force stopping com.example.hello appid=10345 user=0: pkg removed
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3710): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 675us total 32.971ms
,I/art     ( 4124): Explicit concurrent mark sweep GC freed 9971(666KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 1.107ms total 40.892ms
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1787): mOCRHelper is null
,I/KLMS-2.5.123: ( 3449): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Nov 25 15:17:18 GMT+01:00 2015
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 66409(4MB) AllocSpace objects, 24(498KB) LOS objects, 33% free, 23MB/35MB, paused 2.341ms total 175.380ms
,I/art     ( 1016): WaitForGcToComplete blocked for 170.033ms for cause Explicit
,D/RegisteredServicesCache( 1436): empty dynamic service
,D/RCPManagerService( 1016): PackageReceiver onReceive()
,I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10345
,V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10345
D/TaskPersister( 1016): removeObsoleteFile: deleting file=19_task.xml
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 11230(594KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.005ms total 153.421ms
,I/art     ( 1016): WaitForGcToComplete blocked for 282.400ms for cause Explicit
,D/PackageManager( 1016): delete codoeFile: 
,D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
I/AASA_removePackage( 1016): UID=10345 Target=com.example.hello
,D/PackageManager( 1016): result of delete: 1{1069256205}
,D/AndroidRuntime( 5324): Shutting down VM
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 6533(385KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.072ms total 141.624ms
,W/GeofencerStateMachine( 1622): Ignoring removeGeofence because network location is disabled.
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3449): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1016): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27,
I/splitIntent( 1016): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1016): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
,I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3449): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3449): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3449): KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,I/KLMS-2.5.123: ( 3449): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3449): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3449): KLMSIntentService(): listeningToPackageRemoved().START
,E/Zygote  ( 5339): MountEmulatedStorage(),
E/Zygote  ( 5339): v2
I/libpersona( 5339): KNOX_SDCARD checking this for 10090
,I/libpersona( 5339): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5339 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
I/SELinux ( 5339): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 3449): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
I/SELinux ( 5339): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5339): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5339): TimaSignature is unavailable
,D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
,D/ActivityThread( 5339): Added TimaKeyStore provider
W/TextServicesManagerService( 1016): no available spell checker services found
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/art     ( 5324): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/KLMS-2.5.123: ( 3449): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3449): KLMSIntentService(): onDestroy()
,D/elm:15121( 5339): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5339): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5339): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 5339): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/PCWCLIENTTRACE_PushUtil( 5022): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5022): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5022): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5022): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 5339): ElmAgentService : onCreate()
,D/elm:15121( 5339): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 5339): MainReceiver.listeningToPackageRemoved()
,D/elm:15121( 5339): MDMBridge.getInstance()
D/elm:15121( 5339): MDMBridge.getAllLicenseInfoFromSDK()
,I/SA      ( 5163): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5163): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,D/elm:15121( 5339): MDMBridge.getAllLicenseInfoFromSDK()
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/PackagesMonitor( 4327): PackagesMonitor onReceive :com.example.hello
,D/elm:15121( 5339): ElmAgentService : onDestroy().
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75),
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
D/Mms/FreeMessageStatusReceiver( 4185): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/TactileAssist( 1016): enable value -1
I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
D/UsbSettingsManager( 1016): clearDefaults: com.example.hello
I/CrashAnrDetector( 1016): onPackageRemoved : com.example.hello
,D/Mms/FreeMessageReceiverService( 4185): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4185): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1016): List of disabled apps :
,I/ActivityManager( 1016): Killing 4257:com.google.android.music:main/u0a108 (adj 15): empty #31
,D/Compatibility( 5072): onReceive() it will make start service
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5072): onHandleIntent()
,D/Compatibility( 5072): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10345, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5072): found: 2
I/libpersona( 5361): KNOX_SDCARD checking this for 10055
D/Compatibility( 5072): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,I/libpersona( 5361): KNOX_SDCARD not a persona
D/Compatibility( 5072): skipping ResolveInfo{10e8a7d com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5072): considering ResolveInfo{3b113d72 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5072): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5072): enabling receiver ResolveInfo{1f3c15c3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5072): enabling receiver ResolveInfo{3308de40 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/Zygote  ( 5361): MountEmulatedStorage()
E/Zygote  ( 5361): v2
,I/SELinux ( 5361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/Compatibility( 5072): enabling receiver ResolveInfo{13fe5179 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/SELinux ( 5361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5361): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5361 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,D/Compatibility( 5072): enabling receiver ResolveInfo{3cb1bebe com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5072): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/TimaKeyStoreProvider( 5361): TimaSignature is unavailable
,D/ActivityThread( 5361): Added TimaKeyStore provider

```
