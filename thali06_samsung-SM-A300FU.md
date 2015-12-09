#### Test 5065027873d6a28_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
I/PowerManagerService( 1020): [PWL] Off : 75s ago
,--------- beginning of main
D/AndroidRuntime( 6093): 
D/AndroidRuntime( 6093): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6093): CheckJNI is OFF
D/AndroidRuntime( 6093): readGMSProperty: start
D/AndroidRuntime( 6093): readGMSProperty: already setted!!
D/AndroidRuntime( 6093): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6093): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6093): readGMSProperty: end
D/AndroidRuntime( 6093): addProductProperty: start
E/AffinityControl( 6093): AffinityControl: registerfunction enter
D/AndroidRuntime( 6093): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1020): mDVFSHelper.acquire()
D/FocusedStackFrame( 1020): Set to : 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : 25362712
E/Zygote  ( 6105): MountEmulatedStorage()
E/Zygote  ( 6105): v2
I/libpersona( 6105): KNOX_SDCARD checking this for 10338
I/libpersona( 6105): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6105 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1479
D/AndroidRuntime( 6093): Shutting down VM
I/SELinux ( 6105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
E/SELinux ( 6105): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, uhalitest
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6105): TimaSignature is unavailable
D/ActivityThread( 6105): Added TimaKeyStore provider
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1479): updateVisibility : ActivityRecord{1f9b4bf2 token=android.os.BinderProxy@3d4a751e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1479): onTrimMemory. Level: 20
I/WebViewFactory( 6105): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6105): Time to load native libraries: 1 ms (timestamps 4035-4036)
I/LibraryLoader( 6105): Expected native library version number "",actual native library version number ""
W/art     ( 6093): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6105): Binding Chromium to main looper Looper (main, tid 1) {d53f5eb}
,I/LibraryLoader( 6105): Expected native library version number "",actual native library version number ""
,I/chromium( 6105): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6105): Initializing chromium process, singleProcess=true
,W/art     ( 6105): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6105): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6105): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6105): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6105): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6105): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6105): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6105): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6105): Local Branch: 
I/Adreno-EGL( 6105): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6105): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6105):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/SMD     (  296): DCD OFF
,W/art     ( 6105): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6105): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6105): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6105): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6105): CordovaWebView is running on device made by: samsung
,W/art     ( 6105): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6105): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1020): Activity pause timeout for ActivityRecord{28c2d207 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6105): Render dirty regions requested: true
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,W/chromium( 6105): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6105): updateVisibility : ActivityRecord{14209624 token=android.os.BinderProxy@1a63d1b6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6105): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6105): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1020): Focus entered window: 6105,
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6105): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6105): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6105): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6105): Enabling debug mode 0
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,I/ActivityManager( 1020): Displayed Component not be shown by security: +626ms (total +37s680ms)
,W/ActivityManager( 1020): mDVFSHelper.release()
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{28c2d207 u0 com.test.thalitest/.MainActivity t20} time:154520
,W/IInputConnectionWrapper( 6105): showStatusIcon on inactive InputConnection
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (-2/9)
,I/SamsungIME( 1775): getCurrentCandidateView
,I/Timeline( 6105): Timeline: Activity_idle id: android.os.BinderProxy@1a63d1b6 time:154541
,D/SamsungIME( 1775): Dismiss ExpandCandiate
,I/SamsungIME( 1775): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1775): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1775): KeybaordView init() : load resources
,I/SamsungIME( 1775): getCurrentKeyboard
I/SamsungIME( 1775): getTextKeyboard
,W/BindingManager( 6105): Cannot call determinedVisibility() - never saw a connection for the pid: 6105
,D/SamsungIME( 1775): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6105): Set native->JS mode to OnlineEventsBridgeMode
,V/AlarmManager( 1020): waitForAlarm result :4
,I/BooksSync( 6030): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6030): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/jxcore_app_log( 6105): JniHelper::setJavaVM(0xb7d34448), pthread_self() = -1205285960
,D/JX-Cordova( 6105): jxcore cordova android initializing
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksAccountManager( 6030): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): Soft error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6030): Sync error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6030): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 154909, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,V/AlarmManager( 1020): waitForAlarm result :8
,W/jxcore-log( 6105): Initializing JXcore engine
W/jxcore-log( 6105): JXcore engine is ready
,W/jxcore-log( 6105): Starting JXcore engine
,E/audit   ( 1815): type=1400 msg=audit(1449626640.592:205): avc:  denied  { ioctl } for  pid=6105 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1815):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1815): type=1300 msg=audit(1449626640.592:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=be9b4d58 items=0 ppid=324 ppcomm=main pid=6105 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1815): type=1320 msg=audit(1449626640.592:205): 
,W/jxcore-log( 6105): Platform android
W/jxcore-log( 6105): 
W/jxcore-log( 6105): Process ARCH arm
W/jxcore-log( 6105): 
D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2659): Disconnected process message: 10
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
I/jxcore-log( 6105): JXcore Cordova bridge is ready!
I/jxcore-log( 6105): 
W/jxcore-log( 6105): JXcore engine is started
I/Choreographer( 6105): Skipped 124 frames!  The application may be doing too much work on its main thread.
I/chromium( 6105): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/jxcore  ( 6105): Error!: missing ) after argument list
E/jxcore  ( 6105): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
I/chromium( 6105): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
D/FocusedStackFrame( 1020): Set to : 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 6105
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1020): Killing 5210:com.google.android.gm/u0a99 (adj 15): empty #31
I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
W/ActivityManager( 1020): mDVFSHelper.acquire()
,V/WindowManager( 1020): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1479): onRestart, Launcher: 139471645
,D/Launcher( 1479): onStart, Launcher: 139471645
,D/Launcher.HomeView( 1479): onStart
,D/Launcher( 1479): onResume, Launcher: 139471645
,D/SettingsProvider( 1020): name = kids_home_mode
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10006
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,D/Launcher.HomeView( 1479): onResume
,D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1479): onResume
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,D/WallpaperManager( 1479): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/WallpaperManager( 1479): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1020): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,I/splitIntent( 1020): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/GalleryCacheReady( 4999): Receive : home resume
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,E/SMD     (  296): DCD OFF
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
D/Recents_RecreateReceiver( 2444): onReceive by home
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/ActivityManager( 1020): handle home activity for 0
,I/WallpaperManagerService( 1020): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1020): post home show event for user 0
D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/WallpaperManagerService( 1020):  force update = false; persona id = 0; current user =0; current persona = 0
D/Launcher.HomeView( 1479): onPause
D/KnoxTimeoutHandler( 1020): handleHomeShow for 0 and current 0
,D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 5652): ui event
,V/TaskCloserActivity( 5618): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6159): MountEmulatedStorage()
I/libpersona( 6159): KNOX_SDCARD checking this for 10135
E/Zygote  ( 6159): v2
I/libpersona( 6159): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6159 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 6159): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6159): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6159): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/BroadcastQueue( 1020): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1479, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
I/SurfaceFlinger(  257): id=14 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1020): Focus entered window: 1479
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101,
D/SRIB_DCS( 1479): log_dcs ThreadedRenderer::initialize entered! 
,D/Launcher.HomeView( 1479): onStop
V/ActivityThread( 1479): updateVisibility : ActivityRecord{1f9b4bf2 token=android.os.BinderProxy@3d4a751e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/IInputConnectionWrapper( 6105): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1775): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 6159): TimaSignature is unavailable
,D/ActivityThread( 6159): Added TimaKeyStore provider
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,W/libprocessgroup( 1020): failed to open /acct/uid_10099/pid_5210/cgroup.procs: No such file or directory
,W/ResourcesManager( 6159): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6159): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6159): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6159): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 6159): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/Timeline( 1479): Timeline: Activity_idle id: android.os.BinderProxy@3d4a751e time:157413
,W/ActivityManager( 1020): mDVFSHelper.release()
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{96e9092 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:157437
,I/splitIntent( 1020): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1020): Killing 4172:com.sec.spp.push/u0a32 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 5618): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/PersonaManager( 1020): isKioskContainerExistOnDevice
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_4172/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/Watchdog( 1020): !@Sync 5,
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5371): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5371): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5371): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,I/PowerManagerService( 1020): [PWL] Off : 105s ago
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,V/AlarmManager( 1020): waitForAlarm result :4
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1020): waitForAlarm result :4
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5371): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5371): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5371): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/Watchdog( 1020): !@Sync 6
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1689): Vacuum at: now=1449626689588 tag=VacuumService
,I/GoogleURLConnFactory( 1689): Using platform SSLCertificateSocketFactory
,W/Uploader( 1689): No account for auth token provided
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  296): DCD OFF
,I/System.out( 1689): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1689): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1689): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1689): (HTTPLog)-Thread-193-305891601: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1689): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10011
,I/System.out( 1689): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1689): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1689, getuid(): 10011
,I/qtaguid ( 1689): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1689, getuid(): 10011
,W/Uploader( 1689): No account for auth token provided
,I/System.out( 1689): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1689): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1689, getuid(): 10011
,W/Uploader( 1689): No account for auth token provided
,I/System.out( 1689): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1689): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1689, getuid(): 10011
,W/Uploader( 1689): No account for auth token provided
,I/System.out( 1689): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1689): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1689, getuid(): 10011
,W/Uploader( 1689):  no longer exists, so no auth token.
,I/System.out( 1689): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1689): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1689, getuid(): 10011
,W/Uploader( 1689): No account for auth token provided
,I/System.out( 1689): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1689): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1689, getuid(): 10011
,I/art     ( 1689): Explicit concurrent mark sweep GC freed 43306(2MB) AllocSpace objects, 40(2MB) LOS objects, 39% free, 7MB/13MB, paused 1.266ms total 72.193ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1689): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1689): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1689): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1689): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1689): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1689): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1689): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1689): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1689): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1689): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1689): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1689): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1689): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/System.out( 1689): (HTTPLog)-Static: isSBSettingEnabled false
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
I/qtaguid ( 1689): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1689, getuid(): 10011
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1689): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF,
,I/PowerManagerService( 1020): [PWL] Off : 140s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,E/Watchdog( 1020): !@Sync 7
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1020): [PWL] Off : 180s ago
,E/Watchdog( 1020): !@Sync 8
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167],
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6030): Starting books sync for 61035162, extras: ade
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 47585(2MB) AllocSpace objects, 68(1097KB) LOS objects, 33% free, 23MB/35MB, paused 2.423ms total 150.412ms
,I/BooksConfig( 6030): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6030): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6030): Soft error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6030): Sync error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6030): Finished books sync
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 282508, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 9
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 225s ago
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,E/SMD     (  296): DCD OFF,
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1020): initializing...
,I/TLC_TIMA_PKM_initialize( 1020): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1020): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1020): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1020): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1020): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1020): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1020): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1020): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1020): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1020): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1020): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1020): Trustlet response is completed
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/Watchdog( 1020): !@Sync 10
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1020): !@Sync 11,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 275s ago,
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  296): DCD OFF
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,W/GLSActivity( 1689): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1689): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1689): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1689): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1689): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1689): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1689): 	at android.os.Binder.execTransact(Binder.java:461)
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 5371): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5371): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5371): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5371): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5371): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5371): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5371): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 5371): Ignoring header User-Agent because its value was null.
,I/System.out( 5371): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5371): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5371): (HTTPLog)-Static: isShipBuild true
I/System.out( 5371): (HTTPLog)-Thread-903-418068394: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5371): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10026
,I/System.out( 5371): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/Watchdog( 1020): !@Sync 12
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1020): [PWL] Off : 330s ago
,E/Watchdog( 1020): !@Sync 13,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1020): Plugged,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1020): !@Sync 14
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 15,
I/PowerManagerService( 1020): [PWL] Off : 390s ago
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,E/SMD     (  296): DCD OFF,
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/bootchecker(  333): bootchecker wake up!!
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1020): !@Sync 16,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,V/AlarmManager( 1020): No more alarm at this time.nowELAPSED=515652 batch.start=537639
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1020): !@Sync 17
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 455s ago
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksSync( 6030): Starting books sync for 61035162, extras: ade
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6030): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6030): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6030): Soft error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6030): Sync error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6030): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 537639, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1020): !@Sync 18
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,V/AlarmManager( 1020): waitForAlarm result :4,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,I/Atfwd_Daemon(  336): Stop the daemon....,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1020): !@Sync 19
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF,
,I/PowerManagerService( 1020): [PWL] Off : 525s ago
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1020): !@Sync 20
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1020): !@Sync 21
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1020): !@Sync 22
,I/PowerManagerService( 1020): [PWL] Off : 600s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 23,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1020): !@Sync 24
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 680s ago,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1020): !@Sync 25
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 26
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 27
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 765s ago,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 28
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1020): !@Sync 29
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,E/SMD     (  296): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1020): !@Sync 30
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GCM     ( 1689): Message class com.google.f.a.a.i
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 855s ago
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 31
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 32
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 33,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 950s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 34
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6030): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6030): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6030): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6030): Soft error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6030): Sync error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6030): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1047275, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1020): !@Sync 35
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/art     ( 1020): Background sticky concurrent mark sweep GC freed 56898(6MB) AllocSpace objects, 324(5MB) LOS objects, 32% free, 23MB/35MB, paused 2.957ms total 124.562ms
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1020): !@Sync 36,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 37
,I/PowerManagerService( 1020): [PWL] Off : 1050s ago
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1020): Plugged,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 38
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 39,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1020): User[0] Flushing usage stats to disk,
,I/ApplicationUsage( 1020): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1020): Updating Usage Statistics in DB @ 1449627700192
,I/ApplicationPolicy( 1020): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1020): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1020): ::isTableExists: Table exists 
,I/ApplicationUsage( 1020): Done Updating Usage Statistics in DB @ 1449627700601
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 40
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1020): [PWL] Off : 1155s ago
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 41
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 42
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 43,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 44
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,I/PowerManagerService( 1020): [PWL] Off : 1266s ago,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 45,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 46,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 47
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 48,
,I/PowerManagerService( 1020): [PWL] Off : 1381s ago,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 49,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,E/SMD     (  296): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1020): !@Sync 50,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 51
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 52,
,I/PowerManagerService( 1020): [PWL] Off : 1501s ago,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 53,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 54
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 55
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 56
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 1626s ago,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 57
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 58
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 59
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 60
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/PowerManagerService( 1020): [PWL] Off : 1756s ago
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,I/ActivityManager( 1020): Killing 5192:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,I/ActivityManager( 1020): Killing 1604:com.sec.android.widgetapp.ap.hero.accuweather/u0a62 (adj 15): SPC_empty #32
I/ActivityManager( 1020): Killing 1668:com.sec.android.daemonapp/u0a157 (adj 15): SPC_empty #33,
I/ActivityManager( 1020): Killing 3348:com.sec.android.pagebuddynotisvc/u0a113 (adj 15): SPC_empty #34
I/ActivityManager( 1020): Killing 2967:com.samsung.android.providers.context/u0a2 (adj 15): SPC_empty #35
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ProcessStatsService( 1020): Prepared write state in 21ms
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): performPollLocked(flags=0x3)
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,V/NetworkStats( 1020): performPollLocked() took 5ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GpsStatusListenerHelper( 1020): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@e749109
,W/ActivityManager( 1020): Scheduling restart of crashed service com.samsung.android.providers.context/.ContextService in 3605168ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 1000ms
,W/ActivityManager( 1020): Scheduling restart of crashed service com.sec.android.widgetapp.ap.hero.accuweather/.WeatherClockScreenService in 10996ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 20985ms
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 1020): waitForAlarm result :8
,W/BroadcastQueue( 1020): Skipping deliver [foreground] BroadcastRecord{1e4ae1a u-1 android.intent.action.TIME_TICK} to ReceiverList{d560693 1668 com.sec.android.daemonapp/10157/u0 remote:21ac2f82}: filter unregistered
,I/EventLogService( 1989): Aggregate from 1449626318678 (log), 1449626318678 (data)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1689): Message class com.google.f.a.a.i
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ProcessStatsService( 1020): Pruning old procstats: /data/system/procstats/state-2015-12-08-11-13-18.bin
,W/libprocessgroup( 1020): failed to open /acct/uid_10002/pid_2967/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10113/pid_3348/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10062/pid_1604/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_5192/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10157/pid_1668/cgroup.procs: No such file or directory
,E/SQLiteLog( 1689): (10) POSIX Error : 11 SQLite Error : 3850
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6884): MountEmulatedStorage()
I/libpersona( 6884): KNOX_SDCARD checking this for 10113
E/Zygote  ( 6884): v2
I/libpersona( 6884): KNOX_SDCARD not a persona
I/SELinux ( 6884): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6884): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6884): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.android.pagebuddynotisvc for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc: pid=6884 uid=10113 gids={50113, 9997} abi=armeabi-v7a,
,D/TimaKeyStoreProvider( 6884): TimaSignature is unavailable
,D/ActivityThread( 6884): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 3704:com.sec.bcservice/1000 (adj 15): SPC_empty #31
,I/ActivityManager( 1020): Killing 2715:com.sec.phone/1001 (adj 15): SPC_empty #32
,I/PageBuddyNotiSvc( 6884): onCreate mCpBitFlag=0
,E/lowmemorykiller(  254): Error writing /proc/2715/oom_score_adj; errno=22
W/ActivityManager( 1020): ProcessRecord{2eaed3b1 2715:com.sec.phone/1001} is already killed
,E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 1020): Exception when unbinding service com.sec.phone/.SecPhoneService
W/ActivityManager( 1020): android.os.TransactionTooLargeException
W/ActivityManager( 1020): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 1020): 	at android.os.BinderProxy.transact(Binder.java:511)
W/ActivityManager( 1020): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:1029)
W/ActivityManager( 1020): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1997)
W/ActivityManager( 1020): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2381)
W/ActivityManager( 1020): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:18582)
W/ActivityManager( 1020): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6593)
W/ActivityManager( 1020): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:6806)
W/ActivityManager( 1020): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1606)
W/ActivityManager( 1020): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:566)
,W/ActivityManager( 1020): ProcessRecord{2eaed3b1 2715:com.sec.phone/1001} is already killed
,W/ActivityManager( 1020): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 29837ms
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3704/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1001/pid_2715/cgroup.procs: No such file or directory
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6905): MountEmulatedStorage(),
,E/Zygote  ( 6905): v2
I/libpersona( 6905): KNOX_SDCARD checking this for 10062
I/libpersona( 6905): KNOX_SDCARD not a persona
I/SELinux ( 6905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.android.widgetapp.ap.hero.accuweather for service com.sec.android.widgetapp.ap.hero.accuweather/.WeatherClockScreenService: pid=6905 uid=10062 gids={50062, 9997, 3003, 1028} abi=armeabi-v7a,
,I/SELinux ( 6905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6905): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6905): TimaSignature is unavailable
,D/ActivityThread( 6905): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 2061:com.samsung.hs20settings/1000 (adj 15): SPC_empty #31
,W/ResourcesManager( 6905): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6905): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6905): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): Scheduling restart of crashed service com.samsung.hs20settings/.WifiHs20UtilityService in 29856ms
,D/comsamsunglog( 6905): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 6905): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 1504301788142] [ 1 ] 
D/comsamsunglog( 6905): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port A3 qHD
D/comsamsunglog( 6905): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 6905): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 6905): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 1504301788142] [ 1 ] 
D/comsamsunglog( 6905): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port A3 qHD
D/comsamsunglog( 6905): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider( 1020): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10062
,D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2061/cgroup.procs: No such file or directory
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Zygote  ( 6922): MountEmulatedStorage(),
,E/Zygote  ( 6922): v2
I/libpersona( 6922): KNOX_SDCARD checking this for 10157
I/libpersona( 6922): KNOX_SDCARD not a persona
,I/SELinux ( 6922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1020): Start proc com.sec.android.daemonapp for content provider com.sec.android.daemonapp/.ap.common.WeatherContentProvider: pid=6922 uid=10157 gids={50157, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6922): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,I/art     (  324): Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 732us total 26.909ms
,D/TimaKeyStoreProvider( 6922): TimaSignature is unavailable
,D/ActivityThread( 6922): Added TimaKeyStore provider,
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 695us total 19.944ms
,W/ResourcesManager( 6922): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 705us total 20.063ms
,D/comsamsungapp( 6922): [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,D/comsamsungapp( 6922): [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
D/comsamsungapp( 6922): [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,D/comsamsungapp( 6922): [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,D/comsamsungapp( 6922): [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WCP:1122 [0:0] Provider Created
,D/comsamsungapp( 6922): [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/comsamsungapp( 6922): [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WCS:65 [0:0] selLocation : null
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR,
D/comsamsungapp( 6922): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/comsamsungapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,D/comsamsungapp( 6922): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 6922): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 6922): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 6922): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 6922): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 6922): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 6922): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:false, UtilgetIsDay():false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 6922): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 6922): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 6922): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 6922): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 6922): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 6922): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 6922): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 6922): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:false, UtilgetIsDay():false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 6922): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 6922): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 6922): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 6922): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 6922): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 6922): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 6922): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 6922): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:false, UtilgetIsDay():false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 6922): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 6922): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 6922): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 6922): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 6922): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 6922): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 6922): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 6922): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 6922): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 6922): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:false, UtilgetIsDay():false
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1020): !@Sync 61
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/art     ( 1020): Background partial concurrent mark sweep GC freed 54241(6MB) AllocSpace objects, 324(5MB) LOS objects, 33% free, 23MB/35MB, paused 2.437ms total 171.642ms
,E/SMD     (  296): DCD OFF
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6946): MountEmulatedStorage(),
E/Zygote  ( 6946): v2
I/libpersona( 6946): KNOX_SDCARD checking this for 1000
I/libpersona( 6946): KNOX_SDCARD not a persona
I/SELinux ( 6946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1020): Start proc com.sec.bcservice for service com.sec.bcservice/.BroadcastService: pid=6946 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6946): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6946): TimaSignature is unavailable
,D/ActivityThread( 6946): Added TimaKeyStore provider
,W/ResourcesManager( 6946): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/F_PHONE ( 6946): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 6946): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6961): MountEmulatedStorage(),
E/Zygote  ( 6961): v2
I/libpersona( 6961): KNOX_SDCARD checking this for 1001
I/libpersona( 6961): KNOX_SDCARD not a persona
,I/SELinux ( 6961): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1020): Start proc com.sec.phone for service com.sec.phone/.SecPhoneService: pid=6961 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a,
,I/SELinux ( 6961): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6961): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6961): TimaSignature is unavailable
,D/ActivityThread( 6961): Added TimaKeyStore provider
,W/ResourcesManager( 6961): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/F_PHONE ( 6946): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 6946): default registerAction()
I/F_PHONE ( 6946): [[com.sec.bcservice]] sendPendingMessage()
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.samsung.hs20settings for service com.samsung.hs20settings/.WifiHs20UtilityService: pid=6982 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6982): MountEmulatedStorage()
,E/Zygote  ( 6982): v2
,I/libpersona( 6982): KNOX_SDCARD checking this for 1000
I/libpersona( 6982): KNOX_SDCARD not a persona
I/SELinux ( 6982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6982): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6982): TimaSignature is unavailable
,D/ActivityThread( 6982): Added TimaKeyStore provider
,I/Hs20UtilService( 6982): onCreate
,I/Hs20UtilService( 6982): Starting #8
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged,
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/Watchdog( 1020): !@Sync 62
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 63
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1020): !@Sync 64
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  296): DCD OFF
D/AndroidRuntime( 7037): 
D/AndroidRuntime( 7037): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7037): CheckJNI is OFF
D/AndroidRuntime( 7037): readGMSProperty: start
D/AndroidRuntime( 7037): readGMSProperty: already setted!!
D/AndroidRuntime( 7037): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7037): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7037): readGMSProperty: end
D/AndroidRuntime( 7037): addProductProperty: start
E/AffinityControl( 7037): AffinityControl: registerfunction enter
D/AndroidRuntime( 7037): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 1020): START PACKAGE DELETE: observer{698489756}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1020): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 6105:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
W/PackageSettings( 1020): Skipping PackageSetting{39840c54 com.example.hello/10345} due to missing metadata
I/ActivityManager( 1020): Killing 5958:com.google.android.apps.plus/u0a117 (adj 15): empty for 1883s
I/ActivityManager( 1020): Killing 5934:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty for 1883s
I/ActivityManager( 1020): Killing 5911:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1883s
I/ActivityManager( 1020): Killing 5894:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1883s
I/ActivityManager( 1020): Killing 5876:com.sec.android.app.soundalive/u0a48 (adj 15): empty for 1883s
I/ActivityManager( 1020): Killing 5856:com.wsomacp/u0a23 (adj 15): empty for 1884s
I/ActivityManager( 1020): Killing 4848:com.google.android.gms.wearable/u0a11 (adj 15): empty for 1884s
I/ActivityManager( 1020): Killing 5838:com.sec.android.provider.badge/u0a68 (adj 15): empty for 1884s
I/ActivityManager( 1020): Killing 5823:com.sec.android.app.myfiles/u0a42 (adj 15): empty for 1884s
I/ActivityManager( 1020): Killing 5737:com.osp.app.signin/u0a36 (adj 15): empty for 1884s
I/ActivityManager( 1020): Killing 5791:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty for 1884s
I/ActivityManager( 1020): Killing 5773:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty for 1884s
I/ActivityManager( 1020): Killing 5715:com.policydm/1000 (adj 15): empty for 1884s
I/ActivityManager( 1020): Killing 5301:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty for 1885s
I/ActivityManager( 1020): Killing 5700:com.google.android.apps.docs/u0a87 (adj 15): empty for 1885s
I/ActivityManager( 1020): Killing 5685:com.sec.pcw.device/1000 (adj 15): empty for 1885s
I/ActivityManager( 1020): Killing 5662:com.samsung.helphub/1000 (adj 15): empty for 1885s
I/ActivityManager( 1020): Killing 5289:com.google.android.partnersetup/u0a14 (adj 15): empty for 1885s
W/ActivityManager( 1020): Spurious death for ProcessRecord{151779a5 6105:com.test.thalitest/u0a338}, curProc for 6105: null
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
I/art     ( 4084): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 912us total 35.038ms
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
I/art     ( 5984): Explicit concurrent mark sweep GC freed 108(16KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 676us total 66.107ms
W/GeofencerStateMachine( 1707): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1775): mOCRHelper is null
I/KLMS-2.5.123: ( 3751): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 03:34:12 GMT+01:00 2015
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3751): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1020): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1020): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1020): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3751): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3751): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/Zygote  ( 7052): MountEmulatedStorage()
E/Zygote  ( 7052): v2
I/libpersona( 7052): KNOX_SDCARD checking this for 10090
I/libpersona( 7052): KNOX_SDCARD not a persona
I/SELinux ( 7052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7052): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7052 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/art     ( 1020): Explicit concurrent mark sweep GC freed 18504(1884KB) AllocSpace objects, 45(720KB) LOS objects, 33% free, 23MB/35MB, paused 3.330ms total 199.489ms
I/art     ( 1020): WaitForGcToComplete blocked for 181.147ms for cause Explicit
I/KLMS-2.5.123: ( 3751): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
I/KLMS-2.5.123: ( 3751): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/TimaKeyStoreProvider( 7052): TimaSignature is unavailable
D/ActivityThread( 7052): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3751): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3751): KLMSIntentService(): listeningToPackageRemoved().START
D/RegisteredServicesCache( 1441): empty dynamic service
I/KLMS-2.5.123: ( 3751): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/RCPManagerService( 1020): PackageReceiver onReceive()
I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
E/Watchdog( 1020): !@Sync 65
I/KLMS-2.5.123: ( 3751): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:15121( 7052): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 7052): ELMEngine.ELMEngine( context ).
D/elm:15121( 7052): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 7052): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/KLMS-2.5.123: ( 3751): KLMSIntentService(): onDestroy()
D/elm:15121( 7052): ElmAgentService : onCreate()
D/elm:15121( 7052): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 7052): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 7052): MDMBridge.getInstance()
D/elm:15121( 7052): MDMBridge.getAllLicenseInfoFromSDK()
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1020): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10338
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/elm:15121( 7052): MDMBridge.getAllLicenseInfoFromSDK()
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10338
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
D/TaskPersister( 1020): removeObsoleteFile: deleting file=20_task.xml
D/elm:15121( 7052): ElmAgentService : onDestroy().
I/ActivityManager( 1020): Killing 5984:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty for 1883s
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/art     ( 1020): Explicit concurrent mark sweep GC freed 9755(493KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.802ms total 215.111ms
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7069): MountEmulatedStorage()
I/libpersona( 7069): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7069): v2
I/libpersona( 7069): KNOX_SDCARD not a persona
I/SELinux ( 7069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7069): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7069 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 7069): TimaSignature is unavailable
D/ActivityThread( 7069): Added TimaKeyStore provider
D/PackageManager( 1020): delete codoeFile: 
D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1020): UID=10338 Target=com.test.thalitest
D/PackageManager( 1020): result of delete: 1{698489756}
D/AndroidRuntime( 7037): Shutting down VM
I/PCWCLIENTTRACE_LOG( 7069): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7069): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7069): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 7069): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7069): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7069): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7069): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7084): MountEmulatedStorage()
I/libpersona( 7084): KNOX_SDCARD checking this for 10029
E/Zygote  ( 7084): v2
I/libpersona( 7084): KNOX_SDCARD not a persona
I/SELinux ( 7084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7084): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7084 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 6000:com.sec.android.app.samsungapps/u0a9 (adj 15): empty for 1883s
D/TimaKeyStoreProvider( 7084): TimaSignature is unavailable
D/ActivityThread( 7084): Added TimaKeyStore provider
I/FeatureConfig( 7084): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7101): MountEmulatedStorage()
E/Zygote  ( 7101): v2
I/libpersona( 7101): KNOX_SDCARD checking this for 10036
I/libpersona( 7101): KNOX_SDCARD not a persona
I/SELinux ( 7101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7101 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 5595:com.android.defcontainer/u0a3 (adj 15): empty for 1874s
W/ResourcesManager( 7084): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/SELinux ( 7101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7101): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 7084): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/PowerManagerService( 1020): [PWL] Off : 1891s ago
W/ResourcesManager( 7084): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 7101): TimaSignature is unavailable
W/ResourcesManager( 7084): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread( 7101): Added TimaKeyStore provider
W/ResourcesManager( 7084): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/art     ( 7037): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SA      ( 7101): [SSP] onCreated
W/ResourcesManager( 7084): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/libprocessgroup( 1020): failed to open /acct/uid_10068/pid_5838/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10117/pid_5958/cgroup.procs: No such file or directory
I/SA      ( 7101): [TPM] There is no property file
I/SA      ( 7101): [SCU] isHaveSA() - false
I/SA      ( 7101): [TPM] getModelProperty : null
I/SA      ( 7101): [TPM] getCSCProperty : null
I/SA      ( 7101): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 7101): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 7101): [DM] TFT FEATURE: false
I/SA      ( 7101): [DM] init START
I/SA      ( 7101): [DM] This device is not a Vodafone
W/ResourcesManager( 7084): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1020): no available spell checker services found
W/ResourceType( 7101): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7101): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7101): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourceType( 7101): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourcesManager( 7084): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourceType( 7101): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourceType( 7101): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourceType( 7101): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 7101): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/GalaxyFinderApplication( 7084): system/finder_cp/cpdata.xml file not found
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SA      ( 7101): [SCU] isHaveSA() - false
I/SA      ( 7101): support phone number id : false
I/SA      ( 7101): [DM] Supports Ref Jpn : true
I/SA      ( 7101): [DM] init END
I/SA      ( 7101): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 7101): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1020): Killing 4999:com.sec.android.gallery3d/u0a39 (adj 15): empty for 1811s
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 1020): Exception when sending broadcast to ComponentInfo{com.sec.android.gallery3d/com.sec.android.gallery3d.app.PackagesMonitor}
W/BroadcastQueue( 1020): android.os.TransactionTooLargeException
W/BroadcastQueue( 1020): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1020): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1020): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1020): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1020): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1020): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1020): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1020): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1020): 	at android.os.Binder.execTransact(Binder.java:461)
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7121): MountEmulatedStorage()
I/libpersona( 7121): KNOX_SDCARD checking this for 10039
E/Zygote  ( 7121): v2
I/libpersona( 7121): KNOX_SDCARD not a persona
I/SELinux ( 7121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7121 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 7121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7121): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7121): TimaSignature is unavailable
D/ActivityThread( 7121): Added TimaKeyStore provider
W/ResourcesManager( 7121): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7121): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7121): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7121): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7121): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7121): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7121): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}

```
