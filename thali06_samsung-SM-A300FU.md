#### Test 6170335106d974e_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
--------- beginning of main
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,I/PowerManagerService( 1018): [PWL] Off : 15s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1813, ws=null) (elapsedTime=32739)
D/AndroidRuntime( 5279): 
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
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5291 uid=10346 gids={50346, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/libpersona( 5291): KNOX_SDCARD checking this for 10346
D/InputDispatcher( 1018): Focused application set to: xxxx
I/libpersona( 5291): KNOX_SDCARD not a persona
E/Zygote  ( 5291): MountEmulatedStorage()
E/Zygote  ( 5291): v2
D/InputDispatcher( 1018): Focus left window: 1475
D/AndroidRuntime( 5279): Shutting down VM
I/SELinux ( 5291): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5291): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, iello
E/SELinux ( 5291): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/SMD     (  293): DCD OFF
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5291): TimaSignature is unavailable
D/ActivityThread( 5291): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1018): Display changed displayId=0
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1475): updateVisibility : ActivityRecord{20d9dfe5 token=android.os.BinderProxy@70fecc1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1475): onTrimMemory. Level: 20
I/WebViewFactory( 5291): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5291): Time to load native libraries: 1 ms (timestamps 7376-7377)
I/LibraryLoader( 5291): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5291): Binding Chromium to main looper Looper (main, tid 1) {3c8cf02}
I/LibraryLoader( 5291): Expected native library version number "",actual native library version number ""
I/chromium( 5291): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5291): Initializing chromium process, singleProcess=true
W/art     ( 5291): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5291): ApplicationContext is null in ApplicationStatus
W/chromium( 5291): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/art     ( 5279): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/chromium( 5291): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5291): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5291): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5291): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5291): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5291): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5291): Local Branch: 
I/Adreno-EGL( 5291): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5291): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5291):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5291): 889092719: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5291): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5291): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5291): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5291): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5291): CordovaWebView is running on device made by: samsung
,W/art     ( 5291): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5291): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5291): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/chromium( 5291): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/PhoneWindow( 5291): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5291): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1018): Focus entered window: 5291
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5291): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5291): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5291): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
D/OpenGLRenderer( 5291): Enabling debug mode 0
,V/ActivityThread( 5291): updateVisibility : ActivityRecord{2e5363ac token=android.os.BinderProxy@367431fe {com.example.hello/com.example.hello.MainActivity}} show : true,
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1175): Icon Only
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1175): There is/are notification(s) 
,W/IInputConnectionWrapper( 5291): showStatusIcon on inactive InputConnection
,I/Timeline( 5291): Timeline: Activity_idle id: android.os.BinderProxy@367431fe time:67904
,I/ActivityManager( 1018): Displayed Component not be shown by security: +622ms (total +692ms)
,W/ActivityManager( 1018): mDVFSHelper.release()
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{3df951b7 u0 com.example.hello/.MainActivity t22} time:67913
,I/SamsungIME( 1786): getCurrentCandidateView
,I/SurfaceFlinger(  257): id=11 Removed iello (7/9)
,I/SurfaceFlinger(  257): id=11 Removed iello (-2/9)
,W/BindingManager( 5291): Cannot call determinedVisibility() - never saw a connection for the pid: 5291
,D/SamsungIME( 1786): Dismiss ExpandCandiate
,I/chromium( 5291): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/SamsungIME( 1786): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1786): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1786): KeybaordView init() : load resources
,I/SamsungIME( 1786): getCurrentKeyboard
,I/SamsungIME( 1786): getTextKeyboard
,D/SamsungIME( 1786): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5291): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5291): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5291): JniHelper::setJavaVM(0xb75db448), pthread_self() = -1218271528
,W/jxcore-log( 5291): Initializing JXcore engine
,W/jxcore-log( 5291): JXcore engine is ready
,E/audit   ( 1810): type=1400 msg=audit(1457358099.390:203): avc:  denied  { ioctl } for  pid=5340 comm="Thread-917" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1810):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1810): type=1300 msg=audit(1457358099.390:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ebff8f8 items=0 ppid=318 ppcomm=main pid=5340 auid=4294967295 uid=10346 gid=10346 euid=10346 suid=10346 fsuid=10346 egid=10346 sgid=10346 fsgid=10346 ses=4294967295 tty=(none) comm="Thread-917" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1810): type=1320 msg=audit(1457358099.390:203): 
,W/jxcore-log( 5291): Starting JXcore engine
,W/jxcore-log( 5291): Platform android
W/jxcore-log( 5291): 
,W/jxcore-log( 5291): Process ARCH arm
W/jxcore-log( 5291): 
,I/jxcore-log( 5291): JXcore Cordova bridge is ready!
I/jxcore-log( 5291): 
,W/jxcore-log( 5291): JXcore engine is started
,E/jxcore  ( 5291): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 5291): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/PhoneWindow( 5291): *FMB* installDecor mIsFloating : true
,D/PhoneWindow( 5291): *FMB* installDecor flags : 8388610
,D/InputDispatcher( 1018): Focus left window: 5291
,D/InputDispatcher( 1018): Focus entered window: 5291
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/PhoneWindow( 5291): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5291): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=4, NainActivit
,D/SRIB_DCS( 5291): log_dcs ThreadedRenderer::initialize entered! 
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{16a3ea01 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 320
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/Watchdog( 1018): !@Sync 2,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4773): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4773): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4773): [1] 5.onFinished: Scheduling replication attempt 1.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 300,
,I/PowerManagerService( 1018): [PWL] Off : 30s ago,
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1813, ws=null) (elapsedTime=47741)
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate,
,D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  281): getNetworkForDns: using netid 0 for uid 10011
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK,
I/libpersona( 5359): KNOX_SDCARD checking this for 10102
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
I/libpersona( 5359): KNOX_SDCARD not a persona
E/Zygote  ( 5359): MountEmulatedStorage()
E/Zygote  ( 5359): v2
I/SELinux ( 5359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5359 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 5359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5359): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5359): TimaSignature is unavailable
,D/ActivityThread( 5359): Added TimaKeyStore provider
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ResourcesManager( 5359): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/art     ( 5359): Waited 1800 us for thread suspend!
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel_SMS( 5359): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5359): MmsConfig.loadMmsSettings
I/Babel_SMS( 5359): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 5359): MmsConfig.loadFromDatabase
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/Babel_SMS( 5359): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5359): MmsConfig.loadFromResources
,E/Babel_SMS( 5359): canonicalizeMccMnc: invalid mccmnc nullnull
,D/Finsky  ( 4773): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4773): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4773): [1] 5.onFinished: Scheduling replication attempt 2.
,I/Babel_SMS( 5359): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/QCamera2Factory(  287): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  287): getCameraInfo: X
,W/QCamera2Factory(  287): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  287): getCameraInfo: X
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5359): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5359): startup - clean
,I/Babel   ( 5359): deleted: false for 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 5359): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5359): Unsupported mime audio/evrc
,W/AudioCapabilities( 5359): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5359): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5359): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5359): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5359): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5359): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5359): Unsupported mime audio/evrc
,W/VideoCapabilities( 5359): Unsupported mime video/wvc1
,W/VideoCapabilities( 5359): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5359): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5359): Unsupported mime video/wvc1
,W/VideoCapabilities( 5359): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5359): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5359): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5359): Unsupported mime video/mp43
,W/VideoCapabilities( 5359): Unsupported mime video/sorenson
,W/VideoCapabilities( 5359): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5359): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5359): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5359): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5359): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5359): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1018): Killing 4329:com.google.android.music:main/u0a108 (adj 15): empty #31
,I/vclib   ( 5359): onServiceConnected
,W/Babel   ( 5359): Attempted to change video mute state without an active call.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10108/pid_4329/cgroup.procs: No such file or directory
,E/SQLiteLog( 1690): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/PowerManagerService( 1018): [PWL] Off : 50s ago,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,D/FactoryTest( 4670): Not factory mode
,D/FactoryTest( 4670): Not factory mode. isFactoryMode() returend false,
,D/MTPRx   ( 4670): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4670): still no open session command from host, so toast
,W/ContextImpl( 4670): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4670): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4670): Timeline: Activity_launch_request id:com.android.settings time:106886
,E/PersonaManagerService( 1018): inState():  stateMachine is null !!
,I/PersonaManagerService( 1018): PersonaId don't exist
,I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1018): Focused application set to: xxxx
,D/InputDispatcher( 1018): Focus left window: 5291
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,E/MTPRx   ( 4670): started activity for popup
,W/ResourcesManager( 4670): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4670): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4670): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4670): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4670): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4670): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4670): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/InputDispatcher( 1018): Focused application set to: xxxx
,D/InputDispatcher( 1018): Focus entered window: 5291
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SettingsReceiverActivity( 4670): dev.kiessupport is : TRUE
,D/PhoneWindow( 4670): *FMB* installDecor mIsFloating : true,
D/PhoneWindow( 4670): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,V/ActivityThread( 5291): updateVisibility : ActivityRecord{2e5363ac token=android.os.BinderProxy@367431fe {com.example.hello/com.example.hello.MainActivity}} show : true
,I/Timeline( 5291): Timeline: Activity_idle id: android.os.BinderProxy@367431fe time:107079
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,E/Watchdog( 1018): !@Sync 3
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD OFF
,W/ActivityManager( 1018): mDVFSHelper.release()
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF,
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4773): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4773): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4773): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,I/PowerManagerService( 1018): [PWL] Off : 75s ago,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1018): !@Sync 4
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,D/Finsky  ( 4773): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/Finsky  ( 4773): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4773): [1] 5.onFinished: Scheduling replication attempt 4.
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 1690): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 105s ago,
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 38590(2MB) AllocSpace objects, 43(688KB) LOS objects, 33% free, 23MB/35MB, paused 2.074ms total 135.909ms,
,D/Finsky  ( 4773): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4773): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4773): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 5
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    (  281): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 0 for uid 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4773): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4773): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4773): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  293): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 5447): 
D/AndroidRuntime( 5447): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5447): CheckJNI is OFF
D/AndroidRuntime( 5447): readGMSProperty: start
D/AndroidRuntime( 5447): readGMSProperty: already setted!!
D/AndroidRuntime( 5447): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5447): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5447): readGMSProperty: end
D/AndroidRuntime( 5447): addProductProperty: start
E/AffinityControl( 5447): AffinityControl: registerfunction enter
D/AndroidRuntime( 5447): Calling main entry com.android.commands.pm.Pm
E/Watchdog( 1018): !@Sync 7
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{429287546}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1018): !@killApplicatoin: 10346, uninstall pkg
I/ActivityManager( 1018): Force stopping com.example.hello appid=10346 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 5291:com.example.hello/u0a346 (adj 0): stop com.example.hello cause uninstall pkg
W/PackageSettings( 1018): Skipping PackageSetting{34a90bba com.test.thalitest/10338} due to missing metadata
I/WindowState( 1018): WIN DEATH: Window{253b5b31 u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger(  257): id=12 Removed NainActivit (5/9)
I/SurfaceFlinger(  257): id=12 Removed NainActivit (-2/9)
W/InputDispatcher( 1018): channel ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 1018): channel ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher( 1018): Attempted to unregister already unregistered input channel
I/WindowState( 1018): WIN DEATH: Window{38c0df0 u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
D/InputDispatcher( 1018): Focus left window: 5291
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{3df951b7 u0 com.example.hello/.MainActivity t22}
W/ActivityManager( 1018): Spurious death for ProcessRecord{13bd82b 5291:com.example.hello/u0a346}, curProc for 5291: null
D/InputDispatcher( 1018): Focused application released
I/ActivityManager( 1018): Force stopping com.example.hello appid=10346 user=0: pkg removed
W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3608): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 815us total 25.671ms
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4168): Explicit concurrent mark sweep GC freed 102(15KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.191ms total 52.639ms
W/GeofencerStateMachine( 1641): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1786): mOCRHelper is null
I/KLMS-2.5.123: ( 3402): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 07 14:44:19 GMT+01:00 2016
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3402): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5460): MountEmulatedStorage()
E/Zygote  ( 5460): v2
I/libpersona( 5460): KNOX_SDCARD checking this for 10090
I/libpersona( 5460): KNOX_SDCARD not a persona
I/SELinux ( 5460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5460): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5460 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3402): KLMSIntentService(): onCreate()
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
I/KLMS-2.5.123: ( 3402): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/TimaKeyStoreProvider( 5460): TimaSignature is unavailable
D/SecContentProvider2( 1018): mCursor = null
D/ActivityThread( 5460): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3402): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3402): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3402): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3402): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3402): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
I/art     ( 1018): Explicit concurrent mark sweep GC freed 19676(1811KB) AllocSpace objects, 33(528KB) LOS objects, 33% free, 23MB/35MB, paused 2.811ms total 167.796ms
I/art     ( 1018): WaitForGcToComplete blocked for 160.690ms for cause Explicit
D/elm:15121( 5460): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 5460): ELMEngine.ELMEngine( context ).
D/elm:15121( 5460): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/RegisteredServicesCache( 1437): empty dynamic service
D/elm:15121( 5460): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 5460): ElmAgentService : onCreate()
D/elm:15121( 5460): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 5460): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5460): MDMBridge.getInstance()
D/elm:15121( 5460): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 5460): MDMBridge.getAllLicenseInfoFromSDK()
W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
I/KLMS-2.5.123: ( 3402): KLMSIntentService(): listeningToPackageRemoved().END
D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:15121( 5460): ElmAgentService : onDestroy().
I/ActivityManager( 1018): Killing 4904:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/KLMS-2.5.123: ( 3402): KLMSIntentService(): onDestroy()
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     ( 1018): Explicit concurrent mark sweep GC freed 13466(623KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.062ms total 208.963ms
D/PackageManager( 1018): delete codoeFile: 
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10346, packageName = com.example.hello
I/AASA_removePackage( 1018): UID=10346 Target=com.example.hello
D/PackageManager( 1018): result of delete: 1{429287546}
D/AndroidRuntime( 5447): Shutting down VM
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10346
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/TaskPersister( 1018): removeObsoleteFile: deleting file=22_task.xml
V/EnterpriseBillingPolicy( 1018): uID is 10346
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/PCWCLIENTTRACE_PushUtil( 5073): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5073): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5073): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5073): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1018): clearDefaults: com.example.hello
I/CrashAnrDetector( 1018): onPackageRemoved : com.example.hello
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4904/cgroup.procs: No such file or directory
I/SA      ( 5174): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5174): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10346 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 4402): PackagesMonitor onReceive :com.example.hello
D/Mms/FreeMessageStatusReceiver( 4228): onReceive, action : android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1018): enable value -1
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
I/TactileAssist( 1018): List of disabled apps :
D/Mms/FreeMessageReceiverService( 4228): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4228): onHandleIntent: ACTION_PACKAGE_REMOVED
D/Compatibility( 5138): onReceive() it will make start service
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5138): onHandleIntent()
D/Compatibility( 5138): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10346, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5138): found: 2
D/Compatibility( 5138): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5138): skipping ResolveInfo{2b78d94e com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5138): considering ResolveInfo{34fe7a6f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5138): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5138): enabling receiver ResolveInfo{3a82237c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/Zygote  ( 5480): MountEmulatedStorage()
I/libpersona( 5480): KNOX_SDCARD checking this for 10055
E/Zygote  ( 5480): v2
I/libpersona( 5480): KNOX_SDCARD not a persona
I/SELinux ( 5480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5480): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5480 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
D/Compatibility( 5138): enabling receiver ResolveInfo{3e211405 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/Compatibility( 5138): enabling receiver ResolveInfo{90d3c5a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5138): enabling receiver ResolveInfo{2aa24e8b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5138): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 5480): TimaSignature is unavailable
D/ActivityThread( 5480): Added TimaKeyStore provider
D/UserAnalysis.PlaceProvider( 5480): PlaceProvider onCreate()
W/art     ( 5447): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/UserAnalysis.SecureDbManager( 5480): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 5480): SecurePlaceDbHelper() 
D/UserAnalysis( 5480): Create SecureDbHelper
D/IntelligenceServiceApplication( 5480): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 5480): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/ContextImpl( 4475): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/IntelligenceServiceApplication( 5480): no applications having user consent for prediction
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5496): MountEmulatedStorage()
E/Zygote  ( 5496): v2
I/libpersona( 5496): KNOX_SDCARD checking this for 1000
I/SELinux ( 5496): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5496): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5496 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetection::stopService] Service stopped.
I/SELinux ( 5496): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5496): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 4938:com.wssyncmldm/1000 (adj 15): empty #31
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/SQLiteLog( 5480): (10) POSIX Error : 9 SQLite Error : 3850
D/TimaKeyStoreProvider( 5496): TimaSignature is unavailable
D/ActivityThread( 5496): Added TimaKeyStore provider
W/FileUtils( 5480): Failed to chmod(/data/data/com.samsung.android.intelligenceservice/databases/predictor.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteLog( 5480): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/predictor.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5480): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/predictor.db'.
E/SQLiteDatabase( 5480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5480): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.getEnabledState(PlaceCategoryManager.java:76)
E/SQLiteDatabase( 5480): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:152)
E/SQLiteDatabase( 5480): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
E/SQLiteDatabase( 5480): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
E/SQLiteDatabase( 5480): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5480): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5480): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5480): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5480): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5480): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5480): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5480): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5480): Couldn't open predictor.db for writing (will try read-only):
E/SQLiteOpenHelper( 5480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 5480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 5480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 5480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5480): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5480): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.getEnabledState(PlaceCategoryManager.java:76)
E/SQLiteOpenHelper( 5480): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:152)
E/SQLiteOpenHelper( 5480): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
E/SQLiteOpenHelper( 5480): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
E/SQLiteOpenHelper( 5480): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 5480): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 5480): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5480): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 5480): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5480): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5480): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5480): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5480): Opened predictor.db in read-only mode
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
W/ResourcesManager( 5496): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
D/BluetoothAdapter( 5480): 450455060: getState() :  mService = null. Returning STATE_OFF
V/PlaceDetection v1.0.19 ( 5480): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 5480): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/SQLiteLog( 5480): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5480): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
E/SQLiteDatabase( 5480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5480): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
E/SQLiteDatabase( 5480): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 5480): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5480): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5480): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5480): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5480): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5480): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5480): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5480): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 5480): It failed to get the database for dump_log
E/SQLiteLog( 5480): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5480): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
E/SQLiteDatabase( 5480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5480): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5480): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
E/SQLiteDatabase( 5480): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 5480): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5480): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5480): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5480): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5480): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5480): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5480): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5480): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 5480): It failed to get the database for dump_log
D/RCPManager( 5496):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 1018):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 1018): queryAllProviders():  providerCallBack is not register for 0
D/FilterInstaller( 5162): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
W/ContextImpl( 5162): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
I/FilterInstaller( 5162): FilterPackageService : ACTION_PACKAGE_REMOVED
I/FilterInstaller( 5162): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5162): before removeFromFS
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5514): MountEmulatedStorage()
E/Zygote  ( 5514): v2
I/libpersona( 5514): KNOX_SDCARD checking this for 10095
I/libpersona( 5514): KNOX_SDCARD not a persona
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4938/cgroup.procs: No such file or directory
I/ActivityManager( 1018): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5514 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/SELinux ( 5514): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5514): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5514): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
