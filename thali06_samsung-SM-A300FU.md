#### Test 5753124305d96c2_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
,V/AlarmManager( 1022): waitForAlarm result :8
--------- beginning of main
I/ServiceManager(  318): Waiting for service AtCmdFwd...
D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
D/AndroidRuntime( 6135): 
D/AndroidRuntime( 6135): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6135): CheckJNI is OFF
D/AndroidRuntime( 6135): readGMSProperty: start
D/AndroidRuntime( 6135): readGMSProperty: already setted!!
D/AndroidRuntime( 6135): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6135): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6135): readGMSProperty: end
D/AndroidRuntime( 6135): addProductProperty: start
E/AffinityControl( 6135): AffinityControl: registerfunction enter
D/AndroidRuntime( 6135): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1022): inState():  stateMachine is null !!
I/PersonaManagerService( 1022): PersonaId don't exist
I/ActivityManager( 1022): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1022): mDVFSHelper.acquire()
D/FocusedStackFrame( 1022): Set to : 0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1022): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1022): *FMB* installDecor flags : 25362712
E/Zygote  ( 6148): MountEmulatedStorage()
I/ActivityManager( 1022): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6148 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
E/Zygote  ( 6148): v2
I/libpersona( 6148): KNOX_SDCARD checking this for 10338
D/InputDispatcher( 1022): Focused application set to: xxxx
I/libpersona( 6148): KNOX_SDCARD not a persona
D/InputDispatcher( 1022): Focus left window: 1486
D/AndroidRuntime( 6135): Shutting down VM
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6148): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6148): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6148): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6148): TimaSignature is unavailable
D/ActivityThread( 6148): Added TimaKeyStore provider
V/WindowManager( 1022): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1022): isKioskContainerExistOnDevice
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1486): updateVisibility : ActivityRecord{1f45b60e token=android.os.BinderProxy@bf9d28f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1486): onTrimMemory. Level: 20
I/WebViewFactory( 6148): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6148): Time to load native libraries: 1 ms (timestamps 6896-6897)
I/LibraryLoader( 6148): Expected native library version number "",actual native library version number ""
W/art     ( 6135): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6148): Binding Chromium to main looper Looper (main, tid 1) {37de99f1}
I/LibraryLoader( 6148): Expected native library version number "",actual native library version number ""
I/chromium( 6148): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6148): Initializing chromium process, singleProcess=true
W/art     ( 6148): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6148): ApplicationContext is null in ApplicationStatus
W/chromium( 6148): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6148): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6148): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6148): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6148): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6148): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6148): Local Branch: 
I/Adreno-EGL( 6148): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6148): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6148):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/art     ( 6148): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6148): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6148): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6148): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6148): CordovaWebView is running on device made by: samsung
W/art     ( 6148): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6148): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1022): Activity pause timeout for ActivityRecord{3b3d711 u0 com.test.thalitest/.MainActivity t20}
E/SMD     (  289): DCD OFF
I/ServiceManager(  318): Waiting for service AtCmdFwd...
D/OpenGLRenderer( 6148): Render dirty regions requested: true
D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
W/chromium( 6148): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6148): updateVisibility : ActivityRecord{275c9312 token=android.os.BinderProxy@edbbd74 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6148): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6148): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1022): Focus entered window: 6148
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6148): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6148): Initialized EGL, version 1.4
D/OpenGLRenderer( 6148): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6148): Enabling debug mode 0
D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/StatusBar( 1182): Icon Only
D/PanelView( 1182): There is/are notification(s) 
I/ActivityManager( 1022): Displayed Component not be shown by security: +649ms (total +10s458ms)
W/ActivityManager( 1022): mDVFSHelper.release()
I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{3b3d711 u0 com.test.thalitest/.MainActivity t20} time:127419
I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
W/IInputConnectionWrapper( 6148): showStatusIcon on inactive InputConnection
I/Timeline( 6148): Timeline: Activity_idle id: android.os.BinderProxy@edbbd74 time:127436
I/SamsungIME( 1821): getCurrentCandidateView
D/SamsungIME( 1821): Dismiss ExpandCandiate
I/SamsungIME( 1821): getDebugLevel  : 0x4f4c
I/SamsungIME( 1821): getDebugLevel  : 0x4f4c
I/SamsungIME( 1821): KeybaordView init() : load resources
I/SamsungIME( 1821): getCurrentKeyboard
I/SamsungIME( 1821): getTextKeyboard
D/SamsungIME( 1821): [SwiftkeyWrapper] currentLangauge : 1701729619
W/BindingManager( 6148): Cannot call determinedVisibility() - never saw a connection for the pid: 6148
D/JsMessageQueue( 6148): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6148): JniHelper::setJavaVM(0xb74ce448), pthread_self() = -1214119968
I/chromium( 6148): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/PowerManagerService( 1022): [PWL] Off : 50s ago
W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
D/SSRM:n  ( 1022): SIOP:: AP = 290
,V/AlarmManager( 1022): waitForAlarm result :4
,V/AlarmManager( 1022): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1022): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1022): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/SViewCoverWidget( 1182): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/jxcore-log( 6148): Initializing JXcore engine
,W/jxcore-log( 6148): JXcore engine is ready
,E/audit   ( 1872): type=1400 msg=audit(1454422562.787:205): avc:  denied  { ioctl } for  pid=6196 comm="Thread-1067" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1872):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1872): type=1300 msg=audit(1454422562.787:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=9ea008f8 items=0 ppid=307 ppcomm=main pid=6196 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm="Thread-1067" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1872): type=1320 msg=audit(1454422562.787:205): 
,W/jxcore-log( 6148): Starting JXcore engine
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 6148): Platform android
W/jxcore-log( 6148): 
,W/jxcore-log( 6148): Process ARCH arm
W/jxcore-log( 6148): 
,D/Finsky  ( 5400): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5400): [1] 5.onFinished: Installation state replication failed.,
,D/Finsky  ( 5400): [1] 5.onFinished: Scheduling replication attempt 3.
,I/jxcore-log( 6148): JXcore Cordova bridge is ready!
I/jxcore-log( 6148): 
,W/jxcore-log( 6148): JXcore engine is started
,E/jxcore  ( 6148): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6148): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6148): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1022): Set to : 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1022): Focused application set to: xxxx
D/InputDispatcher( 1022): Focus left window: 6148
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1022): Killing 4161:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,W/ActivityManager( 1022): mDVFSHelper.acquire()
,V/WindowManager( 1022): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1486): onRestart, Launcher: 772783859
,D/Launcher( 1486): onStart, Launcher: 772783859
,D/Launcher.HomeView( 1486): onStart
,D/Launcher( 1486): onResume, Launcher: 772783859
D/SettingsProvider( 1022): name = kids_home_mode
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 10006
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1022): ret = -1
D/Launcher.HomeView( 1486): onResume
,D/Launcher( 1486): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1486): onResume
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1022): handle home activity for 0
,I/WallpaperManagerService( 1022): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1022): post home show event for user 0
,D/WallpaperManagerService( 1022):  force update = false; persona id = 0; current user =0; current persona = 0
D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1022): handleHomeShow for 0 and current 0
,D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
D/Launcher.HomeView( 1486): onPause
,D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
,I/splitIntent( 1022): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
D/Launcher( 1486): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/splitIntent( 1022): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
D/GalleryCacheReady( 5007): Receive : home resume
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1022): userId = 0, bbcId = -10000,
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,I/SurfaceFlinger(  258): id=14 createSurf (540x960),1 flag=4, Mauncher
,D/Mms/UIEventReceiver( 5658): ui event
,D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
D/Recents_RecreateReceiver( 2536): onReceive by home
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/InputDispatcher( 1022): Focus entered window: 1486
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 1486): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,V/ActivityThread( 1486): updateVisibility : ActivityRecord{1f45b60e token=android.os.BinderProxy@bf9d28f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1486): onStop
,V/TaskCloserActivity( 6034): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 6148): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1821): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/StatusBar( 1182): Icon Only
D/PanelView( 1182): There is/are notification(s) 
,E/Zygote  ( 6205): MountEmulatedStorage()
I/libpersona( 6205): KNOX_SDCARD checking this for 10135
E/Zygote  ( 6205): v2
I/libpersona( 6205): KNOX_SDCARD not a persona
,I/SELinux ( 6205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/Timeline( 1486): Timeline: Activity_idle id: android.os.BinderProxy@bf9d28f time:129675
,E/SELinux ( 6205): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1022): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6205 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,D/PersonaManager( 1022): isKioskContainerExistOnDevice,
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1022): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1486, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
I/art     (  307): Explicit concurrent mark sweep GC freed 8711(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 21.764ms
,I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{104296e5 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:129703
W/ActivityManager( 1022): mDVFSHelper.release()
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/TimaKeyStoreProvider( 6205): TimaSignature is unavailable
,D/ActivityThread( 6205): Added TimaKeyStore provider
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.532ms
,W/ResourcesManager( 6205): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6205): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6205): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6205): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 16.573ms
,W/ResourcesManager( 6205): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1022): failed to open /acct/uid_10032/pid_4161/cgroup.procs: No such file or directory
,I/splitIntent( 1022): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1022): Killing 5229:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 6034): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,W/libprocessgroup( 1022): failed to open /acct/uid_10032/pid_5229/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1022): !@Sync 4
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1022): SIOP:: AP = 290
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged,
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 290
,V/AlarmManager( 1022): waitForAlarm result :4
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5400): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5400): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5400): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :4
,I/BooksSync( 6080): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6080): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PersonaManager( 1182): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1182): Icon Only
I/StatusBar( 1182): Icon Only
,D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1182): Icon Only
I/StatusBar( 1182): Icon Only
,D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6080): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6080): Soft error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6080): Sync error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6080): Finished books sync
,D/SyncManager( 1022): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 152356, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,I/PowerManagerService( 1022): [PWL] Off : 75s ago
,E/SQLiteLog( 1722): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1022): SIOP:: AP = 290
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1022): !@Sync 5
,D/SSRM:n  ( 1022): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :4
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5400): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5400): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5400): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :4
,I/PowerManagerService( 1022): [PWL] Off : 105s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager( 1022): waitForAlarm result :8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,E/Watchdog( 1022): !@Sync 6,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,V/AlarmManager( 1022): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1182): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1722): Vacuum at: now=1454422633051 tag=VacuumService
,I/GoogleURLConnFactory( 1722): Using platform SSLCertificateSocketFactory
,W/Uploader( 1722): No account for auth token provided
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1722): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1722): (HTTPLog)-Static: isShipBuild true
I/System.out( 1722): (HTTPLog)-Thread-207-295532689: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
,E/SMD     (  289): DCD OFF
,I/System.out( 1722): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1722): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10011
,I/qtaguid ( 1722): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10011
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 44155(2MB) AllocSpace objects, 40(644KB) LOS objects, 33% free, 24MB/36MB, paused 2.312ms total 143.747ms
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5400): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5400): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5400): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1722): No account for auth token provided
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1722): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10011
,W/Uploader( 1722): No account for auth token provided
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1722): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10011
,W/Uploader( 1722): No account for auth token provided
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1722): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10011
,W/Uploader( 1722):  no longer exists, so no auth token.
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1722): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10011
,W/Uploader( 1722): No account for auth token provided
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1722): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10011
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,E/Uploader( 1722): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1722): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1722): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1722): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1722): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1722): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1722): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1722): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/PersonaManager( 1182): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1182): Icon Only
I/StatusBar( 1182): Icon Only
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1182): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1182): Icon Only
I/StatusBar( 1182): Icon Only
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1722): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10011
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1722): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1022): [PWL] Off : 140s ago
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/Watchdog( 1022): !@Sync 7
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1022): [PWL] Off : 180s ago
,E/Watchdog( 1022): !@Sync 8
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/BatteryService( 1022): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1182): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/BooksSync( 6080): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6080): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PersonaManager( 1182): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1182): Icon Only
I/StatusBar( 1182): Icon Only
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1182): Icon Only
,I/StatusBar( 1182): Icon Only
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6080): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6080): Soft error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6080): Sync error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6080): Finished books sync
,D/SyncManager( 1022): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 276137, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/Watchdog( 1022): !@Sync 9
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1022): stay LED for fully charged
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 225s ago
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,V/AlarmManager( 1022): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1182): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/TimaService( 1022): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1022): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1022): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1022): initializing...,
I/TLC_TIMA_PKM_initialize( 1022): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1022): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1022): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1022): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1022): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1022): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1022): max_message_size = 524416 = 0x80080,
D/QSEECOMAPI: ( 1022): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1022): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1022): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1022): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1022): Trustlet response is completed
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1022): Plugged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,I/TLC_TIMA_PKM_measure_kernel( 1022): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1022): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1022): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1022): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1022): !@Sync 10
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/Watchdog( 1022): !@Sync 11
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1022): [PWL] Off : 275s ago,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PersonaManager( 1182): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1182): Icon Only
I/StatusBar( 1182): Icon Only
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1182): Icon Only
I/StatusBar( 1182): Icon Only
,W/GLSActivity( 1722): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1722): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1722): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1722): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1722): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1722): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1722): 	at android.os.Binder.execTransact(Binder.java:461)
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 5400): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5400): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5400): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5400): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5400): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5400): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5400): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 5400): Ignoring header User-Agent because its value was null.
,I/System.out( 5400): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5400): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5400): (HTTPLog)-Static: isShipBuild true
I/System.out( 5400): (HTTPLog)-Thread-918-522801544: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5400): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10026
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/System.out( 5400): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager( 1022): waitForAlarm result :8,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged,
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,E/Watchdog( 1022): !@Sync 12,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 330s ago
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1022): !@Sync 13,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1022): !@Sync 14,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1022): [PWL] Off : 390s ago
,E/Watchdog( 1022): !@Sync 15,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/bootchecker(  314): bootchecker wake up!!,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 16,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1022): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6080): Starting books sync for 61035162, extras: ade
,D/SViewCoverWidget( 1182): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6080): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PersonaManager( 1182): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1182): Icon Only
I/StatusBar( 1182): Icon Only
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1182): Icon Only
I/StatusBar( 1182): Icon Only
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6080): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6080): Soft error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6080): Sync error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6080): Finished books sync
,D/SyncManager( 1022): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 523517, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 17
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1022): [PWL] Off : 455s ago,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1182): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1022): !@Sync 18
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1022): Plugged,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/Atfwd_Daemon(  318): Stop the daemon....
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 19,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 525s ago
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1022): waitForAlarm result :8,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/TimaService( 1022): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1022): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1022): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1022): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1022): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1022): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1022): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 20,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 21
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 600s ago
,E/Watchdog( 1022): !@Sync 22
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 23
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 24
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 680s ago
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1022): Plugged,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 25
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1022): !@Sync 26
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 27
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 765s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 28
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 29
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/TimaService( 1022): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1022): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1022): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1022): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1022): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1022): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1022): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1022): !@Sync 30
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 855s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1022): !@Sync 31
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1022): !@Sync 32
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,E/SMD     (  289): DCD OFF
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1022): !@Sync 33
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SViewCoverWidget( 1182): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167],
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6080): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6080): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PersonaManager( 1182): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1182): Icon Only
I/StatusBar( 1182): Icon Only
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1182): Icon Only
I/StatusBar( 1182): Icon Only
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6080): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6080): Soft error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6080): Sync error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6080): Finished books sync
,D/SyncManager( 1022): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1017920, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 950s ago
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 34
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1182): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1022): waitForAlarm result :4
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000,
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1722): Message class com.google.f.a.a.i
,I/EventLogService( 2044): Aggregate from 1454421701861 (log), 1454421701861 (data)
,E/Watchdog( 1022): !@Sync 35
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1022): !@Sync 36
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 1051s ago
,E/Watchdog( 1022): !@Sync 37
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 38
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false,
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 39
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1022): Plugged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/TimaService( 1022): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1022): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1022): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1022): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1022): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1022): Updating Usage Statistics in DB @ 1454423649697
,I/ApplicationPolicy( 1022): updateDataUsageMap
,I/NetworkDataUsageDb( 1022): ::getAppControlDB: DB is Created 
I/NetworkDataUsageDb( 1022): ::isTableExists: Table exists 
,I/ApplicationUsage( 1022): Done Updating Usage Statistics in DB @ 1454423650039
,I/TLC_TIMA_PKM_measure_kernel( 1022): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1022): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1022): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1022): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 40,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1022): [PWL] Off : 1156s ago
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1022): Plugged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1022): !@Sync 41
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1022): stay LED for fully charged
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 42,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1022): Plugged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged,
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 43,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1182): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1182): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1022): !@Sync 44,
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6733): 
D/AndroidRuntime( 6733): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6733): CheckJNI is OFF
D/AndroidRuntime( 6733): readGMSProperty: start
D/AndroidRuntime( 6733): readGMSProperty: already setted!!
D/AndroidRuntime( 6733): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6733): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6733): readGMSProperty: end
D/AndroidRuntime( 6733): addProductProperty: start
E/AffinityControl( 6733): AffinityControl: registerfunction enter
D/AndroidRuntime( 6733): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1022): START PACKAGE DELETE: observer{634051719}
D/PackageManager( 1022): pkg{<packageName>}
D/PackageManager( 1022): user{0}
D/PackageManager( 1022): caller{2000}
D/PackageManager( 1022): flags{3}
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1022): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1022): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1022): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1022): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1022): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1022): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1022): Killing 6148:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1022): Skipping PackageSetting{121ae70e com.example.hello/10346} due to missing metadata
W/ActivityManager( 1022): Spurious death for ProcessRecord{3dfb37b4 6148:com.test.thalitest/u0a338}, curProc for 6148: null
I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
W/ActivityManager( 1022): CustomStartingWindow se packge removed so remove capture also
I/art     ( 4061): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 1.105ms total 41.390ms
I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
I/art     ( 6000): Explicit concurrent mark sweep GC freed 108(16KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 927us total 59.862ms
E/SamsungIME( 1821): mOCRHelper is null
W/GeofencerStateMachine( 1798): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.123: ( 3703): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 15:36:13 GMT+01:00 2016
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3703): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1022): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1022): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1022): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6746): MountEmulatedStorage()
E/Zygote  ( 6746): v2
I/libpersona( 6746): KNOX_SDCARD checking this for 10090
I/libpersona( 6746): KNOX_SDCARD not a persona
I/SELinux ( 6746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6746 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1022): mCursor = null
D/TimaKeyStoreProvider( 6746): TimaSignature is unavailable
D/ActivityThread( 6746): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3703): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.123: ( 3703): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): PACKAGE_REMOVED
D/RegisteredServicesCache( 1446): empty dynamic service
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): listeningToPackageRemoved().START
I/art     ( 1022): Explicit concurrent mark sweep GC freed 46620(4MB) AllocSpace objects, 145(2MB) LOS objects, 33% free, 24MB/36MB, paused 3.260ms total 222.645ms
I/art     ( 1022): WaitForGcToComplete blocked for 133.709ms for cause Explicit
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/elm:15121( 6746): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 6746): ELMEngine.ELMEngine( context ).
D/elm:15121( 6746): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 6746): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 6746): ElmAgentService : onCreate()
D/RCPManagerService( 1022): PackageReceiver onReceive()
D/elm:15121( 6746): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/HarmonyEASService( 1022): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:15121( 6746): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6746): MDMBridge.getInstance()
D/elm:15121( 6746): MDMBridge.getAllLicenseInfoFromSDK()
D/KnoxMUMContainerPolicy( 1022): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:15121( 6746): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:15121( 6746): ElmAgentService : onDestroy().
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): onDestroy()
D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1022): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1022): uID is 10338
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TaskPersister( 1022): removeObsoleteFile: deleting file=20_task.xml
D/SSRM:aZ ( 1022): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1022): uID is 10338
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
I/PCWCLIENTTRACE_PushUtil( 5705): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5705): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5705): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5705): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5778): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5778): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 5007): PackagesMonitor onReceive :com.test.thalitest
I/art     ( 1022): Explicit concurrent mark sweep GC freed 13333(707KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 14.527ms total 214.094ms
D/EnterpriseDeviceManagerService( 1022): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1022): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1022): no available spell checker services found
D/Mms/FreeMessageStatusReceiver( 5658): onReceive, action : android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/TactileAssist( 1022): enable value -1
I/TactileAssist( 1022): internal enable value -1
I/TactileAssist( 1022): intensity value -1
I/TactileAssist( 1022): saveAppList value true
D/Mms/FreeMessageReceiverService( 5658): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5658): onHandleIntent: ACTION_PACKAGE_REMOVED
D/PackageManager( 1022): delete codoeFile: 
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/TactileAssist( 1022): List of disabled apps :
D/AASAuninstall( 1022): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1022): UID=10338 Target=com.test.thalitest
D/PackageManager( 1022): result of delete: 1{634051719}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 6733): Shutting down VM
D/Compatibility( 5890): onReceive() it will make start service
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5890): onHandleIntent()
D/Compatibility( 5890): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10338, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5890): found: 2
D/Compatibility( 5890): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5890): skipping ResolveInfo{2431e42d com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5890): considering ResolveInfo{4920d62 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5890): default: com.sec.android.app.soundalive.SAControlPanelActivity
E/Zygote  ( 6766): MountEmulatedStorage()
I/libpersona( 6766): KNOX_SDCARD checking this for 10055
E/Zygote  ( 6766): v2
I/libpersona( 6766): KNOX_SDCARD not a persona
I/SELinux ( 6766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6766 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 6766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6766): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5890): enabling receiver ResolveInfo{2e0fbef3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5890): enabling receiver ResolveInfo{bd487b0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/Compatibility( 5890): enabling receiver ResolveInfo{2cf59629 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/TimaKeyStoreProvider( 6766): TimaSignature is unavailable
D/ActivityThread( 6766): Added TimaKeyStore provider
D/Compatibility( 5890): enabling receiver ResolveInfo{5079dae com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5890): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/UserAnalysis.PlaceProvider( 6766): PlaceProvider onCreate()
W/ResourceType( 1022): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1022): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UserAnalysis.SecureDbManager( 6766): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6766): SecurePlaceDbHelper() 
D/UserAnalysis( 6766): Create SecureDbHelper
D/IntelligenceServiceApplication( 6766): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6766): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/ContextImpl( 5911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1022): userId = 0, bbcId = -10000
D/IntelligenceServiceApplication( 6766): no applications having user consent for prediction
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetection::stopService] Service stopped.
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 6783): MountEmulatedStorage()
E/Zygote  ( 6783): v2
I/libpersona( 6783): KNOX_SDCARD checking this for 1000
I/libpersona( 6783): KNOX_SDCARD not a persona
I/SELinux ( 6783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6783 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6783): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UsbSettingsManager( 1022): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1022): onPackageRemoved : com.test.thalitest
I/ActivityManager( 1022): Killing 5316:com.google.android.partnersetup/u0a14 (adj 15): empty #31
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
D/TimaKeyStoreProvider( 6783): TimaSignature is unavailable
D/ActivityThread( 6783): Added TimaKeyStore provider
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
W/ResourcesManager( 6783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/BluetoothAdapter( 6766): cancelDiscovery
E/SMD     (  289): DCD OFF
D/BluetoothAdapterProperties( 2634): mDiscovering is false
E/BluetoothAdapterService( 2634): This is not a scanning status. cancelDiscovery() will be not called.
D/BluetoothAdapter( 6766): cancelDiscovery = true
V/PlaceDetection v1.0.19 ( 6766): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 6766): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
W/art     ( 6733): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/RCPManager( 6783):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1022):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1022): queryAllProviders():  providerCallBack is not register for 0
D/FilterInstaller( 5930): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
W/ContextImpl( 5930): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
I/FilterInstaller( 5930): FilterPackageService : ACTION_PACKAGE_REMOVED
I/FilterInstaller( 5930): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5930): before removeFromFS
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1022): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6799 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
E/Zygote  ( 6799): MountEmulatedStorage()
E/Zygote  ( 6799): v2
I/libpersona( 6799): KNOX_SDCARD checking this for 10095
I/libpersona( 6799): KNOX_SDCARD not a persona
I/SELinux ( 6799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/SELinux ( 6799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6799): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1022): failed to open /acct/uid_10014/pid_5316/cgroup.procs: No such file or directory
E/Zygote  ( 6809): MountEmulatedStorage()
E/Zygote  ( 6809): v2
I/libpersona( 6809): KNOX_SDCARD checking this for 1000
I/libpersona( 6809): KNOX_SDCARD not a persona
I/SELinux ( 6809): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6809): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1022): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6809 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 6809): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6799): TimaSignature is unavailable
D/ActivityThread( 6799): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 6809): TimaSignature is unavailable
D/ActivityThread( 6809): Added TimaKeyStore provider
D/PreloadFilterInstaller( 6799): uses FILTER_DB_VER_1
E/SQLiteLog( 6799): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6799): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6799): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6799): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6799): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6799): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6799): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6799): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6799): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6799): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6799): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6799): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6799): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6799): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6799): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6799): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6799): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteDatabase( 6799): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteDatabase( 6799): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteDatabase( 6799): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteDatabase( 6799): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 6799): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 6799): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6799): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6799): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6799): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6799): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6799): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6799): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6799): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6799): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6799): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6799): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6799): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6799): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 6799): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6799): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6799): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6799): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6799): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6799): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6799): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6799): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6799): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6799): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6799): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6799): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6799): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6799): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6799): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteOpenHelper( 6799): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteOpenHelper( 6799): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteOpenHelper( 6799): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteOpenHelper( 6799): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 6799): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 6799): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 6799): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 6799): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 6799): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6799): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6799): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6799): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6799): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6799): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6799): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6799): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6799): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 6799): Opened filter.db in read-only mode
E/SQLiteLog( 6799): (284) automatic index on titles(filter_id)
W/ContextImpl( 6809): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 6809): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6809): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 6809): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6809): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6809): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6809): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6809): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6809): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6809): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6809): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/SQLiteDatabase( 6809): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/SQLiteDatabase( 6809): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6809): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6809): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Zygote  ( 6832): MountEmulatedStorage()
E/Zygote  ( 6832): v2
I/libpersona( 6832): KNOX_SDCARD checking this for 1000
I/libpersona( 6832): KNOX_SDCARD not a persona
E/AndroidRuntime( 6809): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 6809): Process: com.android.keychain, PID: 6809
E/AndroidRuntime( 6809): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6809): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6809): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6809): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6809): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6809): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6809): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6809): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/AndroidRuntime( 6809): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/AndroidRuntime( 6809): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6809): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6809): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1022): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6832 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6832): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6832): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6832): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.android.keychain
E/SQLiteLog( 6799): (284) automatic index on titles(filter_id)
I/Process ( 6809): Sending signal. PID: 6809 SIG: 9
E/DropBoxManagerService( 1022): Can't write: system_app_crash
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop175.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1022): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1022): 	... 5 more
D/TimaKeyStoreProvider( 6832): TimaSignature is unavailable
D/ActivityThread( 6832): Added TimaKeyStore provider

```
