#### Test 50388019c82294c_thali08_samsung-SM-A300FU Logs


```
--------- beginning of system
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
D/AndroidRuntime( 5037): 
D/AndroidRuntime( 5037): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5037): CheckJNI is OFF
D/AndroidRuntime( 5037): readGMSProperty: start
D/AndroidRuntime( 5037): readGMSProperty: already setted!!
D/AndroidRuntime( 5037): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5037): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5037): readGMSProperty: end
D/AndroidRuntime( 5037): addProductProperty: start
E/AffinityControl( 5037): AffinityControl: registerfunction enter
D/AndroidRuntime( 5037): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
E/Zygote  ( 5049): MountEmulatedStorage()
E/Zygote  ( 5049): v2
I/libpersona( 5049): KNOX_SDCARD checking this for 10333
I/libpersona( 5049): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5049 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1461
I/SELinux ( 5049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/AndroidRuntime( 5037): Shutting down VM
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, iello
I/SELinux ( 5049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5049): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5049): TimaSignature is unavailable
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/ActivityThread( 5049): Added TimaKeyStore provider
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1019): Display changed displayId=0
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1461): updateVisibility : ActivityRecord{1d693e98 token=android.os.BinderProxy@3d2feeb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1461): onTrimMemory. Level: 20
I/WebViewFactory( 5049): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
W/art     ( 5037): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/LibraryLoader( 5049): Loading: webviewchromium
,I/LibraryLoader( 5049): Time to load native libraries: 43 ms (timestamps 9146-9189)
I/LibraryLoader( 5049): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5049): Binding Chromium to main looper Looper (main, tid 1) {2d9fd86d}
,I/LibraryLoader( 5049): Expected native library version number "",actual native library version number ""
,I/chromium( 5049): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5049): Initializing chromium process, renderers=0
,W/art     ( 5049): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 5049): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 5049): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 5049): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 5049): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/Adreno-EGL( 5049): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5049): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5049): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5049): Local Branch: 
I/Adreno-EGL( 5049): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5049): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5049):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5049): 844008610: getState() :  mService = null. Returning STATE_OFF
,W/chromium( 5049): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 5049): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 5049): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5049): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5049): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5049): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5049): CordovaWebView is running on device made by: samsung
,W/art     ( 5049): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5049): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{158e8687 u0 com.example.hello/.MainActivity t10}
,D/OpenGLRenderer( 5049): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,V/ActivityThread( 5049): updateVisibility : ActivityRecord{63cbe20 token=android.os.BinderProxy@25d76252 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/PhoneWindow( 5049): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5049): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 5049
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 5049): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5049): Initialized EGL, version 1.4
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 5049): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5049): Enabling debug mode 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1178): Icon Only
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PanelView( 1178): There is/are notification(s) 
,W/IInputConnectionWrapper( 5049): showStatusIcon on inactive InputConnection
,I/Timeline( 5049): Timeline: Activity_idle id: android.os.BinderProxy@25d76252 time:69618
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1019): Displayed Component not be shown by security: +646ms (total +721ms)
,W/ActivityManager( 1019): mDVFSHelper.release()
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{158e8687 u0 com.example.hello/.MainActivity t10} time:69634
,I/SurfaceFlinger(  258): id=11 Removed iello (7/9)
,I/SurfaceFlinger(  258): id=11 Removed iello (-2/9)
,I/SamsungIME( 1756): getCurrentCandidateView
,D/SamsungIME( 1756): Dismiss ExpandCandiate
,I/chromium( 5049): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 5049): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/SamsungIME( 1756): getDebugLevel  : 0x4f4c
,D/JsMessageQueue( 5049): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1756): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1756): KeybaordView init() : load resources
,I/SamsungIME( 1756): getCurrentKeyboard
,I/SamsungIME( 1756): getTextKeyboard
D/SamsungIME( 1756): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 5049): JniHelper::setJavaVM(0xb814f448), pthread_self() = -1200540920
,D/JX-Cordova( 5049): jxcore cordova android initializing
,W/jxcore-log( 5049): Initializing JXcore engine
,W/jxcore-log( 5049): JXcore engine is ready
,W/jxcore-log( 5049): Starting JXcore engine
,E/audit   ( 1781): type=1400 msg=audit(1447782162.384:203): avc:  denied  { ioctl } for  pid=5049 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1781):  SEPF_SM-A300FU_5.0.2_0027
,E/audit   ( 1781): type=1300 msg=audit(1447782162.384:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bef3ad58 items=0 ppid=322 ppcomm=main pid=5049 auid=4294967295 uid=10333 gid=10333 euid=10333 suid=10333 fsuid=10333 egid=10333 sgid=10333 fsgid=10333 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1781): type=1320 msg=audit(1447782162.384:203): 
,W/jxcore-log( 5049): Platform android,
W/jxcore-log( 5049): 
W/jxcore-log( 5049): Process ARCH arm
W/jxcore-log( 5049): 
,I/jxcore-log( 5049): JXcore Cordova bridge is ready!,
I/jxcore-log( 5049): 
W/jxcore-log( 5049): JXcore engine is started,
,I/chromium( 5049): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!,
I/chromium( 5049): 
,E/SMD     (  292): DCD OFF
,E/jxcore-log( 5049): >> samsung-SM-A300FU
E/jxcore-log( 5049): 
,I/jxcore-log( 5049): Total memory 1451114496
I/jxcore-log( 5049): 
,I/jxcore-log( 5049): Free memory 24526848
I/jxcore-log( 5049): 
I/jxcore-log( 5049): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5049): 
I/jxcore-log( 5049): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5049): 
,I/jxcore-log( 5049): userPath [ 'www' ]
I/jxcore-log( 5049): 
,I/jxcore-log( 5049): Size 540 960
I/jxcore-log( 5049): 
,I/jxcore-log( 5049): Screen Brightness 255
I/jxcore-log( 5049): 
,E/jxcore-log( 5049): Dummy Error Log.
E/jxcore-log( 5049): 
,D/SSRM:n  ( 1019): SIOP:: AP = 340
,I/jxcore-log( 5049): getBuffer is called!!!!
I/jxcore-log( 5049): 
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{17eedb32 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BluetoothAdapter( 5049): disable()
,E/BluetoothManagerService( 1019): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1019): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1019): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1019): mCursor = null
,D/WifiService( 1019): setWifiEnabled: false pid=5049, uid=10333
,D/SettingsProvider( 1019): name = wifi_on
,I/jxcore-log( 5049): ****TEST TOOK:  5058  ms ****
I/jxcore-log( 5049): 
,I/jxcore-log( 5049): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5049): 
,D/AndroidRuntime( 5104): ,
D/AndroidRuntime( 5104): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5104): CheckJNI is OFF,
D/AndroidRuntime( 5104): readGMSProperty: start
D/AndroidRuntime( 5104): readGMSProperty: already setted!!,
D/AndroidRuntime( 5104): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5104): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5104): readGMSProperty: end
D/AndroidRuntime( 5104): addProductProperty: start
,E/AffinityControl( 5104): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5104): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1019): START PACKAGE DELETE: observer{190519364},
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true,
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true,
,D/PackageManager( 1019): !@killApplicatoin: 10333, uninstall pkg
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 5049:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1019): Skipping PackageSetting{38d8f304 com.test.thalitest/10326} due to missing metadata
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{158e8687 u0 com.example.hello/.MainActivity t10}
,E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1019): Focus left window: 5049
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1019): Focused application released,
E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager( 1019): Force stopping com.example.hello appid=10333 user=0: pkg removed
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3621): Explicit concurrent mark sweep GC freed 2483(148KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 810us total 30.179ms
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 2966): Explicit concurrent mark sweep GC freed 21557(1358KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 918us total 46ms
,E/SamsungIME( 1756): mOCRHelper is null
,W/GeofencerStateMachine( 1622): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3400): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Nov 17 18:42:48 GMT+01:00 2015
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,I/KLMS-2.5.123: ( 3400): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1019): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=30, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 1 receivers.size=39
,I/splitIntent( 1019): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,I/KLMS-2.5.123: ( 3400): KLMSIntentService(): onCreate()
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3400): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 5118): MountEmulatedStorage()
E/Zygote  ( 5118): v2
I/libpersona( 5118): KNOX_SDCARD checking this for 10090
I/libpersona( 5118): KNOX_SDCARD not a persona
,I/SELinux ( 5118): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5118 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 5118): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5118): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 21018(1572KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 22MB/33MB, paused 2.615ms total 162.863ms
,I/art     ( 1019): WaitForGcToComplete blocked for 76.850ms for cause Explicit
I/KLMS-2.5.123: ( 3400): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,I/KLMS-2.5.123: ( 3400): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/Mms/FreeMessageStatusReceiver( 4066): onReceive, action : android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5118): TimaSignature is unavailable
,D/ActivityThread( 5118): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3400): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3400): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3400): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,E/Zygote  ( 5133): MountEmulatedStorage(),
,E/Zygote  ( 5133): v2
I/libpersona( 5133): KNOX_SDCARD checking this for 10145
I/libpersona( 5133): KNOX_SDCARD not a persona
I/SELinux ( 5133): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5133 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 5133): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5133): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/FilterInstaller( 4905): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
,W/ContextImpl( 4905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,D/TimaKeyStoreProvider( 5133): TimaSignature is unavailable
,D/ActivityThread( 5133): Added TimaKeyStore provider
,D/RCPManagerService( 1019): PackageReceiver onReceive()
,I/TactileAssist( 1019): enable value -1
I/TactileAssist( 1019): internal enable value -1
I/TactileAssist( 1019): intensity value -1
I/TactileAssist( 1019): saveAppList value true
,I/TactileAssist( 1019): List of disabled apps :
,I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/RegisteredServicesCache( 1422): empty dynamic service
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4066): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4066): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/FilterInstaller( 4905): FilterPackageService : ACTION_PACKAGE_REMOVED
,I/FilterInstaller( 4905): FilterPackageService : ACTION_REMOVED
,D/FilterUnInstaller( 4905): before removeFromFS
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 5118): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5118): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5118): MDMBridge.setEnterpriseBridge()
,E/SMD     (  292): DCD OFF
I/ActivityManager( 1019): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5150 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,E/Zygote  ( 5150): MountEmulatedStorage()
E/Zygote  ( 5150): v2
I/libpersona( 5150): KNOX_SDCARD checking this for 10095
I/libpersona( 5150): KNOX_SDCARD not a persona
,I/SELinux ( 5150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5150): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3400): KLMSIntentService(): listeningToPackageRemoved().END
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 5118): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ThemeInfoUtil( 5133): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 5133): isCurrentFestival = false
,D/elm:15121( 5118): ElmAgentService : onCreate()
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 5118): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 5118): MainReceiver.listeningToPackageRemoved()
,D/elm:15121( 5118): MDMBridge.getInstance()
D/elm:15121( 5118): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5118): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 5166): MountEmulatedStorage()
E/Zygote  ( 5166): v2
I/libpersona( 5166): KNOX_SDCARD checking this for 1000
I/libpersona( 5166): KNOX_SDCARD not a persona
,I/SELinux ( 5166): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5166 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5150): TimaSignature is unavailable
,D/ActivityThread( 5150): Added TimaKeyStore provider
I/SELinux ( 5166): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5166): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Compatibility( 4860): onReceive() it will make start service
,D/elm:15121( 5118): ElmAgentService : onDestroy().
,I/KLMS-2.5.123: ( 3400): KLMSIntentService(): onDestroy()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/TimaKeyStoreProvider( 5166): TimaSignature is unavailable
,D/ActivityThread( 5166): Added TimaKeyStore provider
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 7035(367KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 6.305ms total 230.289ms
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10333
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
,D/Compatibility( 4860): onHandleIntent()
,D/Compatibility( 4860): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10333, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 4860): found: 2
D/Compatibility( 4860): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 4860): skipping ResolveInfo{d2cd0ee com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 4860): considering ResolveInfo{9d1a98f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 4860): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 4860): enabling receiver ResolveInfo{388f41c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 4860): enabling receiver ResolveInfo{2558a825 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/PreloadFilterInstaller( 5150): uses FILTER_DB_VER_1
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10333
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/PackageManager( 1019): delete codoeFile: 
,E/SQLiteLog( 5150): (284) automatic index on titles(filter_id)
,D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10333, packageName = com.example.hello
,I/AASA_removePackage( 1019): UID=10333 Target=com.example.hello
W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/PackageManager( 1019): result of delete: 1{190519364}
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/TaskPersister( 1019): removeObsoleteFile: deleting file=10_task.xml
,D/AndroidRuntime( 5104): Shutting down VM
,D/Compatibility( 4860): enabling receiver ResolveInfo{1b990dfa com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/TapandpayWidget:TapandpayAppWidgetProvider( 4763): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 4763): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 4763): Clear T&P info.
,D/TapandpayWidget:TapandpayAppWidgetProvider( 4763): Widget is not attached.
,D/Compatibility( 4860): enabling receiver ResolveInfo{2bc94fab com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/Compatibility( 4860): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/SQLiteLog( 5150): (284) automatic index on titles(filter_id)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ContextImpl( 5166): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,I/UpdateIcingCorporaServi( 2966): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5186): MountEmulatedStorage()
E/Zygote  ( 5186): v2
I/libpersona( 5186): KNOX_SDCARD checking this for 10055
I/libpersona( 5186): KNOX_SDCARD not a persona
,I/SELinux ( 5186): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5186 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5186): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5186): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5197): MountEmulatedStorage()
,E/Zygote  ( 5197): v2
I/libpersona( 5197): KNOX_SDCARD checking this for 1000
I/libpersona( 5197): KNOX_SDCARD not a persona
I/SELinux ( 5197): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5197): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/TimaKeyStoreProvider( 5186): TimaSignature is unavailable
D/ActivityThread( 5186): Added TimaKeyStore provider
E/SELinux ( 5197): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5197 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
W/TextServicesManagerService( 1019): no available spell checker services found
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
I/PCWCLIENTTRACE_PushUtil( 4800): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4800): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4800): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4800): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/TimaKeyStoreProvider( 5197): TimaSignature is unavailable
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread( 5197): Added TimaKeyStore provider
I/ActivityManager( 1019): Killing 4458:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/PackageBroadcastService( 1927): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1927): Clearing selected account for com.example.hello
,E/Zygote  ( 5218): MountEmulatedStorage(),
I/libpersona( 5218): KNOX_SDCARD checking this for 10032
E/Zygote  ( 5218): v2
I/libpersona( 5218): KNOX_SDCARD not a persona
I/SELinux ( 5218): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5218): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1019): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5218 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 4193:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,E/SELinux ( 5218): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/UserAnalysis.PlaceProvider( 5186): PlaceProvider onCreate()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 5104): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,D/ChimeraCfgMgr( 1927): Loading module com.google.android.gms.games from APK com.google.android.gms,
,D/AcmsPackageEventListener( 5197): Received: android.intent.action.PACKAGE_REMOVED
,W/ContextImpl( 5197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
D/UserAnalysis.SecureDbManager( 5186): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 5186): SecurePlaceDbHelper() 
D/UserAnalysis( 5186): Create SecureDbHelper
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5218): TimaSignature is unavailable
W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ActivityThread( 5218): Added TimaKeyStore provider
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AcmsService( 5197): Enter Oncreate
D/AcmsServiceMonitor( 5197): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5197): creating AcmsCore
D/AcmsCore( 5197): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5197): AcmsCore
,I/LocationSettingsChecker( 1927): Removing dialog suppression flag for package com.example.hello
D/IntelligenceServiceApplication( 5186): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 5186): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,D/AcmsCore( 5197): init
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/AcmsCore( 5197): Looper handler is not null
D/AcmsCore( 5197): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5197): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5197): Incrementing - Counter value: 1
D/AcmsCore( 5197): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 5197): onStartCommand
D/AcmsService( 5197): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor( 5197): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5197): Incrementing - Counter value: 2
D/AcmsService( 5197): Incremented Counter Value : onStartCommand
,D/IntelligenceServiceApplication( 5186): no applications having user consent for prediction
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AcmsCertificateMngr( 5197): AcmsCertificateMngr
,D/AcmsRevocationMngr( 5197): AcmsRevocationMngr
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetection::stopService] Service stopped.
D/gH_CompatibleDatabase( 1927): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1927): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1927): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1927): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/ActivityThread( 5197): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/gH_CompatibleDatabase( 1927): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1927): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 1927): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ContextImpl( 3541): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,D/gH_CompatibleDatabase( 1927): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1927): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/gH_CompatibleDatabase( 1927): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/FilterUnInstaller( 4905): FilterUninstaller.java : removeFromDB()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/gH_CompatibleDatabase( 1927): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1927): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/gH_CompatibleDatabase( 1927): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
I/UpdateIcingCorporaServi( 2966): UpdateCorporaTask done [took 286 ms] updated apps [took 286 ms] 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,E/SQLiteLog( 1927): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
E/NetworkScheduler.SchedulerReceiver( 1633): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1633): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
,V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,D/UsbSettingsManager( 1019): clearDefaults: com.example.hello
I/CrashAnrDetector( 1019): onPackageRemoved : com.example.hello
,D/BluetoothAdapter( 5186): 894122887: getState() :  mService = null. Returning STATE_OFF
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4458/cgroup.procs: No such file or directory
V/PlaceDetection v1.0.19 ( 5186): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
W/libprocessgroup( 1019): failed to open /acct/uid_10035/pid_4193/cgroup.procs: No such file or directory
,E/SQLiteDatabase( 1927): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1927): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1927): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1927): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 1927): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 1927): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 1927): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 1927): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 1927): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 1927): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 1927): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 1927): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 1927): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 1927): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 1927): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1927): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1927): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1927): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1927): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1927): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 1927): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 1927): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1927): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1927): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1927): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 1927): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 1927): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 1927): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 1927): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 1927): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 1927): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 1927): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 1927): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 1927): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 1927): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 1927): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1927): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1927): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 1927): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1927): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1927): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 1927): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 1927): Opened phenotype.db in read-only mode
D/AcmsService( 5197): Inside handle Intent
D/AcmsService( 5197): App removed - package name: com.example.hello
D/AcmsCore( 5197): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5197): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5197): Incrementing - Counter value: 3
D/AcmsCore( 5197): Incremented Counter Value: postToAcmsCoreHandler =>5
D/AcmsService( 5197): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5197): Decrementing - Counter value: 2
D/FilterProvider( 5150): delete when PACKAGE_NAME : 2002 
D/FilterProvider( 5150): packageName : com.example.hello
E/SPPClientService( 5218): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5218): [PushClientApplication] Push log off : This is Ship build version
E/SQLiteLog( 3541): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 3541): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3541): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3541): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3541): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3541): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3541): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3541): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3541): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3541): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3541): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3541): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 3541): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
E/SQLiteDatabase( 3541): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3541): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3541): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3541): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3541): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3541): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3541): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3541): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3541): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3541): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 3541): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3541): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 3541): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 3541): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 3541): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
W/System.err( 3541): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3541): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3541): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3541): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 5186): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/SQLiteLog( 5186): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/SQLiteDatabase( 5186): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
E/SQLiteDatabase( 5186): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5186): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5186): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5186): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
E/SQLiteDatabase( 5186): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 5186): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5186): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5186): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5186): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5186): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5186): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5186): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5186): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 5186): It failed to get the database for dump_log
E/SQLiteLog( 5186): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5186): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
E/SQLiteDatabase( 5186): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5186): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5186): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5186): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
E/SQLiteDatabase( 5186): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 5186): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5186): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5186): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5186): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5186): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5186): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5186): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5186): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 5186): It failed to get the database for dump_log
E/Zygote  ( 5248): MountEmulatedStorage()
,E/Zygote  ( 5248): v2
I/libpersona( 5248): KNOX_SDCARD checking this for 1000
I/libpersona( 5248): KNOX_SDCARD not a persona
I/SELinux ( 5248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5248 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 5248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5248): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ContextImpl( 4905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:48 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:152 android.os.Handler.dispatchMessage:102 
I/SA      ( 4842): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4842): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10333 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
E/SQLiteLog( 5218): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
I/ActivityManager( 1019): Killing 4140:com.google.android.music:main/u0a108 (adj 15): empty #31
I/ActivityManager( 1019): Killing 3586:com.google.android.talk/u0a102 (adj 15): empty #31
D/TimaKeyStoreProvider( 5248): TimaSignature is unavailable
E/SQLiteDatabase( 5218): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 5218): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5218): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5218): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5218): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5218): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5218): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5218): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5218): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5218): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5218): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5218): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 5218): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 5218): 	at com.sec.spp.push.notisvc.registration.n.b(Unknown Source)
E/SQLiteDatabase( 5218): 	at com.sec.spp.push.notisvc.registration.n.a(Unknown Source)
E/SQLiteDatabase( 5218): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 5218): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 5218): 	at com.sec.spp.push.notisvc.registration.i.handleMessage(Unknown Source)
E/SQLiteDatabase( 5218): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5218): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5218): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5218): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5218): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5218): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5218): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/LNoti   ( 5218): [b] open fail. SQLException occured
D/ActivityThread( 5248): Added TimaKeyStore provider

```
