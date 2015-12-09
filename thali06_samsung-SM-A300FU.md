#### Test 50650278eab32a5_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  293): DCD OFF
--------- beginning of system
V/AlarmManager( 1021): waitForAlarm result :4
I/BooksSync( 6021): Starting books sync for 61035162, extras: ade
I/BooksConfig( 6021): GmsCore Version = 7.8.99 (2134222-434)
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/BooksAccountManager( 6021): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
E/BooksSync( 6021): Soft error
E/BooksSync( 6021): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6021): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6021): Sync error
E/BooksSync( 6021): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6021): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6021): Finished books sync
D/SyncManager( 1021): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 152019, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
,D/AndroidRuntime( 6089): 
D/AndroidRuntime( 6089): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6089): CheckJNI is OFF
D/AndroidRuntime( 6089): readGMSProperty: start
D/AndroidRuntime( 6089): readGMSProperty: already setted!!
D/AndroidRuntime( 6089): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6089): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6089): readGMSProperty: end
D/AndroidRuntime( 6089): addProductProperty: start
E/AffinityControl( 6089): AffinityControl: registerfunction enter
D/AndroidRuntime( 6089): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1021): mDVFSHelper.acquire()
D/FocusedStackFrame( 1021): Set to : 0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1021): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1021): *FMB* installDecor flags : 25362712
E/Zygote  ( 6101): MountEmulatedStorage()
E/Zygote  ( 6101): v2
I/libpersona( 6101): KNOX_SDCARD checking this for 10338
I/libpersona( 6101): KNOX_SDCARD not a persona
I/SELinux ( 6101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6101 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 1481
D/AndroidRuntime( 6089): Shutting down VM
I/SELinux ( 6101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6101): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6101): TimaSignature is unavailable
D/ActivityThread( 6101): Added TimaKeyStore provider
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
V/WindowManager( 1021): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1021): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
D/Launcher( 1481): onTrimMemory. Level: 20
V/ActivityThread( 1481): updateVisibility : ActivityRecord{889e406 token=android.os.BinderProxy@393a8540 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/WebViewFactory( 6101): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6101): Time to load native libraries: 1 ms (timestamps 3194-3195)
I/LibraryLoader( 6101): Expected native library version number "",actual native library version number ""
W/art     ( 6089): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/WebViewChromiumFactoryProvider( 6101): Binding Chromium to main looper Looper (main, tid 1) {2056b4ce}
I/LibraryLoader( 6101): Expected native library version number "",actual native library version number ""
I/chromium( 6101): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6101): Initializing chromium process, singleProcess=true
,W/art     ( 6101): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6101): ApplicationContext is null in ApplicationStatus
,W/chromium( 6101): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6101): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6101): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6101): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6101): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6101): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6101): Local Branch: 
I/Adreno-EGL( 6101): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6101): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6101):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6101): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6101): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6101): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6101): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6101): CordovaWebView is running on device made by: samsung
,W/art     ( 6101): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6101): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1021): Activity pause timeout for ActivityRecord{23bfb396 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6101): Render dirty regions requested: true
,D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
,W/chromium( 6101): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6101): updateVisibility : ActivityRecord{17ef9dfb token=android.os.BinderProxy@272599f5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6101): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6101): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1021): Focus entered window: 6101
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6101): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6101): Initialized EGL, version 1.4
D/OpenGLRenderer( 6101): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6101): Enabling debug mode 0
,D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
,I/ActivityManager( 1021): Displayed Component not be shown by security: +679ms (total +37s333ms)
W/IInputConnectionWrapper( 6101): showStatusIcon on inactive InputConnection
,I/Timeline( 6101): Timeline: Activity_idle id: android.os.BinderProxy@272599f5 time:153732
,W/ActivityManager( 1021): mDVFSHelper.release()
,I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{23bfb396 u0 com.test.thalitest/.MainActivity t20} time:153733
,I/SurfaceFlinger(  259): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  259): id=12 Removed uhalitest (-2/9)
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1821): getCurrentCandidateView
,D/SamsungIME( 1821): Dismiss ExpandCandiate
,I/SamsungIME( 1821): getDebugLevel  : 0x4f4c
,W/BindingManager( 6101): Cannot call determinedVisibility() - never saw a connection for the pid: 6101
,I/SamsungIME( 1821): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1821): KeybaordView init() : load resources
,I/SamsungIME( 1821): getCurrentKeyboard
I/SamsungIME( 1821): getTextKeyboard
,D/SamsungIME( 1821): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6101): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6101): JniHelper::setJavaVM(0xb78c4448), pthread_self() = -1209941584
,D/JX-Cordova( 6101): jxcore cordova android initializing
,E/SMD     (  293): DCD OFF
,W/jxcore-log( 6101): Initializing JXcore engine
W/jxcore-log( 6101): JXcore engine is ready
,W/jxcore-log( 6101): Starting JXcore engine
,E/audit   ( 1817): type=1400 msg=audit(1449668743.149:205): avc:  denied  { ioctl } for  pid=6101 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1817):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1817): type=1300 msg=audit(1449668743.149:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=bec52d58 items=0 ppid=311 ppcomm=main pid=6101 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null),
E/audit   ( 1817): type=1320 msg=audit(1449668743.149:205): 
,W/jxcore-log( 6101): Platform android
W/jxcore-log( 6101): 
W/jxcore-log( 6101): Process ARCH arm
W/jxcore-log( 6101): 
,I/jxcore-log( 6101): JXcore Cordova bridge is ready!
I/jxcore-log( 6101): 
W/jxcore-log( 6101): JXcore engine is started
,I/Choreographer( 6101): Skipped 124 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6101): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 6101): Error!: missing ) after argument list
E/jxcore  ( 6101): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6101): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1021): Set to : 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1021): Focused application set to: xxxx
,D/InputDispatcher( 1021): Focus left window: 6101
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1021): Killing 5206:com.google.android.gm/u0a99 (adj 15): empty #31
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
,W/ActivityManager( 1021): mDVFSHelper.acquire()
,V/WindowManager( 1021): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1481): onRestart, Launcher: 418314984
,D/Launcher( 1481): onStart, Launcher: 418314984
,D/Launcher.HomeView( 1481): onStart
D/Launcher( 1481): onResume, Launcher: 418314984
,D/SettingsProvider( 1021): name = kids_home_mode
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10006
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1021): ret = -1
,D/Launcher.HomeView( 1481): onResume
,D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1481): onResume
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1021): handle home activity for 0
,I/WallpaperManagerService( 1021): switchPersonaWallpaper is called for personaId-0
,D/KnoxTimeoutHandler( 1021): post home show event for user 0
D/WallpaperManagerService( 1021):  force update = false; persona id = 0; current user =0; current persona = 0
,D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): handleHomeShow for 0 and current 0
,D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
D/Launcher.HomeView( 1481): onPause
,D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/splitIntent( 1021): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,I/splitIntent( 1021): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/GalleryCacheReady( 4991): Receive : home resume
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,D/Recents_RecreateReceiver( 2455): onReceive by home
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,V/TaskCloserActivity( 5995): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/Mms/UIEventReceiver( 5621): ui event
,I/SurfaceFlinger(  259): id=14 createSurf (540x960),1 flag=4, Mauncher
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1021): failed to open /acct/uid_10099/pid_5206/cgroup.procs: No such file or directory
,D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1021): Focus entered window: 1481
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1481): log_dcs ThreadedRenderer::initialize entered! 
,E/Zygote  ( 6152): MountEmulatedStorage()
I/libpersona( 6152): KNOX_SDCARD checking this for 10135
E/Zygote  ( 6152): v2
I/libpersona( 6152): KNOX_SDCARD not a persona
,I/SELinux ( 6152): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6152): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6152): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,V/ActivityThread( 1481): updateVisibility : ActivityRecord{889e406 token=android.os.BinderProxy@393a8540 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1481): onStop
I/ActivityManager( 1021): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6152 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6101): showStatusIcon on inactive InputConnection
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SamsungIME( 1821): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1021): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,D/TimaKeyStoreProvider( 6152): TimaSignature is unavailable
,I/Timeline( 1481): Timeline: Activity_idle id: android.os.BinderProxy@393a8540 time:156534
,D/ActivityThread( 6152): Added TimaKeyStore provider
,W/ActivityManager( 1021): mDVFSHelper.release()
I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{9c5af32 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:156548
,W/ResourcesManager( 6152): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6152): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6152): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6152): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 6152): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/splitIntent( 1021): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1021): Killing 4161:com.sec.spp.push/u0a32 (adj 15): empty #31
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 5995): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/PersonaManager( 1021): isKioskContainerExistOnDevice
,D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,W/libprocessgroup( 1021): failed to open /acct/uid_10032/pid_4161/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1021): [PWL] Off : 75s ago
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,V/AlarmManager( 1021): waitForAlarm result :4
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5362): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5362): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5362): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1021): SIOP:: AP = 280,
,E/Watchdog( 1021): !@Sync 5
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 1021): waitForAlarm result :4
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5362): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5362): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5362): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF,
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 105s ago
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 6
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1688): Vacuum at: now=1449668791368 tag=VacuumService
,I/GoogleURLConnFactory( 1688): Using platform SSLCertificateSocketFactory
,W/Uploader( 1688): No account for auth token provided
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 46675(2MB) AllocSpace objects, 46(740KB) LOS objects, 33% free, 23MB/35MB, paused 2.440ms total 167.654ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1688): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1688): (HTTPLog)-Static: isShipBuild true
I/System.out( 1688): (HTTPLog)-Thread-190-404530418: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,I/System.out( 1688): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,I/qtaguid ( 1688): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/Uploader( 1688):  no longer exists, so no auth token.
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,E/SQLiteLog( 1688): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 140s ago
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/Watchdog( 1021): !@Sync 7,
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :8,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1021): !@Sync 8
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 180s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1021): stay LED for fully charged
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6021): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6021): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6021): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6021): Soft error
E/BooksSync( 6021): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6021): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6021): Sync error
E/BooksSync( 6021): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6021): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6021): Finished books sync
,D/SyncManager( 1021): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 274021, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 9
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 225s ago
,E/SMD     (  293): DCD OFF
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1021): initializing...
,I/TLC_TIMA_PKM_initialize( 1021): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1021): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1021): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1021): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1021): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1021): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1021): max_message_size = 524416 = 0x80080,
D/QSEECOMAPI: ( 1021): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: ( 1021): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1021): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1021): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1021): Trustlet response is completed
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1021): !@Sync 10
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 11
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1021): waitForAlarm result :8
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD OFF
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,W/GLSActivity( 1688): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1688): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1688): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1688): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1688): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1688): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1688): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 5362): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5362): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5362): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5362): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5362): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5362): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5362): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 5362): Ignoring header User-Agent because its value was null.
,I/System.out( 5362): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5362): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5362): (HTTPLog)-Static: isShipBuild true
I/System.out( 5362): (HTTPLog)-Thread-903-474550521: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5362): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10026
,I/System.out( 5362): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 275s ago
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 12
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1021): !@Sync 13
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1021): [PWL] Off : 330s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 14
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/Watchdog( 1021): !@Sync 15
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 1021): [PWL] Off : 390s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/bootchecker(  327): bootchecker wake up!!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/Watchdog( 1021): !@Sync 16
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 17,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,V/AlarmManager( 1021): waitForAlarm result :8
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6021): Starting books sync for 61035162, extras: ade
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6021): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,E/SMD     (  293): DCD OFF
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6021): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6021): Soft error
E/BooksSync( 6021): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6021): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6021): Sync error
E/BooksSync( 6021): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6021): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6021): Finished books sync
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1021): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 517739, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1021): mCursor = null
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 455s ago,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/Watchdog( 1021): !@Sync 18
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,I/Atfwd_Daemon(  331): Stop the daemon....,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/Watchdog( 1021): !@Sync 19
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :8,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1021): Plugged,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 525s ago,
,E/SMD     (  293): DCD OFF,
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/Watchdog( 1021): !@Sync 20
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/BatteryService( 1021): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 21
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/Watchdog( 1021): !@Sync 22
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 600s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/Watchdog( 1021): !@Sync 23
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 24
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10,
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): stay LED for fully charged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate,
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 680s ago
,E/Watchdog( 1021): !@Sync 25
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 26
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  293): DCD OFF
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 27
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,I/PowerManagerService( 1021): [PWL] Off : 765s ago,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 28
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged,
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/Watchdog( 1021): !@Sync 29
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,E/SMD     (  293): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1021): !@Sync 30
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/EventLogService( 1997): Aggregate from 1449667159497 (log), 1449667159497 (data)
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1688): Message class com.google.f.a.a.i
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GCM     ( 1997): Message from null null
,E/GCM     ( 1997): Dropping message from null
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1021): [PWL] Off : 855s ago
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 31
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 32
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/Watchdog( 1021): !@Sync 33,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1021): waitForAlarm result :4
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6021): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6021): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksAccountManager( 6021): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6021): Soft error
E/BooksSync( 6021): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6021): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6021): Sync error
E/BooksSync( 6021): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6021): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6021): Finished books sync
,D/SyncManager( 1021): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1022510, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1021): mCursor = null
,E/SQLiteLog( 1688): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 950s ago,
,E/Watchdog( 1021): !@Sync 34
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,V/AlarmManager( 1021): waitForAlarm result :4
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/Watchdog( 1021): !@Sync 35
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/Watchdog( 1021): !@Sync 36
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/Watchdog( 1021): !@Sync 37
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 1050s ago
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 38,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 39
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1021): User[0] Flushing usage stats to disk,
,I/ApplicationUsage( 1021): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1021): Updating Usage Statistics in DB @ 1449669803599
,I/ApplicationPolicy( 1021): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1021): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1021): ::isTableExists: Table exists 
,I/ApplicationUsage( 1021): Done Updating Usage Statistics in DB @ 1449669803966
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 40
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): Plugged,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 1155s ago,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 41
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 42
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/Watchdog( 1021): !@Sync 43
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/Watchdog( 1021): !@Sync 44,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 1266s ago,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 45
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 46
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/Watchdog( 1021): !@Sync 47
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 48,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 1381s ago,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 49
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,E/SMD     (  293): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1021): !@Sync 50
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 51
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/Watchdog( 1021): !@Sync 52
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 1501s ago
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 53
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 54
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/Watchdog( 1021): !@Sync 55
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 56
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 1626s ago,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 57,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 58
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/Watchdog( 1021): !@Sync 59
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 60
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,I/ActivityManager( 1021): Killing 5280:com.google.android.partnersetup/u0a14 (adj 15): empty #31
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
I/ActivityManager( 1021): Killing 5632:com.samsung.helphub/1000 (adj 15): empty #32
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,I/ActivityManager( 1021): Killing 5188:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #33
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,I/ActivityManager( 1021): Killing 2962:com.samsung.android.providers.context/u0a2 (adj 15): SPC_empty #34
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,I/ProcessStatsService( 1021): Prepared write state in 14ms
,I/ProcessStatsService( 1021): Prepared write state in 8ms
,V/NetworkStats( 1021): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox main else ---
,V/NetworkStats( 1021): performPollLocked() took 7ms
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GpsStatusListenerHelper( 1021): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@48c8bd6
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1021): Scheduling restart of crashed service com.samsung.android.providers.context/.ContextService in 3603460ms
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ProcessStatsService( 1021): Pruning old procstats: /data/system/procstats/state-2015-12-08-18-25-38.bin
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_5632/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10014/pid_5280/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10032/pid_5188/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10002/pid_2962/cgroup.procs: No such file or directory
,D/GCM     ( 1688): Message class com.google.f.a.a.i
,E/SMD     (  293): DCD OFF
,E/SQLiteLog( 1688): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,I/ActivityManager( 1021): Killing 2695:com.sec.phone/1001 (adj 15): SPC_empty #31
,I/ActivityManager( 1021): Killing 3489:com.sec.android.pagebuddynotisvc/u0a113 (adj 15): SPC_empty #32,
E/lowmemorykiller(  256): Error writing /proc/3489/oom_score_adj; errno=22
,I/ActivityManager( 1021): Killing 3648:com.sec.bcservice/1000 (adj 15): SPC_empty #31
,W/ActivityManager( 1021): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 1000ms
,W/ActivityManager( 1021): Scheduling restart of crashed service com.sec.phone/.SecPhoneService in 10996ms
,W/ActivityManager( 1021): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 10931ms,
,W/libprocessgroup( 1021): failed to open /acct/uid_10113/pid_3489/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_1001/pid_2695/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3648/cgroup.procs: No such file or directory
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6883): MountEmulatedStorage(),
E/Zygote  ( 6883): v2
I/libpersona( 6883): KNOX_SDCARD checking this for 10113
,I/libpersona( 6883): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.sec.android.pagebuddynotisvc for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc: pid=6883 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,I/SELinux ( 6883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6883): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6883): TimaSignature is unavailable
,D/ActivityThread( 6883): Added TimaKeyStore provider
,I/PageBuddyNotiSvc( 6883): onCreate mCpBitFlag=0
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 1756s ago
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1021): !@Sync 61,
,E/SMD     (  293): DCD OFF,
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6903): MountEmulatedStorage(),
,E/Zygote  ( 6903): v2
I/libpersona( 6903): KNOX_SDCARD checking this for 1000
I/libpersona( 6903): KNOX_SDCARD not a persona
,I/ActivityManager( 1021): Start proc com.sec.bcservice for service com.sec.bcservice/.BroadcastService: pid=6903 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6903): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6903): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6903): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6903): TimaSignature is unavailable
,D/ActivityThread( 6903): Added TimaKeyStore provider
,I/ActivityManager( 1021): Killing 2118:com.samsung.hs20settings/1000 (adj 15): SPC_empty #31
,W/ResourcesManager( 6903): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/F_PHONE ( 6903): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 6903): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6918): MountEmulatedStorage()
,E/Zygote  ( 6918): v2
I/libpersona( 6918): KNOX_SDCARD checking this for 1001
I/libpersona( 6918): KNOX_SDCARD not a persona
,I/SELinux ( 6918): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.sec.phone for service com.sec.phone/.SecPhoneService: pid=6918 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,I/SELinux ( 6918): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6918): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  311): Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 30.046ms
,W/ActivityManager( 1021): Scheduling restart of crashed service com.samsung.hs20settings/.WifiHs20UtilityService in 1000ms
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_2118/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6918): TimaSignature is unavailable
,D/ActivityThread( 6918): Added TimaKeyStore provider
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 18.028ms
,W/ResourcesManager( 6918): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 16.708ms
,D/F_PHONE ( 6903): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 6903): default registerAction()
I/F_PHONE ( 6903): [[com.sec.bcservice]] sendPendingMessage()
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6937): MountEmulatedStorage(),
E/Zygote  ( 6937): v2
I/libpersona( 6937): KNOX_SDCARD checking this for 1000
I/libpersona( 6937): KNOX_SDCARD not a persona
,I/SELinux ( 6937): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.samsung.hs20settings for service com.samsung.hs20settings/.WifiHs20UtilityService: pid=6937 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 6937): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6937): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6937): TimaSignature is unavailable
,D/ActivityThread( 6937): Added TimaKeyStore provider
,I/Hs20UtilService( 6937): onCreate
,I/Hs20UtilService( 6937): Starting #8
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 62
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 63
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 64
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7000): 
D/AndroidRuntime( 7000): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7000): CheckJNI is OFF
D/AndroidRuntime( 7000): readGMSProperty: start
D/AndroidRuntime( 7000): readGMSProperty: already setted!!
D/AndroidRuntime( 7000): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7000): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7000): readGMSProperty: end
D/AndroidRuntime( 7000): addProductProperty: start
E/AffinityControl( 7000): AffinityControl: registerfunction enter
D/AndroidRuntime( 7000): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1021): START PACKAGE DELETE: observer{909981964}
D/PackageManager( 1021): pkg{<packageName>}
D/PackageManager( 1021): user{0}
D/PackageManager( 1021): caller{2000}
D/PackageManager( 1021): flags{3}
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1021): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1021): !@killApplicatoin: 10338, uninstall pkg
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1021): Killing 6101:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1021): Skipping PackageSetting{1e1217c7 com.example.hello/10345} due to missing metadata
I/ActivityManager( 1021): Killing 5971:com.sec.android.app.samsungapps/u0a9 (adj 15): empty for 1880s
I/ActivityManager( 1021): Killing 5953:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty for 1880s
I/ActivityManager( 1021): Killing 5927:com.google.android.apps.plus/u0a117 (adj 15): empty for 1880s
I/ActivityManager( 1021): Killing 5906:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty for 1881s
I/ActivityManager( 1021): Killing 5884:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1881s
I/ActivityManager( 1021): Killing 5867:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1881s
I/ActivityManager( 1021): Killing 5848:com.sec.android.app.soundalive/u0a48 (adj 15): empty for 1881s
I/ActivityManager( 1021): Killing 5826:com.wsomacp/u0a23 (adj 15): empty for 1881s
I/ActivityManager( 1021): Killing 5810:com.sec.android.app.myfiles/u0a42 (adj 15): empty for 1881s
I/ActivityManager( 1021): Killing 5790:com.sec.android.provider.badge/u0a68 (adj 15): empty for 1881s
I/ActivityManager( 1021): Killing 5754:com.osp.app.signin/u0a36 (adj 15): empty for 1881s
I/ActivityManager( 1021): Killing 4848:com.google.android.gms.wearable/u0a11 (adj 15): empty for 1881s
I/ActivityManager( 1021): Killing 5741:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty for 1882s
I/ActivityManager( 1021): Killing 5717:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty for 1882s
I/ActivityManager( 1021): Killing 5701:com.policydm/1000 (adj 15): empty for 1882s
I/ActivityManager( 1021): Killing 5292:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty for 1882s
I/ActivityManager( 1021): Killing 5668:com.sec.pcw.device/1000 (adj 15): empty for 1882s
I/ActivityManager( 1021): Killing 5652:com.google.android.apps.docs/u0a87 (adj 15): empty for 1882s
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
E/JavaBinder( 1021): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1021): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1021): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1021): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1021): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1021): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1021): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3963): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 698us total 22.403ms
I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1821): mOCRHelper is null
W/GeofencerStateMachine( 1703): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.123: ( 3694): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 15:15:51 GMT+01:00 2015
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3694): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1021): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1021): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1021): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): onCreate()
E/Zygote  ( 7013): MountEmulatedStorage()
I/libpersona( 7013): KNOX_SDCARD checking this for 10090
E/Zygote  ( 7013): v2
I/libpersona( 7013): KNOX_SDCARD not a persona
I/SELinux ( 7013): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7013): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7013): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3694): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/ActivityManager( 1021): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7013 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3694): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
D/TimaKeyStoreProvider( 7013): TimaSignature is unavailable
D/ActivityThread( 7013): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/art     ( 1021): Explicit concurrent mark sweep GC freed 36336(3MB) AllocSpace objects, 72(1204KB) LOS objects, 33% free, 24MB/36MB, paused 6.610ms total 227.047ms
I/art     ( 1021): WaitForGcToComplete blocked for 221.376ms for cause Explicit
D/elm:15121( 7013): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 7013): ELMEngine.ELMEngine( context ).
D/elm:15121( 7013): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/RegisteredServicesCache( 1438): empty dynamic service
D/RCPManagerService( 1021): PackageReceiver onReceive()
D/elm:15121( 7013): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/HarmonyEASService( 1021): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1021): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:15121( 7013): ElmAgentService : onCreate()
D/elm:15121( 7013): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 7013): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 7013): MDMBridge.getInstance()
D/elm:15121( 7013): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 7013): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:15121( 7013): ElmAgentService : onDestroy().
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): onDestroy()
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1021): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10338
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10338
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
D/SSRM:aZ ( 1021): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
D/TaskPersister( 1021): removeObsoleteFile: deleting file=20_task.xml
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
E/SMD     (  293): DCD OFF
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/art     ( 1021): Explicit concurrent mark sweep GC freed 13500(744KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 3.123ms total 189.326ms
E/Zygote  ( 7030): MountEmulatedStorage()
E/Zygote  ( 7030): v2
I/libpersona( 7030): KNOX_SDCARD checking this for 1000
I/libpersona( 7030): KNOX_SDCARD not a persona
I/SELinux ( 7030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7030): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7030 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 7030): TimaSignature is unavailable
D/ActivityThread( 7030): Added TimaKeyStore provider
I/PCWCLIENTTRACE_LOG( 7030): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7030): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7030): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 7030): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7030): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7030): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7030): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1021): delete codoeFile: 
D/AASAuninstall( 1021): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1021): UID=10338 Target=com.test.thalitest
D/PackageManager( 1021): result of delete: 1{909981964}
D/AndroidRuntime( 7000): Shutting down VM
E/Zygote  ( 7045): MountEmulatedStorage()
E/Zygote  ( 7045): v2
I/libpersona( 7045): KNOX_SDCARD checking this for 10029
I/libpersona( 7045): KNOX_SDCARD not a persona
I/SELinux ( 7045): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7045 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 7045): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7045): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7045): TimaSignature is unavailable
D/ActivityThread( 7045): Added TimaKeyStore provider
I/FeatureConfig( 7045): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7062): MountEmulatedStorage()
E/Zygote  ( 7062): v2
I/libpersona( 7062): KNOX_SDCARD checking this for 10036
I/libpersona( 7062): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7062 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 5589:com.android.defcontainer/u0a3 (adj 15): empty for 1872s
I/SELinux ( 7062): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7062): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7062): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 7045): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 7062): TimaSignature is unavailable
D/ActivityThread( 7062): Added TimaKeyStore provider
W/ResourcesManager( 7045): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 7062): [SSP] onCreated
W/ResourcesManager( 7045): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 7062): [TPM] There is no property file
I/SA      ( 7062): [SCU] isHaveSA() - false
I/SA      ( 7062): [TPM] getModelProperty : null
I/SA      ( 7062): [TPM] getCSCProperty : null
W/ResourcesManager( 7045): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/SA      ( 7062): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 7062): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 7062): [DM] TFT FEATURE: false
I/SA      ( 7062): [DM] init START
I/SA      ( 7062): [DM] This device is not a Vodafone
W/ResourcesManager( 7045): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourceType( 7062): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7062): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7062): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/art     ( 7000): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ResourceType( 7062): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 7062): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
W/ResourcesManager( 7045): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 7062): [SCU] isHaveSA() - false
I/SA      ( 7062): support phone number id : false
I/SA      ( 7062): [DM] Supports Ref Jpn : true
I/SA      ( 7062): [DM] init END
I/SA      ( 7062): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 7062): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1021): Killing 4991:com.sec.android.gallery3d/u0a39 (adj 15): empty for 1808s
W/ResourcesManager( 7045): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
E/JavaBinder( 1021): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 1021): Exception when sending broadcast to ComponentInfo{com.sec.android.gallery3d/com.sec.android.gallery3d.app.PackagesMonitor}
W/BroadcastQueue( 1021): android.os.TransactionTooLargeException
W/BroadcastQueue( 1021): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1021): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1021): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1021): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1021): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1021): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1021): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1021): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1021): 	at android.os.Binder.execTransact(Binder.java:461)
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 7045): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/Zygote  ( 7082): MountEmulatedStorage()
E/Zygote  ( 7082): v2
I/libpersona( 7082): KNOX_SDCARD checking this for 10039
I/libpersona( 7082): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7082 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
W/ResourcesManager( 7045): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/GalaxyFinderApplication( 7045): system/finder_cp/cpdata.xml file not found
I/SELinux ( 7082): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7082): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7082): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7082): TimaSignature is unavailable
D/ActivityThread( 7082): Added TimaKeyStore provider
W/ResourcesManager( 7082): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7082): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7082): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7082): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7082): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7082): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7082): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
E/SQLiteLog( 7082): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 7082): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 7082): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7082): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7082): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7082): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7082): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7082): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7082): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7082): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 7082): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 7082): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7082): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 7082): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7082): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7082): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7082): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 7082): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 7082): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 7082): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 7082): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 7082): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 7082): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 7082): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7082): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7082): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 7082): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7082): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7082): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 7082): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)

```
