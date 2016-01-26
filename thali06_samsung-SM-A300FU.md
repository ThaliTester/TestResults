#### Test 5667282762e056f_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  291): DCD OFF
--------- beginning of system
V/AlarmManager( 1019): waitForAlarm result :4
I/BooksSync( 6142): Starting books sync for 61035162, extras: ade
I/BooksConfig( 6142): GmsCore Version = 7.8.99 (2134222-434)
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/BooksAccountManager( 6142): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6142): Soft error
E/BooksSync( 6142): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6142): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6142): Sync error
E/BooksSync( 6142): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6142): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6142): Finished books sync
D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 151621, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,D/AndroidRuntime( 6213): 
D/AndroidRuntime( 6213): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6213): CheckJNI is OFF
D/AndroidRuntime( 6213): readGMSProperty: start
D/AndroidRuntime( 6213): readGMSProperty: already setted!!
D/AndroidRuntime( 6213): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6213): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6213): readGMSProperty: end
D/AndroidRuntime( 6213): addProductProperty: start
E/AffinityControl( 6213): AffinityControl: registerfunction enter
D/AndroidRuntime( 6213): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6225 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/libpersona( 6225): KNOX_SDCARD checking this for 10338
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1492
E/Zygote  ( 6225): MountEmulatedStorage()
E/Zygote  ( 6225): v2
D/AndroidRuntime( 6213): Shutting down VM
I/libpersona( 6225): KNOX_SDCARD not a persona
I/SELinux ( 6225): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6225): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6225): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/TimaKeyStoreProvider( 6225): TimaSignature is unavailable
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/ActivityThread( 6225): Added TimaKeyStore provider
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1492): updateVisibility : ActivityRecord{1ad1c7b token=android.os.BinderProxy@25d0251 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1492): onTrimMemory. Level: 20
I/WebViewFactory( 6225): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6225): Time to load native libraries: 3 ms (timestamps 2865-2868)
I/LibraryLoader( 6225): Expected native library version number "",actual native library version number ""
W/art     ( 6213): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6225): Binding Chromium to main looper Looper (main, tid 1) {2a5ec523}
,I/LibraryLoader( 6225): Expected native library version number "",actual native library version number ""
,I/chromium( 6225): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6225): Initializing chromium process, singleProcess=true,
,W/art     ( 6225): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6225): ApplicationContext is null in ApplicationStatus
,W/chromium( 6225): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6225): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6225): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6225): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6225): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6225): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6225): Local Branch: 
I/Adreno-EGL( 6225): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6225): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6225):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6225): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6225): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6225): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6225): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6225): CordovaWebView is running on device made by: samsung
,W/art     ( 6225): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6225): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{2b60b881 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6225): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,W/chromium( 6225): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6225): updateVisibility : ActivityRecord{f487c7c token=android.os.BinderProxy@5674a4e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6225): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6225): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 6225
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6225): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,I/OpenGLRenderer( 6225): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6225): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6225): Enabling debug mode 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1019): Displayed Component not be shown by security: +651ms (total +35s132ms)
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{2b60b881 u0 com.test.thalitest/.MainActivity t20} time:153365
W/ActivityManager( 1019): mDVFSHelper.release()
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (-2/9)
,W/IInputConnectionWrapper( 6225): showStatusIcon on inactive InputConnection
,I/Timeline( 6225): Timeline: Activity_idle id: android.os.BinderProxy@5674a4e time:153374
,I/SamsungIME( 1860): getCurrentCandidateView
,D/SamsungIME( 1860): Dismiss ExpandCandiate
,I/SamsungIME( 1860): getDebugLevel  : 0x4f4c
,W/BindingManager( 6225): Cannot call determinedVisibility() - never saw a connection for the pid: 6225
,I/SamsungIME( 1860): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1860): KeybaordView init() : load resources
,I/SamsungIME( 1860): getCurrentKeyboard
I/SamsungIME( 1860): getTextKeyboard
,D/SamsungIME( 1860): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6225): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6225): JniHelper::setJavaVM(0xb83c0448), pthread_self() = -1198423440
,I/chromium( 6225): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  291): DCD OFF
,W/jxcore-log( 6225): Initializing JXcore engine
W/jxcore-log( 6225): JXcore engine is ready
,E/audit   ( 1859): type=1400 msg=audit(1453831015.393:205): avc:  denied  { ioctl } for  pid=6273 comm="Thread-1082" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1859):  SEPF_SM-A300FU_5.0.2_0027
,E/audit   ( 1859): type=1300 msg=audit(1453831015.393:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=9ee748f8 items=0 ppid=310 ppcomm=main pid=6273 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm="Thread-1082" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1859): type=1320 msg=audit(1453831015.393:205): 
,W/jxcore-log( 6225): Starting JXcore engine,
,W/jxcore-log( 6225): Platform android
W/jxcore-log( 6225): 
W/jxcore-log( 6225): Process ARCH arm
W/jxcore-log( 6225): 
,I/jxcore-log( 6225): JXcore Cordova bridge is ready!
I/jxcore-log( 6225): 
,W/jxcore-log( 6225): JXcore engine is started
,E/jxcore  ( 6225): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6225): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6225): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus left window: 6225
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1019): Killing 5677:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,W/PluginManager( 6225): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,V/WindowManager( 1019): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1492): onRestart, Launcher: 811581589
,D/Launcher( 1492): onStart, Launcher: 811581589
,D/Launcher.HomeView( 1492): onStart
,D/Launcher( 1492): onResume, Launcher: 811581589
,D/SettingsProvider( 1019): name = kids_home_mode
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 10006
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
,D/Launcher.HomeView( 1492): onResume
,D/Launcher( 1492): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/MenuAppsGridFragment( 1492): onResume
,D/WallpaperManager( 1492): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
I/splitIntent( 1019): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1019): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,D/WallpaperManager( 1492): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 5072): Receive : home resume
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/Recents_RecreateReceiver( 2534): onReceive by home
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6275): MountEmulatedStorage(),
E/Zygote  ( 6275): v2
I/libpersona( 6275): KNOX_SDCARD checking this for 10139
I/libpersona( 6275): KNOX_SDCARD not a persona
,I/SELinux ( 6275): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6275 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 6275): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6275): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
D/Mms/UIEventReceiver( 5746): ui event
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6288 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
E/Zygote  ( 6288): MountEmulatedStorage()
E/Zygote  ( 6288): v2
I/libpersona( 6288): KNOX_SDCARD checking this for 10135
I/libpersona( 6288): KNOX_SDCARD not a persona
,I/SELinux ( 6288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/ActivityManager( 1019): handle home activity for 0
,D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
,D/Launcher.HomeView( 1492): onPause
I/SELinux ( 6288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/Launcher( 1492): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,E/SELinux ( 6288): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/BroadcastQueue( 1019): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1492, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/TimaKeyStoreProvider( 6275): TimaSignature is unavailable
D/ActivityThread( 6275): Added TimaKeyStore provider
,I/SurfaceFlinger(  257): id=14 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/TimaKeyStoreProvider( 6288): TimaSignature is unavailable
,D/ActivityThread( 6288): Added TimaKeyStore provider
,D/InputDispatcher( 1019): Focus entered window: 1492
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 1492): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,V/TaskCloserActivity( 6275): TaskCloserActivity enter()
,V/TaskCloserActivity( 6275): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,V/ActivityThread( 1492): updateVisibility : ActivityRecord{1ad1c7b token=android.os.BinderProxy@25d0251 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1492): onStop
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,W/ResourcesManager( 6288): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6288): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6288): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
I/ActivityManager( 1019): Killing 4224:com.sec.spp.push/u0a32 (adj 15): empty #31
W/ResourcesManager( 6288): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 6288): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1019): failed to open /acct/uid_10139/pid_5677/cgroup.procs: No such file or directory
,W/IInputConnectionWrapper( 6225): showStatusIcon on inactive InputConnection
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1860): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
,I/Timeline( 1492): Timeline: Activity_idle id: android.os.BinderProxy@25d0251 time:156165
,I/splitIntent( 1019): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1019): Killing 5755:com.samsung.helphub/1000 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 6275): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,W/ActivityManager( 1019): mDVFSHelper.release()
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{109b189b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:156187
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/PersonaManager( 1019): isKioskContainerExistOnDevice
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5755/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_4224/cgroup.procs: No such file or directory
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2630): Disconnected process message: 10
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/AlarmManager( 1019): waitForAlarm result :8
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1179): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5466): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5466): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5466): [1] 5.onFinished: Scheduling replication attempt 5.
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1179): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 5
,I/PowerManagerService( 1019): [PWL] Off : 105s ago
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5466): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5466): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5466): [1] 5.onFinished: Giving up after 6 failures.
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 6
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1663): Vacuum at: now=1453831063504 tag=VacuumService
,I/GoogleURLConnFactory( 1663): Using platform SSLCertificateSocketFactory
,W/Uploader( 1663): No account for auth token provided
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1663): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1663): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1663): (HTTPLog)-Static: isShipBuild true
I/System.out( 1663): (HTTPLog)-Thread-191-482271153: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1663): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10011
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/System.out( 1663): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1663): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1663, getuid(): 10011
,I/PowerManagerService( 1019): [PWL] Off : 140s ago
I/PowerManagerService( 1019): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1019): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10011, pid=1663, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=193)
,I/qtaguid ( 1663): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1663, getuid(): 10011
,W/Uploader( 1663): No account for auth token provided
,I/System.out( 1663): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1663): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1663, getuid(): 10011
,W/Uploader( 1663): No account for auth token provided
,I/System.out( 1663): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1663): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1663, getuid(): 10011
,W/Uploader( 1663): No account for auth token provided
,I/System.out( 1663): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1663): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1663, getuid(): 10011
,W/Uploader( 1663):  no longer exists, so no auth token.
,I/System.out( 1663): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1663): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1663, getuid(): 10011
,W/Uploader( 1663): No account for auth token provided
,I/System.out( 1663): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1663): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1663, getuid(): 10011
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1663): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1663): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,E/Uploader( 1663): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1663): 	,at com.google.android.gms.auth.p.d(SourceFile:599),
E/Uploader( 1663): ,	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1663): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1663): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1663): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337),
E/Uploader( 1663): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1663): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1663): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1663): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1663): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
,I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1663): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1663): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1663, getuid(): 10011
D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1663): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/Watchdog( 1019): !@Sync 7,
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/PowerManagerService( 1019): [PWL] Off : 180s ago,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1019): !@Sync 8
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1179): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,I/BooksSync( 6142): Starting books sync for 61035162, extras: ade
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 44736(2MB) AllocSpace objects, 63(1017KB) LOS objects, 33% free, 23MB/35MB, paused 2.510ms total 148.584ms
,I/BooksConfig( 6142): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6142): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6142): Soft error
E/BooksSync( 6142): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6142): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6142): Sync error
E/BooksSync( 6142): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6142): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6142): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 273320, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1179): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 9
,I/PowerManagerService( 1019): [PWL] Off : 225s ago
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1179): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/SMD     (  291): DCD OFF,
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1019): initializing...,
I/TLC_TIMA_PKM_initialize( 1019): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1019): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1019): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1019): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1019): Trustlet response is completed
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 10
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1019): [PWL] Off : 275s ago,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1019): waitForAlarm result :8
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 11
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1663): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1663): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1663): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1663): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1663): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1663): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1663): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 5466): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5466): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5466): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5466): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5466): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5466): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5466): 	at android.os.Binder.execTransact(Binder.java:461)
D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
,D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,W/System  ( 5466): Ignoring header User-Agent because its value was null.
,I/System.out( 5466): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5466): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5466): (HTTPLog)-Static: isShipBuild true
I/System.out( 5466): (HTTPLog)-Thread-933-937995970: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5466): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10026
,I/System.out( 5466): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1179): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 12
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1179): level :100 plugged : 2
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 13
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 14
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 390s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 15
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/bootchecker(  321): bootchecker wake up!!,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 16
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1179): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6142): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6142): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6142): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6142): Soft error
E/BooksSync( 6142): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6142): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6142): Sync error
E/BooksSync( 6142): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6142): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6142): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 516614, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 455s ago
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 17
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SViewCoverWidget( 1179): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 18
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1019): waitForAlarm result :8,
,E/SMD     (  291): DCD OFF
,I/Atfwd_Daemon(  325): Stop the daemon....,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 19
,I/PowerManagerService( 1019): [PWL] Off : 525s ago
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 20
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 21
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 600s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 22
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 23
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1019): !@Sync 24
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 680s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1019): !@Sync 25
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1019): !@Sync 26
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 27
,I/PowerManagerService( 1019): [PWL] Off : 765s ago
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1019): !@Sync 28
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1019): !@Sync 29
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,E/SMD     (  291): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1019): !@Sync 30
,I/PowerManagerService( 1019): [PWL] Off : 855s ago
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GCM     ( 1663): Message class com.google.f.a.a.i
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1179): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1019): !@Sync 31
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1019): !@Sync 32
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1179): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6142): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6142): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1663): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1663): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1663): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1663): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1663): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6142): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6142): Soft error
E/BooksSync( 6142): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6142): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6142): Sync error
E/BooksSync( 6142): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6142): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6142): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1002559, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1019): !@Sync 33
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 950s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1019): waitForAlarm result :4
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1019): !@Sync 34
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 35,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 36
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1019): [PWL] Off : 1051s ago
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 37
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 38
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 39
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1019): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1019): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1019): Updating Usage Statistics in DB @ 1453832076136
,I/ApplicationPolicy( 1019): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1019): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1019): ::isTableExists: Table exists 
,I/ApplicationUsage( 1019): Done Updating Usage Statistics in DB @ 1453832076494
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1019): !@Sync 40
,I/PowerManagerService( 1019): [PWL] Off : 1156s ago,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1019): !@Sync 41
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 42
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 43
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1266s ago
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1019): !@Sync 44
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6819): 
D/AndroidRuntime( 6819): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6819): CheckJNI is OFF
D/AndroidRuntime( 6819): readGMSProperty: start
D/AndroidRuntime( 6819): readGMSProperty: already setted!!
D/AndroidRuntime( 6819): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6819): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6819): readGMSProperty: end
D/AndroidRuntime( 6819): addProductProperty: start
E/AffinityControl( 6819): AffinityControl: registerfunction enter
D/AndroidRuntime( 6819): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1019): START PACKAGE DELETE: observer{525025929}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1019): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 6225:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1019): Skipping PackageSetting{1ac5b8ac com.example.hello/10346} due to missing metadata
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
I/art     ( 4045): Explicit concurrent mark sweep GC freed 2539(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 671us total 22.824ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/art     ( 6080): Explicit concurrent mark sweep GC freed 108(16KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 713us total 38.840ms
E/SamsungIME( 1860): mOCRHelper is null
W/GeofencerStateMachine( 1834): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.123: ( 3687): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 26 19:17:07 GMT+01:00 2016
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3687): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1019): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1019): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1019): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3687): KLMSIntentService(): onCreate()
E/Zygote  ( 6834): MountEmulatedStorage()
E/Zygote  ( 6834): v2
I/libpersona( 6834): KNOX_SDCARD checking this for 10090
I/libpersona( 6834): KNOX_SDCARD not a persona
I/SELinux ( 6834): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6834 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3687): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/SELinux ( 6834): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6834): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3687): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
I/KLMS-2.5.123: ( 3687): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/TimaKeyStoreProvider( 6834): TimaSignature is unavailable
D/ActivityThread( 6834): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3687): KLMSIntentService(): PACKAGE_REMOVED
D/RegisteredServicesCache( 1458): empty dynamic service
I/art     ( 1019): Explicit concurrent mark sweep GC freed 30998(3MB) AllocSpace objects, 129(2MB) LOS objects, 33% free, 23MB/35MB, paused 2.835ms total 173.294ms
I/art     ( 1019): WaitForGcToComplete blocked for 126.078ms for cause Explicit
I/KLMS-2.5.123: ( 3687): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3687): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/RCPManagerService( 1019): PackageReceiver onReceive()
I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:15121( 6834): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 6834): ELMEngine.ELMEngine( context ).
I/KLMS-2.5.123: ( 3687): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3687): KLMSIntentService(): onDestroy()
D/elm:15121( 6834): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 6834): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10338
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/elm:15121( 6834): ElmAgentService : onCreate()
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10338
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
D/elm:15121( 6834): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/TaskPersister( 1019): removeObsoleteFile: deleting file=20_task.xml
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
D/elm:15121( 6834): MainReceiver.listeningToPackageRemoved()
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/elm:15121( 6834): MDMBridge.getInstance()
D/elm:15121( 6834): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 6834): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 6834): ElmAgentService : onDestroy().
I/PCWCLIENTTRACE_PushUtil( 5792): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5792): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5792): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5792): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5948): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5948): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/art     ( 1019): Explicit concurrent mark sweep GC freed 12330(675KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 3.536ms total 204.226ms
I/PackagesMonitor( 5072): PackagesMonitor onReceive :com.test.thalitest
D/Mms/FreeMessageStatusReceiver( 5746): onReceive, action : android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1019): enable value -1
I/TactileAssist( 1019): internal enable value -1
I/TactileAssist( 1019): intensity value -1
I/TactileAssist( 1019): saveAppList value true
D/PackageManager( 1019): delete codoeFile: 
I/TactileAssist( 1019): List of disabled apps :
D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1019): UID=10338 Target=com.test.thalitest
D/PackageManager( 1019): result of delete: 1{525025929}
D/Mms/FreeMessageReceiverService( 5746): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5746): onHandleIntent: ACTION_PACKAGE_REMOVED
D/AndroidRuntime( 6819): Shutting down VM
D/Compatibility( 5964): onReceive() it will make start service
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5964): onHandleIntent()
D/Compatibility( 5964): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10338, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5964): found: 2
D/Compatibility( 5964): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5964): skipping ResolveInfo{134e907f com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5964): considering ResolveInfo{29b4684c com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5964): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5964): enabling receiver ResolveInfo{305fc095 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/Zygote  ( 6854): MountEmulatedStorage()
I/libpersona( 6854): KNOX_SDCARD checking this for 10055
E/Zygote  ( 6854): v2
I/libpersona( 6854): KNOX_SDCARD not a persona
I/SELinux ( 6854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6854 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/Compatibility( 5964): enabling receiver ResolveInfo{db095aa com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/SELinux ( 6854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6854): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5964): enabling receiver ResolveInfo{d45b59b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5964): enabling receiver ResolveInfo{34e5bd38 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5964): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 6854): TimaSignature is unavailable
D/ActivityThread( 6854): Added TimaKeyStore provider
D/UserAnalysis.PlaceProvider( 6854): PlaceProvider onCreate()
D/UserAnalysis.SecureDbManager( 6854): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6854): SecurePlaceDbHelper() 
D/UserAnalysis( 6854): Create SecureDbHelper
D/IntelligenceServiceApplication( 6854): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6854): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/ContextImpl( 5990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/IntelligenceServiceApplication( 6854): no applications having user consent for prediction
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetection::stopService] Service stopped.
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/Zygote  ( 6871): MountEmulatedStorage()
E/Zygote  ( 6871): v2
I/libpersona( 6871): KNOX_SDCARD checking this for 1000
I/libpersona( 6871): KNOX_SDCARD not a persona
I/SELinux ( 6871): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6871): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6871 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 6871): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 5293:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
D/TimaKeyStoreProvider( 6871): TimaSignature is unavailable
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
D/ActivityThread( 6871): Added TimaKeyStore provider
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
D/BluetoothAdapter( 6854): cancelDiscovery
D/BluetoothAdapterProperties( 2630): mDiscovering is false
E/BluetoothAdapterService( 2630): This is not a scanning status. cancelDiscovery() will be not called.
W/ResourcesManager( 6871): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/BluetoothAdapter( 6854): cancelDiscovery = true
V/PlaceDetection v1.0.19 ( 6854): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 6854): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/Watchdog( 1019): !@Sync 45
W/art     ( 6819): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/RCPManager( 6871):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1019):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1019): queryAllProviders():  providerCallBack is not register for 0
D/FilterInstaller( 6006): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
W/ContextImpl( 6006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/FilterInstaller( 6006): FilterPackageService : ACTION_PACKAGE_REMOVED
I/FilterInstaller( 6006): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 6006): before removeFromFS
E/Zygote  ( 6887): MountEmulatedStorage()
E/Zygote  ( 6887): v2
I/libpersona( 6887): KNOX_SDCARD checking this for 1000
I/libpersona( 6887): KNOX_SDCARD not a persona
I/SELinux ( 6887): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6887 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6887): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6887): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6903): MountEmulatedStorage()
I/libpersona( 6903): KNOX_SDCARD checking this for 10095
E/Zygote  ( 6903): v2
I/libpersona( 6903): KNOX_SDCARD not a persona
I/SELinux ( 6903): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 6887): TimaSignature is unavailable
D/ActivityThread( 6887): Added TimaKeyStore provider
I/ActivityManager( 1019): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6903 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 6903): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6903): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6903): TimaSignature is unavailable
D/ActivityThread( 6903): Added TimaKeyStore provider
D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1019): no available spell checker services found
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteLog( 6887): (28) failed to open "/data/data/com.samsung.helphub/databases/search.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6887): Failed to open database '/data/data/com.samsung.helphub/databases/search.db'.
E/SQLiteDatabase( 6887): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6887): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6887): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6887): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6887): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6887): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6887): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6887): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6887): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6887): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6887): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteDatabase( 6887): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 6887): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 6887): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6887): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6887): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6887): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6887): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6887): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6887): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6887): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6887): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6887): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6887): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6887): Couldn't open search.db for writing (will try read-only):
E/SQLiteOpenHelper( 6887): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6887): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6887): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6887): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6887): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6887): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6887): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6887): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6887): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6887): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6887): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteOpenHelper( 6887): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 6887): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 6887): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 6887): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 6887): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 6887): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6887): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6887): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6887): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6887): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6887): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6887): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6887): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 6887): Opened search.db in read-only mode
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PreloadFilterInstaller( 6903): uses FILTER_DB_VER_1
E/SQLiteLog( 6903): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6903): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6903): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6903): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6903): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6903): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6903): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6903): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6903): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6903): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6903): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6903): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6903): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6903): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6903): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6903): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6903): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteDatabase( 6903): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteDatabase( 6903): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteDatabase( 6903): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteDatabase( 6903): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 6903): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 6903): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6903): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6903): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6903): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6903): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6903): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6903): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6903): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6903): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6903): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 6903): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6903): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6903): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6903): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6903): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6903): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6903): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6903): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6903): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6903): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6903): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6903): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6903): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6903): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6903): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteOpenHelper( 6903): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteOpenHelper( 6903): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteOpenHelper( 6903): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteOpenHelper( 6903): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 6903): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 6903): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 6903): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 6903): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 6903): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6903): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6903): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6903): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6903): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6903): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 6903): Opened filter.db in read-only mode
E/SQLiteLog( 6903): (284) automatic index on titles(filter_id)
E/Zygote  ( 6919): MountEmulatedStorage()
I/libpersona( 6919): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6919): v2
I/libpersona( 6919): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6919 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a

```
