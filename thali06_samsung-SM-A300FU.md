#### Test 573480789efee08_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  290): DCD OFF
,D/AndroidRuntime( 6154): 
D/AndroidRuntime( 6154): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6154): CheckJNI is OFF
D/AndroidRuntime( 6154): readGMSProperty: start
D/AndroidRuntime( 6154): readGMSProperty: already setted!!
D/AndroidRuntime( 6154): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6154): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6154): readGMSProperty: end
D/AndroidRuntime( 6154): addProductProperty: start
E/AffinityControl( 6154): AffinityControl: registerfunction enter
D/AndroidRuntime( 6154): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/Zygote  ( 6167): MountEmulatedStorage()
E/Zygote  ( 6167): v2
I/libpersona( 6167): KNOX_SDCARD checking this for 10338
I/libpersona( 6167): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6167 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6167): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1481
D/AndroidRuntime( 6154): Shutting down VM
I/SELinux ( 6167): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6167): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, uhalitest
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6167): TimaSignature is unavailable
D/ActivityThread( 6167): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1018): Display changed displayId=0
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1481): updateVisibility : ActivityRecord{11777c95 token=android.os.BinderProxy@287fd6fc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1481): onTrimMemory. Level: 20
I/WebViewFactory( 6167): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6167): Time to load native libraries: 1 ms (timestamps 2177-2178)
I/LibraryLoader( 6167): Expected native library version number "",actual native library version number ""
W/art     ( 6154): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6167): Binding Chromium to main looper Looper (main, tid 1) {3e6d6d24}
I/LibraryLoader( 6167): Expected native library version number "",actual native library version number ""
I/chromium( 6167): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6167): Initializing chromium process, singleProcess=true
W/art     ( 6167): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6167): ApplicationContext is null in ApplicationStatus
W/chromium( 6167): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6167): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6167): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6167): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6167): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6167): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6167): Local Branch: 
I/Adreno-EGL( 6167): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6167): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6167):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/art     ( 6167): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6167): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6167): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6167): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6167): CordovaWebView is running on device made by: samsung
W/art     ( 6167): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6167): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{5100e1d u0 com.test.thalitest/.MainActivity t20}
D/OpenGLRenderer( 6167): Render dirty regions requested: true
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
W/chromium( 6167): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6167): updateVisibility : ActivityRecord{6ded5f9 token=android.os.BinderProxy@12aae643 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6167): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6167): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1018): Focus entered window: 6167
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6167): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6167): Initialized EGL, version 1.4
D/OpenGLRenderer( 6167): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6167): Enabling debug mode 0
D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
W/IInputConnectionWrapper( 6167): showStatusIcon on inactive InputConnection
I/Timeline( 6167): Timeline: Activity_idle id: android.os.BinderProxy@12aae643 time:152714
I/ActivityManager( 1018): Displayed Component not be shown by security: +685ms (total +36s675ms)
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{5100e1d u0 com.test.thalitest/.MainActivity t20} time:152723
I/SurfaceFlinger(  259): id=13 Removed uhalitest (7/9)
I/SurfaceFlinger(  259): id=13 Removed uhalitest (-2/9)
V/AlarmManager( 1018): waitForAlarm result :4
I/SamsungIME( 1800): getCurrentCandidateView
I/BooksSync( 6085): Starting books sync for 61035162, extras: ade
D/SamsungIME( 1800): Dismiss ExpandCandiate
I/BooksConfig( 6085): GmsCore Version = 7.8.99 (2134222-434)
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/BindingManager( 6167): Cannot call determinedVisibility() - never saw a connection for the pid: 6167
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/SamsungIME( 1800): getDebugLevel  : 0x4f4c
D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/StatusBar( 1189): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1189): isKioskContainerExistOnDevice
D/PersonaManager( 1189): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1189): Icon Only
I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1189): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1189): Icon Only
I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/SamsungIME( 1800): getDebugLevel  : 0x4f4c
I/SamsungIME( 1800): KeybaordView init() : load resources
I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/BooksAccountManager( 6085): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
I/SamsungIME( 1800): getCurrentKeyboard
I/SamsungIME( 1800): getTextKeyboard
E/BooksSync( 6085): Soft error
E/BooksSync( 6085): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6085): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6085): Sync error
E/BooksSync( 6085): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6085): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6085): Finished books sync
D/PanelView( 1189): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 152748, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/SamsungIME( 1800): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 6167): Set native->JS mode to OnlineEventsBridgeMode
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
D/jxcore_app_log( 6167): JniHelper::setJavaVM(0xb8480448), pthread_self() = -1197626416
,I/chromium( 6167): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  290): DCD OFF
,W/jxcore-log( 6167): Initializing JXcore engine
,W/jxcore-log( 6167): JXcore engine is ready
,E/audit   ( 1833): type=1400 msg=audit(1453981635.937:205): avc:  denied  { ioctl } for  pid=6216 comm="Thread-1056" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
E/audit   ( 1833):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1833): type=1300 msg=audit(1453981635.937:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9ee008f8 items=0 ppid=311 ppcomm=main pid=6216 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm="Thread-1056" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1833): type=1320 msg=audit(1453981635.937:205): 
,W/jxcore-log( 6167): Starting JXcore engine,
,W/jxcore-log( 6167): Platform android
W/jxcore-log( 6167): 
,W/jxcore-log( 6167): Process ARCH arm
W/jxcore-log( 6167): 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6167): JXcore Cordova bridge is ready!
I/jxcore-log( 6167): 
W/jxcore-log( 6167): JXcore engine is started
E/jxcore  ( 6167): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6167): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
I/chromium( 6167): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
D/FocusedStackFrame( 1018): Set to : 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 6167
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1018): Killing 4149:com.sec.spp.push/u0a32 (adj 15): empty #31
W/PluginManager( 6167): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
I/SurfaceFlinger(  259): id=14 Removed NainActivit (6/8)
I/SurfaceFlinger(  259): id=14 Removed NainActivit (-2/8)
W/ActivityManager( 1018): mDVFSHelper.acquire()
V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/Launcher( 1481): onRestart, Launcher: 563445902
D/Launcher( 1481): onStart, Launcher: 563445902
D/Launcher.HomeView( 1481): onStart
D/Launcher( 1481): onResume, Launcher: 563445902
D/SettingsProvider( 1018): name = kids_home_mode
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10006
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/Launcher.HomeView( 1481): onResume
D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/MenuAppsGridFragment( 1481): onResume
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
D/ActivityManager( 1018): handle home activity for 0
I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
I/splitIntent( 1018): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
D/Launcher.HomeView( 1481): onPause
I/splitIntent( 1018): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/GalleryCacheReady( 4988): Receive : home resume
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
D/Recents_RecreateReceiver( 2536): onReceive by home
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
V/TaskCloserActivity( 5645): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
D/Mms/UIEventReceiver( 5680): ui event
I/SurfaceFlinger(  259): id=15 createSurf (540x960),1 flag=4, Mauncher
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/InputDispatcher( 1018): Focus entered window: 1481
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1481): log_dcs ThreadedRenderer::initialize entered! 
W/BroadcastQueue( 1018): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
I/splitIntent( 1018): Queue : backgroundsplit_0 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
V/ActivityThread( 1481): updateVisibility : ActivityRecord{11777c95 token=android.os.BinderProxy@287fd6fc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1481): onStop
D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
V/TaskCloserActivity( 5645): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/SamsungIME( 1800): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
I/StatusBar( 1189): Icon Only
W/IInputConnectionWrapper( 6167): showStatusIcon on inactive InputConnection
D/PanelView( 1189): There is/are notification(s) 
I/Timeline( 1481): Timeline: Activity_idle id: android.os.BinderProxy@287fd6fc time:155628
W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{181d4bcb u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:155648
W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_4149/cgroup.procs: No such file or directory
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,I/PowerManagerService( 1018): [PWL] Off : 50s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5383): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5383): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5383): [1] 5.onFinished: Scheduling replication attempt 5.
,E/Watchdog( 1018): !@Sync 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4,
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5383): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5383): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5383): [1] 5.onFinished: Giving up after 6 failures.
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 75s ago
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 6
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1189): handleTimeUpdate
,D/SecKeyguardClockView( 1189): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1189): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1189): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1189): *** don't update sliding image ***
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1189): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1688): Vacuum at: now=1453981685065 tag=VacuumService
,I/GoogleURLConnFactory( 1688): Using platform SSLCertificateSocketFactory
,W/Uploader( 1688): No account for auth token provided
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1688): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1688): (HTTPLog)-Static: isShipBuild true
I/System.out( 1688): (HTTPLog)-Thread-189-273104703: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,I/System.out( 1688): KnoxVpnUidStorageknoxVpnSupported API value returned is false,
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
,E/SMD     (  290): DCD OFF
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 43610(2MB) AllocSpace objects, 38(612KB) LOS objects, 33% free, 23MB/35MB, paused 2.473ms total 150.620ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1189): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
D/PersonaManager( 1189): isKioskContainerExistOnDevice
D/PersonaManager( 1189): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1189): Icon Only
,I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1189): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1189): Icon Only
I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1688): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1688): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1688): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1688): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1688): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1688): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1688): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1688): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1688): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1688): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1688): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1688): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1688): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,D/PanelView( 1189): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1688): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1688): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1688): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1688): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1688): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1688): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1688): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1688): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1688): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1688): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1688): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1688): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1688): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1189): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1189): Icon Only
,I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
,D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1189): Icon Only
I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
,D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1189): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1688): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 105s ago,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/Watchdog( 1018): !@Sync 7,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 140s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 8,
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1189): handleTimeUpdate
,D/SecKeyguardClockView( 1189): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1189): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1189): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1189): *** don't update sliding image ***
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1189): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6085): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6085): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1189): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
D/PersonaManager( 1189): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1189): Icon Only
I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1189): Icon Only
I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6085): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6085): Soft error
E/BooksSync( 6085): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6085): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6085): Sync error
E/BooksSync( 6085): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6085): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6085): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 279197, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1189): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): stay LED for fully charged
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 9,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1018): initializing...,
,I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 10
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1018): [PWL] Off : 225s ago,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1189): handleTimeUpdate
,D/SecKeyguardClockView( 1189): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1189): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1189): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1189): *** don't update sliding image ***
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6311): MountEmulatedStorage()
E/Zygote  ( 6311): v2
I/libpersona( 6311): KNOX_SDCARD checking this for 10161,
I/libpersona( 6311): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6311 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6311): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1189): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/TimaKeyStoreProvider( 6311): TimaSignature is unavailable
,D/ActivityThread( 6311): Added TimaKeyStore provider
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,W/ResourcesManager( 6311): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6311): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6311): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6311): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6311): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39f99649: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6311): Installed default security provider GmsCore_OpenSSL
,E/SMD     (  290): DCD OFF
,I/dex2oat ( 6337): ----------------------------------------------------
I/dex2oat ( 6337): <SS>: S T A R T I N G . . .
I/dex2oat ( 6337): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 6337): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1173280535.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1173280535.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/YouTube MDX( 6311): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 6337): dex2oat took 77.601ms (threads: 4)
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6311): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6311): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6311): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6311): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/InstanceID/Rpc( 6311): Found 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6311): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/AndroidHttpClient( 6311): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,D/AndroidHttpClient( 6311): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 6311): Thread-1098(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6311): Thread-1098(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6311): Thread-1098(ApacheHTTPLog):isShipBuild true
I/System.out( 6311): Thread-1098(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 6311): Thread-1098(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/System.out( 6311): Thread-1098 calls detatch()
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,E/Watchdog( 1018): !@Sync 11,
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager( 1018): Killing 5211:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1189): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
D/PersonaManager( 1189): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1189): Icon Only
I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1189): Icon Only
,I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,W/GLSActivity( 1688): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1688): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1688): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1688): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1688): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1688): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1688): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 5383): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5383): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5383): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5383): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5383): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5383): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5383): 	at android.os.Binder.execTransact(Binder.java:461)
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5211/cgroup.procs: No such file or directory
,W/System  ( 5383): Ignoring header User-Agent because its value was null.
,I/System.out( 5383): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5383): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5383): (HTTPLog)-Static: isShipBuild true
,I/System.out( 5383): (HTTPLog)-Thread-903-597078631: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5383): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10026
,I/System.out( 5383): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1189): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 12
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 13
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1189): handleTimeUpdate
,D/SecKeyguardClockView( 1189): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1189): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1189): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1189): *** don't update sliding image ***
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1189): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 14
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 330s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 15
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/bootchecker(  316): bootchecker wake up!!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 16,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1018): [PWL] Off : 390s ago
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 17
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1189): handleTimeUpdate
,D/SecKeyguardClockView( 1189): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1189): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1189): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1189): *** don't update sliding image ***
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6085): Starting books sync for 61035162, extras: ade
,D/SViewCoverWidget( 1189): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6085): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1189): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1189): Icon Only
I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1189): Icon Only
,I/StatusBar( 1189): Icon Only
,D/PanelView( 1189): There is/are notification(s) 
,D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6085): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6085): Soft error
E/BooksSync( 6085): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6085): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6085): Sync error
E/BooksSync( 6085): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6085): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6085): Finished books sync
,D/PanelView( 1189): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 531923, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 18,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1018): stay LED for fully charged
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 1189): handleTimeUpdate
D/SecKeyguardClockView( 1189): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1189): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1189): onReceive action : android.intent.action.TIME_TICK,
I/KeyguardEffectViewController( 1189): *** don't update sliding image ***
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1189): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 455s ago
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/Atfwd_Daemon(  319): Stop the daemon....,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 19,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 20
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 525s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 21
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 22
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate,
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 23
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 600s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 24
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 25
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 680s ago
,E/Watchdog( 1018): !@Sync 26,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 27,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 28,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,I/PowerManagerService( 1018): [PWL] Off : 765s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 29,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1018): !@Sync 30,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1189): handleTimeUpdate
,D/SecKeyguardClockView( 1189): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1189): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1189): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1189): *** don't update sliding image ***
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SViewCoverWidget( 1189): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/GCM     ( 1688): Message class com.google.f.a.a.i
,I/EventLogService( 2035): Aggregate from 1453979996624 (log), 1453979996624 (data)
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 31
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,I/PowerManagerService( 1018): [PWL] Off : 855s ago,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 32
,V/AlarmManager( 1018): waitForAlarm result :8
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 33
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1189): handleTimeUpdate
,D/SecKeyguardClockView( 1189): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1189): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1189): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1189): *** don't update sliding image ***
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1189): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6085): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6085): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1189): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
D/PersonaManager( 1189): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1189): Icon Only
I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1189): Icon Only
I/StatusBar( 1189): Icon Only
D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6085): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6085): Soft error
E/BooksSync( 6085): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6085): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6085): Sync error
E/BooksSync( 6085): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6085): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6085): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1037045, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1189): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,E/Watchdog( 1018): !@Sync 34
,V/AlarmManager( 1018): waitForAlarm result :8
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 950s ago,
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1189): handleTimeUpdate
,D/SecKeyguardClockView( 1189): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1189): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1189): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1189): *** don't update sliding image ***
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1189): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 1018): !@Sync 35,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 36
,V/AlarmManager( 1018): waitForAlarm result :8
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 37,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 38
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1050s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 39
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1018): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1018): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1018): Updating Usage Statistics in DB @ 1453982696609
,I/ApplicationPolicy( 1018): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1018): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1018): ::isTableExists: Table exists 
,I/ApplicationUsage( 1018): Done Updating Usage Statistics in DB @ 1453982697012
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 40
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 41,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1155s ago
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1189): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1189): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 42
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 43
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 44
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6822): 
D/AndroidRuntime( 6822): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6822): CheckJNI is OFF
D/AndroidRuntime( 6822): readGMSProperty: start
D/AndroidRuntime( 6822): readGMSProperty: already setted!!
D/AndroidRuntime( 6822): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6822): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6822): readGMSProperty: end
D/AndroidRuntime( 6822): addProductProperty: start
E/AffinityControl( 6822): AffinityControl: registerfunction enter
D/AndroidRuntime( 6822): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{803008867}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): !@killApplicatoin: 10338, uninstall pkg
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 6167:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1018): Skipping PackageSetting{19056525 com.example.hello/10346} due to missing metadata
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
E/SMD     (  290): DCD OFF
I/art     ( 3992): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 1.331ms total 47.156ms
I/art     ( 6018): Explicit concurrent mark sweep GC freed 108(16KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 1.195ms total 63.301ms
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1800): mOCRHelper is null
W/GeofencerStateMachine( 1767): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.123: ( 3650): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 28 13:07:28 GMT+01:00 2016
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3650): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3650): KLMSIntentService(): onCreate()
I/libpersona( 6836): KNOX_SDCARD checking this for 10090
I/KLMS-2.5.123: ( 3650): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/libpersona( 6836): KNOX_SDCARD not a persona
E/Zygote  ( 6836): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6836 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 6836): v2
I/SELinux ( 6836): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6836): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6836): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3650): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/RegisteredServicesCache( 1443): empty dynamic service
I/KLMS-2.5.123: ( 3650): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/TimaKeyStoreProvider( 6836): TimaSignature is unavailable
I/KLMS-2.5.123: ( 3650): KLMSIntentService(): PACKAGE_REMOVED
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
D/ActivityThread( 6836): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3650): KLMSIntentService(): listeningToPackageRemoved().START
I/art     ( 1018): Explicit concurrent mark sweep GC freed 45945(4MB) AllocSpace objects, 173(2MB) LOS objects, 33% free, 24MB/36MB, paused 2.734ms total 222.311ms
I/KLMS-2.5.123: ( 3650): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/art     ( 1018): WaitForGcToComplete blocked for 130.196ms for cause Explicit
D/elm:15121( 6836): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 6836): ELMEngine.ELMEngine( context ).
D/elm:15121( 6836): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 6836): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 6836): ElmAgentService : onCreate()
D/elm:15121( 6836): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6836): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6836): MDMBridge.getInstance()
D/elm:15121( 6836): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 6836): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.123: ( 3650): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3650): KLMSIntentService(): onDestroy()
D/RCPManagerService( 1018): PackageReceiver onReceive()
D/elm:15121( 6836): ElmAgentService : onDestroy().
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10338
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10338
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
D/TaskPersister( 1018): removeObsoleteFile: deleting file=20_task.xml
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
I/PCWCLIENTTRACE_PushUtil( 5728): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5728): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5728): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5728): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5801): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5801): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/art     ( 1018): Explicit concurrent mark sweep GC freed 12435(624KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 6.850ms total 188.877ms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 4988): PackagesMonitor onReceive :com.test.thalitest
D/PackageManager( 1018): delete codoeFile: 
I/AASA_removePackage( 1018): UID=10338 Target=com.test.thalitest
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
D/Mms/FreeMessageStatusReceiver( 5680): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/PackageManager( 1018): result of delete: 1{803008867}
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1018): enable value -1
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
D/Mms/FreeMessageReceiverService( 5680): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5680): onHandleIntent: ACTION_PACKAGE_REMOVED
D/AndroidRuntime( 6822): Shutting down VM
I/TactileAssist( 1018): List of disabled apps :
D/Compatibility( 5904): onReceive() it will make start service
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5904): onHandleIntent()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5904): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10338, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5904): found: 2
D/Compatibility( 5904): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5904): skipping ResolveInfo{ba63790 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5904): considering ResolveInfo{2413b889 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5904): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5904): enabling receiver ResolveInfo{2195808e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/Zygote  ( 6856): MountEmulatedStorage()
I/libpersona( 6856): KNOX_SDCARD checking this for 10055
E/Zygote  ( 6856): v2
I/libpersona( 6856): KNOX_SDCARD not a persona
I/SELinux ( 6856): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/Compatibility( 5904): enabling receiver ResolveInfo{15a730af com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/SELinux ( 6856): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6856): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6856 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
D/Compatibility( 5904): enabling receiver ResolveInfo{3f5f3cbc com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5904): enabling receiver ResolveInfo{35765445 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/TimaKeyStoreProvider( 6856): TimaSignature is unavailable
D/Compatibility( 5904): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/ActivityThread( 6856): Added TimaKeyStore provider
I/art     (  311): Explicit concurrent mark sweep GC freed 8681(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 24.491ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.624ms
D/UserAnalysis.PlaceProvider( 6856): PlaceProvider onCreate()
D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.671ms
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UserAnalysis.SecureDbManager( 6856): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6856): SecurePlaceDbHelper() 
D/UserAnalysis( 6856): Create SecureDbHelper
D/IntelligenceServiceApplication( 6856): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6856): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/ContextImpl( 5928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/IntelligenceServiceApplication( 6856): no applications having user consent for prediction
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetection::stopService] Service stopped.
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/Zygote  ( 6873): MountEmulatedStorage()
E/Zygote  ( 6873): v2
I/libpersona( 6873): KNOX_SDCARD checking this for 1000
I/libpersona( 6873): KNOX_SDCARD not a persona
I/SELinux ( 6873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6873): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6873 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5688:com.samsung.helphub/1000 (adj 15): empty #31
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
D/TimaKeyStoreProvider( 6873): TimaSignature is unavailable
D/ActivityThread( 6873): Added TimaKeyStore provider
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
W/art     ( 6822): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
W/ResourcesManager( 6873): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/BluetoothAdapter( 6856): cancelDiscovery
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/BluetoothAdapterProperties( 2634): mDiscovering is false
E/BluetoothAdapterService( 2634): This is not a scanning status. cancelDiscovery() will be not called.
D/BluetoothAdapter( 6856): cancelDiscovery = true
V/PlaceDetection v1.0.19 ( 6856): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 6856): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManager( 6873):  in createShortcut() for packageName: com.test.thalitest userId0
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManagerService( 1018):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1018): queryAllProviders():  providerCallBack is not register for 0
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/FilterInstaller( 5945): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/ContextImpl( 5945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/FilterInstaller( 5945): FilterPackageService : ACTION_PACKAGE_REMOVED
E/SQLiteLog( 6856): (10) unixWrite() File Descriptor : 25 gets errno : 9
E/SQLiteLog( 6856): (10) unixWrite() File Descriptor : 25 gets errno : 9
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/FilterInstaller( 5945): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5945): before removeFromFS
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
E/SQLiteDatabase( 6856): Error inserting timestamp=1453982848699 message=Predictor: service is stopped by Application.onCreate
E/SQLiteDatabase( 6856): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 6856): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6856): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6856): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6856): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6856): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6856): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6856): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
E/SQLiteDatabase( 6856): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 6856): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6856): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6856): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6856): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6856): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6856): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6856): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6856): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 6856): It failed to insert to dump_log table
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5688/cgroup.procs: No such file or directory
I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
E/SQLiteLog( 6856): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6856): (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
E/SQLiteDatabase( 6856): Error inserting timestamp=1453982848782 message=Predictor: service stopped by removePlaceCategories()
E/SQLiteDatabase( 6856): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6856): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6856): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6856): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6856): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6856): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6856): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6856): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
E/SQLiteDatabase( 6856): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 6856): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6856): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6856): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6856): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6856): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6856): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6856): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6856): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 6856): It failed to insert to dump_log table
E/Zygote  ( 6891): MountEmulatedStorage()
I/libpersona( 6891): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6891): v2
I/libpersona( 6891): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6891 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/SELinux ( 6891): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6891): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6891): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Zygote  ( 6903): MountEmulatedStorage()
E/Zygote  ( 6903): v2
I/libpersona( 6903): KNOX_SDCARD checking this for 10095
I/libpersona( 6903): KNOX_SDCARD not a persona
I/SELinux ( 6903): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6903 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 6903): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6903): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6891): TimaSignature is unavailable
D/ActivityThread( 6891): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 6903): TimaSignature is unavailable
E/Watchdog( 1018): !@Sync 45
D/ActivityThread( 6903): Added TimaKeyStore provider

```
