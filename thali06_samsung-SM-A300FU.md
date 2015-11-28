#### Test 50388019809f971_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
W/Atfwd_Sendcmd(  342): AtCmdFwd service not published, waiting... retryCnt : 5
,D/AndroidRuntime( 6047): 
D/AndroidRuntime( 6047): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6047): CheckJNI is OFF
D/AndroidRuntime( 6047): readGMSProperty: start
D/AndroidRuntime( 6047): readGMSProperty: already setted!!
D/AndroidRuntime( 6047): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6047): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6047): readGMSProperty: end
D/AndroidRuntime( 6047): addProductProperty: start
E/AffinityControl( 6047): AffinityControl: registerfunction enter
D/AndroidRuntime( 6047): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
E/Zygote  ( 6059): MountEmulatedStorage()
E/Zygote  ( 6059): v2
I/libpersona( 6059): KNOX_SDCARD checking this for 10345
I/libpersona( 6059): KNOX_SDCARD not a persona
I/SELinux ( 6059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6059 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1480
I/SELinux ( 6059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/AndroidRuntime( 6047): Shutting down VM
E/SELinux ( 6059): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, iello
D/TimaKeyStoreProvider( 6059): TimaSignature is unavailable
D/ActivityThread( 6059): Added TimaKeyStore provider
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1017): Display changed displayId=0
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
D/Launcher( 1480): onTrimMemory. Level: 20
V/ActivityThread( 1480): updateVisibility : ActivityRecord{d965b43 token=android.os.BinderProxy@cc17aa0 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/WebViewFactory( 6059): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6059): Time to load native libraries: 2 ms (timestamps 4435-4437)
I/LibraryLoader( 6059): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6059): Binding Chromium to main looper Looper (main, tid 1) {2088223a}
I/LibraryLoader( 6059): Expected native library version number "",actual native library version number ""
I/chromium( 6059): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6059): Initializing chromium process, singleProcess=true
W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6059): ApplicationContext is null in ApplicationStatus
W/art     ( 6047): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/chromium( 6059): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6059): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6059): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6059): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6059): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6059): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6059): Local Branch: 
I/Adreno-EGL( 6059): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6059): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6059):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6059): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6059): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6059): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6059): CordovaWebView is running on device made by: samsung
W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6059): Render dirty regions requested: true
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{3a86e371 u0 com.example.hello/.MainActivity t19}
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
W/chromium( 6059): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/PhoneWindow( 6059): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6059): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1017): Focus entered window: 6059
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6059): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6059): Initialized EGL, version 1.4
D/OpenGLRenderer( 6059): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6059): Enabling debug mode 0
V/ActivityThread( 6059): updateVisibility : ActivityRecord{b3937b7 token=android.os.BinderProxy@22535651 {com.example.hello/com.example.hello.MainActivity}} show : true
D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 6059): showStatusIcon on inactive InputConnection
I/Timeline( 6059): Timeline: Activity_idle id: android.os.BinderProxy@22535651 time:84992
I/ActivityManager( 1017): Displayed Component not be shown by security: +654ms (total +724ms)
W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{3a86e371 u0 com.example.hello/.MainActivity t19} time:84998
I/SurfaceFlinger(  259): id=12 Removed iello (7/9)
I/SurfaceFlinger(  259): id=12 Removed iello (-2/9)
I/SamsungIME( 1848): getCurrentCandidateView
D/SamsungIME( 1848): Dismiss ExpandCandiate
E/SMD     (  290): DCD OFF
I/SamsungIME( 1848): getDebugLevel  : 0x4f4c
I/SamsungIME( 1848): getDebugLevel  : 0x4f4c
I/SamsungIME( 1848): KeybaordView init() : load resources
I/SamsungIME( 1848): getCurrentKeyboard
I/SamsungIME( 1848): getTextKeyboard
W/BindingManager( 6059): Cannot call determinedVisibility() - never saw a connection for the pid: 6059
D/SamsungIME( 1848): [SwiftkeyWrapper] currentLangauge : 1701729619
I/chromium( 6059): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 6059): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 6059): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/jxcore_app_log( 6059): JniHelper::setJavaVM(0xb7a71448), pthread_self() = -1208184352
D/JX-Cordova( 6059): jxcore cordova android initializing
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/jxcore-log( 6059): Initializing JXcore engine
W/jxcore-log( 6059): JXcore engine is ready
W/jxcore-log( 6059): Starting JXcore engine
E/audit   ( 1866): type=1400 msg=audit(1448709370.503:205): avc:  denied  { ioctl } for  pid=6059 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1866):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1866): type=1300 msg=audit(1448709370.503:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bebedd58 items=0 ppid=324 ppcomm=main pid=6059 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1866): type=1320 msg=audit(1448709370.503:205): 
W/jxcore-log( 6059): Platform android
W/jxcore-log( 6059): 
W/jxcore-log( 6059): Process ARCH arm
W/jxcore-log( 6059): 
I/jxcore-log( 6059): JXcore Cordova bridge is ready!
I/jxcore-log( 6059): 
W/jxcore-log( 6059): JXcore engine is started
E/jxcore-log( 6059): >> samsung-SM-A300FU
E/jxcore-log( 6059): 
I/jxcore-log( 6059): Total memory 1451114496
I/jxcore-log( 6059): 
I/jxcore-log( 6059): Free memory 23678976
I/jxcore-log( 6059): 
I/jxcore-log( 6059): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6059): 
I/jxcore-log( 6059): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6059): 
I/jxcore-log( 6059): userPath [ 'www' ]
I/jxcore-log( 6059): 
I/jxcore-log( 6059): Size 540 960
I/jxcore-log( 6059): 
I/jxcore-log( 6059): Screen Brightness 160
I/jxcore-log( 6059): 
E/jxcore-log( 6059): Dummy Error Log.
E/jxcore-log( 6059): 
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/jxcore-log( 6059): getBuffer is called!!!!
I/jxcore-log( 6059): 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 330
,V/AlarmManager( 1017): waitForAlarm result :4
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6110): MountEmulatedStorage()
E/Zygote  ( 6110): v2
I/libpersona( 6110): KNOX_SDCARD checking this for 10071
I/libpersona( 6110): KNOX_SDCARD not a persona
,I/SELinux ( 6110): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6110 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,I/SELinux ( 6110): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/SELinux ( 6110): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6119): MountEmulatedStorage(),
E/Zygote  ( 6119): v2
I/libpersona( 6119): KNOX_SDCARD checking this for 10099
I/libpersona( 6119): KNOX_SDCARD not a persona
,I/SELinux ( 6119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6119 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6119): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6110): TimaSignature is unavailable
,D/ActivityThread( 6110): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6119): TimaSignature is unavailable
,D/ActivityThread( 6119): Added TimaKeyStore provider
,W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/Gmail   ( 6119): getAccountsCursor
W/GAV2    ( 6119): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/Gmail   ( 6119): Observing account changes for notifications
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/Gmail   ( 6119): Sync started for account: account:61035162
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Gmail   ( 6119): Error finding the version of the Email provider.....
E/Gmail   ( 6119): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6119): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 6119): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6119): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6119): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6119): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6119): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 6119): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6119): We do not support migrating this version of the Email provider.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/SQLiteLog( 6119): (283) recovered 31 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 6119): getAccountsCursor
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/GAV2    ( 6110): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6110): Created application version: 3.6.9 (30609)
,E/File    ( 6119): fail readDirectory() errno=2
,I/Gmail   ( 6119): notifyAccountChanged
,I/Gmail   ( 6119): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6119): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6119): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6119): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6110): Starting books sync for 61035162, extras: ade
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 44640(2MB) AllocSpace objects, 19(308KB) LOS objects, 33% free, 23MB/35MB, paused 2.384ms total 158.359ms,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 6119): notifyAccountChanged
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 6110): (284) automatic index on view_volumes(volume_id)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BooksConfig( 6110): GmsCore Version = 7.8.99 (2134222-434)
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 6119): getAccountsCursor
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6119): getAccountsCursor
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1663): Explicit concurrent mark sweep GC freed 13080(790KB) AllocSpace objects, 3(60KB) LOS objects, 39% free, 7MB/12MB, paused 1.072ms total 41.370ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 6119): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5350, normalSync: true
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only,
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true,
W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 6119): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6119): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/JNIHelp ( 6119): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/BooksAccountManager( 6110): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6110): Soft error
E/BooksSync( 6110): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6110): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6110): Sync error
E/BooksSync( 6110): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6110): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6110): Finished books sync
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 65629, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1017): Killing 5026:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,W/ActivityThread( 6119): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6119): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16f7312d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6119): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
W/GLSActivity( 1663): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1663): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1663): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1663): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1663): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1663): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1663): 	at android.os.Binder.execTransact(Binder.java:461)
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_5026/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
,W/GLSActivity( 1663): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1663): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1663): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1663): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1663): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1663): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1663): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) ,
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/Gmail   ( 6119): notifyAccountChanged
,I/Gmail   ( 6119): getAccountsCursor
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/Gmail   ( 6119): notifyAccountChanged
,W/Gmail   ( 6119): Sync complete for account: account:61035162
,I/Gmail   ( 6119): getAccountsCursor
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 70950, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1017): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 155670, reason: Periodic
,I/ActivityManager( 1017): Killing 4365:com.google.android.music:main/u0a108 (adj 15): empty #31
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,W/libprocessgroup( 1017): failed to open /acct/uid_10108/pid_4365/cgroup.procs: No such file or directory
,D/BluetoothAdapter( 6059): disable(),
,D/SettingsProvider( 1017): name = bluetooth_on,
,D/BluetoothAdapterState( 2628): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2628): Setting state to 13
I/BluetoothAdapterState( 2628): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 2628): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2628): updateAdapterState state is 13
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2628): Autoconnection is available 
D/BluetoothAdapterService( 2628): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2628): terminating service from this receiver
,I/BluetoothPbapService( 2628): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/BluetoothSocket( 2628): close() in, this: android.bluetooth.BluetoothSocket@bc798fa, channel: 19, state: LISTENING
D/BluetoothSocket( 2628): close() this: android.bluetooth.BluetoothSocket@bc798fa, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b82b7a2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ff47eabmSocket: android.net.LocalSocket@3cf43908 impl:android.net.LocalSocketImpl@18ce8a1 fd:FileDescriptor[74]
D/BluetoothSocket( 2628): Closing mSocket: android.net.LocalSocket@3cf43908 impl:android.net.LocalSocketImpl@18ce8a1 fd:FileDescriptor[74]
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2628): onBluetoothDisable()
D/BluetoothAdapterProperties( 2628): mDiscovering is false
,D/SecContentProvider( 1017): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 2628): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1017): [BT Setting State] State =13
,D/BluetoothTile( 1177):  onBluetoothStateChange:
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: false pid=6059, uid=10345
,D/SettingsProvider( 1017): name = wifi_on
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,I/SamsungIME( 1848): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 13
,I/jxcore-log( 6059): ****TEST TOOK:  5079  ms ****
I/jxcore-log( 6059): 
,I/jxcore-log( 6059): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6059): 
,E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1383): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1383): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1383): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1383): Scan requested (ret=0) - scan timeout 30 seconds
V/BluetoothEventManager( 1305): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterProperties( 2628): Scan Mode:20
D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothSocket( 2628): close() in, this: android.bluetooth.BluetoothSocket@25664ac6, channel: 5, state: LISTENING
,D/BluetoothSocket( 2628): close() this: android.bluetooth.BluetoothSocket@25664ac6, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e7bc33, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@327a5a87mSocket: android.net.LocalSocket@1117ddb4 impl:android.net.LocalSocketImpl@39ee6ddd fd:FileDescriptor[76]
D/BluetoothSocket( 2628): Closing mSocket: android.net.LocalSocket@1117ddb4 impl:android.net.LocalSocketImpl@39ee6ddd fd:FileDescriptor[76]
,I/BtOppRfcommListener( 2628): stopping Accept Thread
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
D/STATUSBAR-QSTileView( 1177): onStateChanged: Bluetooth
D/BluetoothSocket( 2628): close() in, this: android.bluetooth.BluetoothSocket@25ec4d52, channel: 12, state: LISTENING
D/BluetoothSocket( 2628): close() this: android.bluetooth.BluetoothSocket@25ec4d52, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@144e7f25, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4981823mSocket: android.net.LocalSocket@1a2f2120 impl:android.net.LocalSocketImpl@e90ad9 fd:FileDescriptor[80]
D/BluetoothSocket( 2628): Closing mSocket: android.net.LocalSocket@1a2f2120 impl:android.net.LocalSocketImpl@e90ad9 fd:FileDescriptor[80],
E/BtOppRfcommListener( 2628): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 2628): BluetoothSocket listen thread finished
,V/BluetoothOppManager( 2628): cleanUp...
,D/BluetoothAdapterState( 2628): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 2628): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 2628): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/WifiNative-wlan0( 1017): do suspend true
,E/bt-btif ( 2628): cmd socket is not created
,W/ContextImpl( 1305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/bt-btm  ( 2628): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 2628): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
D/btif_config_util( 2628): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/BluetoothPbap( 1305): Proxy object disconnected
D/PbapServerProfile( 1305): Bluetooth service disconnected
,W/bt-l2cap( 2628): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2628): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2628): L2CAP - PSM: 0x001b not found for deregistration
,D/DockEventReceiver( 1305): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,V/BluetoothStatusReceiver( 1177): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1177): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6188): MountEmulatedStorage()
I/libpersona( 6188): KNOX_SDCARD checking this for 10055
E/Zygote  ( 6188): v2
I/libpersona( 6188): KNOX_SDCARD not a persona
I/SELinux ( 6188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6188): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6188 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6188): TimaSignature is unavailable
,D/ActivityThread( 6188): Added TimaKeyStore provider
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1663): Read error: ssl=0xb7f79b88: I/O error during system call, Connection timed out
,V/NativeCrypto( 1663): SSL shutdown failed: ssl=0xb7f79b88: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1017): updateNetworkInfo()
,E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/UserAnalysis.PlaceProvider( 6188): PlaceProvider onCreate()
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1017): Tagging socket 338 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,I/qtaguid ( 1017): Untagging socket 338
D/WifiP2pService( 1017): InactiveState{ what=131204 }
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
D/WifiP2pService( 1017): P2pEnabledState{ what=131204 }
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/WifiP2pService( 1017): sending p2p connection changed broadcast: FAILED
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiDisplayController( 1017): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiDisplayAdapter( 1017): onP2pDisconnected
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiScanningService( 1017): SCAN_AVAILABLE : 1
D/WifiScanningService( 1017): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1017): SCAN_AVAILABLE : 1
D/RttService( 1017): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
,D/UserAnalysis.SecureDbManager( 6188): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 6188): SecurePlaceDbHelper() 
D/UserAnalysis( 6188): Create SecureDbHelper
,D/IpRemoteDisplayController( 1017): disconnectWfdBridgeServer
,D/IpRemoteDisplayController( 1017): WfdBridgeServer is already null
,D/IntelligenceServiceApplication( 6188): onCreate()
,I/ActivityManager( 1017): Killing 5481:com.google.android.gms:car/u0a11 (adj 15): empty #31,
,E/SMD     (  290): DCD OFF,
D/IntelligenceServiceApplication( 6188): no applications having user consent for prediction
,D/AuthorizationBluetoothService( 1663): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/PlaceDetection v1.0.19 ( 6188): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 6188): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 1717): Starting #8
I/Hs20UtilService( 1717): Message received 5007
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,D/WifiP2pService( 1017): sending p2p connection changed broadcast: DISCONNECTED
D/WifiP2pService( 1017): P2pDisablingState
D/WifiP2pService( 1017): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1017): p2p socket connection lost
D/WifiP2pService( 1017): P2pDisabledState
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1305): MountReceiver.onReceive - Set preference state off
E/WifiNative-wlan0( 1017): do suspend true
E/WifiStateMachine( 1017): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,V/NearbySettings( 1305): MountReceiver.mPrefHandler - 7002
D/WifiDisplayController( 1017): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
D/WifiDisplayController( 1017): disconnect
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
D/WifiDisplayController( 1017): updateConnection
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/TelephonyNetworkFactory( 1456): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/TelephonyNetworkFactory( 1456): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiP2pService( 1017): P2pDisabledState{ what=143375 }
W/bt-l2cap( 2628): L2CAP - PSM: 0x0019 not found for deregistration
D/WifiP2pService( 1017): DefaultState{ what=143375 }
W/bt-l2cap( 2628): L2CAP - PSM: 0x0017 not found for deregistration
D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
W/bt-l2cap( 2628): L2CAP - PSM: 0x001b not found for deregistration
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
W/bt-l2cap( 2628): L2CAP - PSM: 0x0019 not found for deregistration
D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/bt-l2cap( 2628): L2CAP - PSM: 0x0017 not found for deregistration
D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
W/bt-l2cap( 2628): L2CAP - PSM: 0x001b not found for deregistration
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
W/bt-l2cap( 2628): L2CAP - PSM: 0x0019 not found for deregistration
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/bt-l2cap( 2628): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2628): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2628): ag scb idx 1 not allocated
W/bt-btif ( 2628): ag scb idx 2 not allocated
E/bt-btif ( 2628): BTA AG is already disabled, ignoring ...
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
I/bt_userial_mct( 2628): exiting userial_read_thread
D/bt_userial_mct( 2628): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2628): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2628): hw_epilog_process
D/bt_userial_mct( 2628): userial_close
I/bt_vendor( 2628): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/WifiDisplayController( 1017): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1017): onP2pDisconnected
D/IpRemoteDisplayController( 1017): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1017): WfdBridgeServer is already null
,I/wpa_supplicant( 1383): p2p0: State: DISCONNECTED -> DISCONNECTED
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/AllShareCastTile( 1177): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
D/AllShareCastTile( 1177): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
V/NetworkStats( 1017): updateIfacesLocked()
D/Tethering( 1017): MasterInitialState.processMessage what=3
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---,
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,W/libprocessgroup( 1017): failed to open /acct/uid_10011/pid_5481/cgroup.procs: No such file or directory
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
E/ConnectivityService( 1017): updateNetworkInfo()
E/ConnectivityService( 1017): updateNetworkInfo()
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NetworkStats( 1017): performPollLocked() took 12ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(0)
D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
,D/HotspotTile( 1177): onReceive : 0, 0
,D/WifiCredService( 1305): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1305): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1305): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6213): MountEmulatedStorage()
,E/Zygote  ( 6213): v2
I/libpersona( 6213): KNOX_SDCARD checking this for 10064,
I/libpersona( 6213): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6213 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6213): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6213): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6213): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1383): Blacklist: Clear (all) 
,D/AndroidRuntime( 6197): ,
D/AndroidRuntime( 6197): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6197): CheckJNI is OFF
,D/AndroidRuntime( 6197): readGMSProperty: start
D/AndroidRuntime( 6197): readGMSProperty: already setted!!
D/AndroidRuntime( 6197): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6197): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6197): readGMSProperty: end
D/AndroidRuntime( 6197): addProductProperty: start
,D/TimaKeyStoreProvider( 6213): TimaSignature is unavailable
,D/ActivityThread( 6213): Added TimaKeyStore provider
,V/AlarmManager( 1017): waitForAlarm result :4
,W/ResourcesManager( 6213): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.,
,I/wpa_supplicant( 1383): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1017): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged p2p0, false
D/Tethering( 1017): interfaceStatusChanged p2p0, false
,D/FileShare-Client( 6213): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 6213): ClientBroadcastReceiver.onReceive - disconnected,
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/wpa_supplicant( 1383): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
V/NetworkStats( 1017): performPollLocked(flags=0x1)
I/wpa_supplicant( 1383): wlan0: State: COMPLETED -> DISCONNECTED
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
I/wpa_supplicant( 1383): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/HotspotTile( 1177): updateTetherState():false, false
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
V/NetworkStats( 1017): performPollLocked() took 3ms
I/wpa_supplicant( 1383): wlan0: State: DISCONNECTED -> DISCONNECTED
D/Tethering( 1017): InitialState.processMessage what=4
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
E/Tethering( 1017): No numeric data
D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1017): clearTetheredNotification()
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileShare-Client( 6213): Outbound.stopDelayTimer - 
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3,
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,E/Zygote  ( 6247): MountEmulatedStorage()
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
E/Zygote  ( 6247): v2
,I/libpersona( 6247): KNOX_SDCARD checking this for 10065
I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6247 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 6247): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Killing 4232:com.sec.spp.push/u0a32 (adj 15): empty #31
I/SELinux ( 6247): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,I/SELinux ( 6247): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6247): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/bt_vendor( 2628): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2628): bluetooth satus is on
I/bt_vendor( 2628): bt-vendor : resetting BT status
I/bt_vendor( 2628): Starting hciattach daemon
I/bt_vendor( 2628): try to set false
,I/bt_vendor( 2628): Starting hciattach daemon
I/bt_vendor( 2628): try to set false
I/bt_vendor( 2628): cleanup
I/GKI_LINUX( 2628): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2628): GKI_exit_task 0 done
I/GKI_LINUX( 2628): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2628): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2628): isSecureModeOn:false
D/BluetoothAdapterService( 2628): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2628): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 2628): Not skipping com.android.bluetooth.gatt.GattService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BtGatt.DebugUtils( 2628): handleDebugAction() action=null
W/BluetoothAdapterService( 2628): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 2628): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 2628): Received stop request...Stopping profile...
D/BtGatt.GattService( 2628): stop()
D/BtGatt.AdvertiseManager( 2628): advertise clients cleared
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2628): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 2628): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2628): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cfd0448
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/HeadsetService( 2628): Received stop request...Stopping profile...
,D/TimaKeyStoreProvider( 6247): TimaSignature is unavailable
,W/BluetoothAdapterService( 2628): Not skipping com.android.bluetooth.hid.HidService
D/ActivityThread( 6247): Added TimaKeyStore provider
,D/BluetoothAdapterService( 2628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cfd0448
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2628): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService,
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2628): Not skipping com.android.bluetooth.hdp.HealthService
D/AudioService( 1017): onServiceDisconnected: Bluetooth profile: 1
D/HeadsetProfile( 1305): Bluetooth service disconnected
,D/A2dpService( 2628): Received stop request...Stopping profile...
D/A2dpStateMachine( 2628): Exit Disconnected: -1
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2628): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2628): Not skipping com.android.bluetooth.pan.PanService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
W/BluetoothAdapterService( 2628): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cfd0448
,D/BluetoothA2dp( 1017): Proxy object disconnected
D/AudioService( 1017): onServiceDisconnected: Bluetooth profile: 2
,W/BluetoothAdapterService( 2628): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/BluetoothA2dp( 1305): Proxy object disconnected
D/A2dpProfile( 1305): Bluetooth service disconnected
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2628): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2628): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2628): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2628): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2628): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2628): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2628): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2628): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2628): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService,
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2628): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2628): Stopping profile services that were post enabled,
E/BluetoothAdapterService(754779208)( 2628): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
E/BluetoothAdapterService(754779208)( 2628): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.hid.HidService,
D/BluetoothAdapterService( 2628): Profile still running: com.android.bluetooth.hid.HidService
,D/HidService( 2628): Received stop request...Stopping profile...
D/HidService( 2628): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2628): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 2628): cleanup: HH disabling or disabled already, status = 0,
W/BluetoothHidServiceJni( 2628): Cleaning up Bluetooth GID callback object
,D/FileShare-Server( 6247): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/BluetoothAdapterService( 2628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cfd0448
,E/AffinityControl( 6197): AffinityControl: registerfunction enter
,D/BluetoothInputDevice( 1305): Proxy object disconnected
D/HidProfile( 1305): Bluetooth service disconnected
,W/BluetoothHeadsetServiceJni( 2628): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2628): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 2628): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cfd0448
,D/PanService( 2628): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cfd0448
,D/BluetoothPan( 1017): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 1305): BluetoothPAN Proxy object disconnected
D/PanProfile( 1305): Bluetooth service disconnected
,E/BluetoothAdapterService(754779208)( 2628): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2628): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2628): Proxy object disconnected
D/BluetoothAdapterService( 2628): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 2628): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2628): GKI_exit_task 2 done
I/GKI_LINUX( 2628): GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothMapService( 2628): Received stop request...Stopping profile...
,I/ActivityManager( 1017): Killing 5302:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1717): Starting #9
I/Hs20UtilService( 1717): Message received 5007
,D/AndroidRuntime( 6197): Calling main entry com.android.commands.pm.Pm
,D/BluetoothAdapterService( 2628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cfd0448
,D/SapService( 2628): Received stop request...Stopping profile...
D/SapService( 2628): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cfd0448
,D/BluetoothMap( 1305): Proxy object disconnected
,D/MapProfile( 1305): Bluetooth service disconnected
E/BluetoothAdapterService(754779208)( 2628): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2628): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(754779208)( 2628): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2628): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2628): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2628): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(754779208)( 2628): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2628): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2628): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2628): Cleaning up Bluetooth PAN callback object
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,E/BluetoothAdapterService(754779208)( 2628): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2628): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2628): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(754779208)( 2628): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 2628): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2628): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/BluetoothAdapterState( 2628): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2628): Setting state to 10
I/BluetoothAdapterState( 2628): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2628): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2628): updateAdapterState state is 10
D/BluetoothAdapterService( 2628): Autoconnection is available 
D/BluetoothAdapterService( 2628): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2628): Entering OffState
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1305): MountReceiver.onReceive - Set preference state off
,D/Bluetoothsap( 1305): BluetoothSAP Proxy object disconnected
D/SapProfile( 1305): Bluetooth service disconnected
V/NearbySettings( 1305): MountReceiver.mPrefHandler - 7002
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1017): START PACKAGE DELETE: observer{205938005}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/BluetoothAdapter( 1432): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1432): Bluetooth is turned off, stop adv and scan
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothA2dp( 2628): onBluetoothStateChange: up=false
,D/PackageManager( 1017): !@killApplicatoin: 10345, uninstall pkg
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/wpa_supplicant( 1383): Blacklist: Clear (all) 
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_4232/cgroup.procs: No such file or directory
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1383): wlan0: CTRL-EVENT-TERMINATING 
,W/PackageSettings( 1017): Skipping PackageSetting{c24fd66 com.test.thalitest/10338} due to missing metadata
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 6059:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/Hs20UtilService( 1717): Starting #10
,I/Hs20UtilService( 1717): Message received 5011
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{3a86e371 u0 com.example.hello/.MainActivity t19}
,D/BluetoothA2dp( 1017): onBluetoothStateChange: up=false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6268): MountEmulatedStorage()
I/libpersona( 6268): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6268): v2
I/libpersona( 6268): KNOX_SDCARD not a persona
I/SELinux ( 6268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6268 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6268): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/InputDispatcher( 1017): Focus left window: 6059
E/SELinux ( 6268): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  259): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1017): Focused application released
E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager( 1017): Force stopping com.example.hello appid=10345 user=0: pkg removed
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/art     (  324): Explicit concurrent mark sweep GC freed 8669(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 26.848ms
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/TimaKeyStoreProvider( 6268): TimaSignature is unavailable
,D/ActivityThread( 6268): Added TimaKeyStore provider
,D/BluetoothInputDevice( 1305): onBluetoothStateChange: up=false
I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 17.246ms
,E/WifiStateMachine( 1017): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [21]
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 753us total 16.782ms
,I/art     ( 4140): Explicit concurrent mark sweep GC freed 18704(1058KB) AllocSpace objects, 4(64KB) LOS objects, 50% free, 3MB/7MB, paused 740us total 36.501ms
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5302/cgroup.procs: No such file or directory
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 5890): Explicit concurrent mark sweep GC freed 10083(463KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 3MB/5MB, paused 657us total 61.122ms
,I/art     ( 5335): Explicit concurrent mark sweep GC freed 9893(663KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 737us total 58.771ms
,E/SamsungIME( 1848): mOCRHelper is null
,W/GeofencerStateMachine( 1812): Ignoring removeGeofence because network location is disabled.
,W/Settings( 5970): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ResourcesManager( 1456): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
,D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,W/Settings( 1812): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiCredService( 1305): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1177): onReceive : 1, 0
,D/Bluetoothsap( 1305): onBluetoothStateChange: up=false
D/Bluetoothsap( 1305): Unbinding service...
,D/BluetoothMap( 1305): onBluetoothStateChange: up=false
,D/SecurityLogAgent( 6268): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6268): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6268): StateMachine : Current State = 1
,D/BluetoothAdapter( 1305): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1305): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1446): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1446): Bluetooth is turned off, stop adv and scan
,D/BluetoothPbap( 1305): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1305): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1812): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1812): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1177): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1177): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 2628): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2628): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1456): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1456): Bluetooth is turned off, stop adv and scan
D/SecurityLogAgent( 6268): StateMachine : Changed Current State = 1
D/BluetoothAdapter( 1017): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1017): Bluetooth is turned off, stop adv and scan
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1017): Killing 5690:com.samsung.helphub/1000 (adj 15): empty #31
,E/BluetoothManagerService( 1017): Unable to call onBluetoothStateChange() on callback #22
E/BluetoothManagerService( 1017): android.os.DeadObjectException
E/BluetoothManagerService( 1017): 	at android.os.BinderProxy.transactNative(Native Method)
E/BluetoothManagerService( 1017): 	at android.os.BinderProxy.transact(Binder.java:511)
E/BluetoothManagerService( 1017): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
E/BluetoothManagerService( 1017): 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1067)
E/BluetoothManagerService( 1017): 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2021)
E/BluetoothManagerService( 1017): 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
E/BluetoothManagerService( 1017): 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1590)
E/BluetoothManagerService( 1017): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/BluetoothManagerService( 1017): 	at android.os.Looper.loop(Looper.java:145)
E/BluetoothManagerService( 1017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/BluetoothManagerService( 1017): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceUp() to 0 receivers.
,I/GKI_LINUX( 2628): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2628): GKI_exit_task 1 done
I/GKI_LINUX( 2628): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2628): cleanupNative: return from cleanup
,I/art     ( 2628): System.exit called, status: 0
,I/AndroidRuntime( 2628): VM exiting with result code 0, cleanup skipped.
,D/BluetoothAdapter( 1177): 823201035: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 1177): 823201035: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 10
D/BluetoothAdapter( 1177): 823201035: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1177): 823201035: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1177): 823201035: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,I/SamsungIME( 1848): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,V/BluetoothEventManager( 1305): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
,D/RegisteredServicesCache( 1446): empty dynamic service
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1017): uID is 10345
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1017): Process com.android.bluetooth (pid 2628)(adj 0) has died(57,697)
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello,
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/TaskPersister( 1017): removeObsoleteFile: deleting file=19_task.xml
,D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1017): uID is 10345
,V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1017): [BT Setting State] State =10
I/InputMethodManagerService( 1017): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/ApplicationPolicy( 1017): updateDataUsageMap
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 59023(3MB) AllocSpace objects, 13(268KB) LOS objects, 33% free, 24MB/36MB, paused 2.584ms total 246.811ms
,D/PackageManager( 1017): delete codoeFile: 
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
,I/AASA_removePackage( 1017): UID=10345 Target=com.example.hello
,D/PackageManager( 1017): result of delete: 1{205938005}
,D/AndroidRuntime( 6197): Shutting down VM
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1017): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1017): onPackageRemoved : com.example.hello
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5690/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/art     ( 6197): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 10011
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Tethering( 1017): interfaceRemoved wlan0
E/Tethering( 1017): attempting to remove unknown iface (wlan0), ignoring
,I/KLMS-2.5.123: ( 3718): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sat Nov 28 12:16:17 GMT+01:00 2015
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3718): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1017): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1017): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1017): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
,I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6292): MountEmulatedStorage()
E/Zygote  ( 6292): v2
I/libpersona( 6292): KNOX_SDCARD checking this for 10090
I/libpersona( 6292): KNOX_SDCARD not a persona
,I/KLMS-2.5.123: ( 3718): KLMSIntentService(): onCreate()
,I/SELinux ( 6292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/KLMS-2.5.123: ( 3718): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3718): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SELinux ( 6292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6292): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6292 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3718): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3718): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3718): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3718): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/Tethering( 1017): interfaceRemoved p2p0
E/Tethering( 1017): attempting to remove unknown iface (p2p0), ignoring
,D/TimaKeyStoreProvider( 6292): TimaSignature is unavailable
,D/ActivityThread( 6292): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3718): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3718): KLMSIntentService(): onDestroy()
,D/elm:15121( 6292): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6292): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6292): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 6292): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 6292): ElmAgentService : onCreate()
D/elm:15121( 6292): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6292): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6292): MDMBridge.getInstance()
D/elm:15121( 6292): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 6292): MDMBridge.getAllLicenseInfoFromSDK()
I/PCWCLIENTTRACE_PushUtil( 5733): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5733): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5733): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5733): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5842): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5842): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,D/elm:15121( 6292): ElmAgentService : onDestroy().
,I/ActivityManager( 1017): Killing 4803:com.android.mms/u0a41 (adj 15): empty #31
,I/PackagesMonitor( 5041): PackagesMonitor onReceive :com.example.hello
,E/SharedPreferencesImpl( 5041): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak

```
