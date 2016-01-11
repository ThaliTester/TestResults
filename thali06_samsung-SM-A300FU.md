#### Test 50242285feafdeb_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 5303): 
D/AndroidRuntime( 5303): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5303): CheckJNI is OFF
D/AndroidRuntime( 5303): readGMSProperty: start
D/AndroidRuntime( 5303): readGMSProperty: already setted!!
D/AndroidRuntime( 5303): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5303): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5303): readGMSProperty: end
D/AndroidRuntime( 5303): addProductProperty: start
W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
E/AffinityControl( 5303): AffinityControl: registerfunction enter
D/AndroidRuntime( 5303): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1022): inState():  stateMachine is null !!
I/PersonaManagerService( 1022): PersonaId don't exist
I/ActivityManager( 1022): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
W/ActivityManager( 1022): mDVFSHelper.acquire()
D/FocusedStackFrame( 1022): Set to : 0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1022): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1022): *FMB* installDecor flags : 25362712
E/Zygote  ( 5315): MountEmulatedStorage()
E/Zygote  ( 5315): v2
I/libpersona( 5315): KNOX_SDCARD checking this for 10346
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1022): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5315 uid=10346 gids={50346, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/libpersona( 5315): KNOX_SDCARD not a persona
D/InputDispatcher( 1022): Focused application set to: xxxx
D/InputDispatcher( 1022): Focus left window: 1480
D/AndroidRuntime( 5303): Shutting down VM
I/SELinux ( 5315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 5315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, iello
E/SELinux ( 5315): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5315): TimaSignature is unavailable
D/ActivityThread( 5315): Added TimaKeyStore provider
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
V/WindowManager( 1022): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
V/ActivityManager( 1022): Display changed displayId=0
D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1022): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1480): updateVisibility : ActivityRecord{3ee6524f token=android.os.BinderProxy@34a298bc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1480): onTrimMemory. Level: 20
I/WebViewFactory( 5315): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5315): Time to load native libraries: 1 ms (timestamps 4129-4130)
I/LibraryLoader( 5315): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5315): Binding Chromium to main looper Looper (main, tid 1) {11e976e4}
I/LibraryLoader( 5315): Expected native library version number "",actual native library version number ""
I/chromium( 5315): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 5303): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/BrowserStartupController( 5315): Initializing chromium process, singleProcess=true
W/art     ( 5315): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5315): ApplicationContext is null in ApplicationStatus
W/chromium( 5315): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5315): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5315): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5315): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5315): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5315): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5315): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5315): Local Branch: 
I/Adreno-EGL( 5315): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5315): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5315):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/BluetoothAdapter( 5315): 495664206: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5315): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5315): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5315): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5315): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5315): CordovaWebView is running on device made by: samsung
W/art     ( 5315): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5315): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5315): Render dirty regions requested: true
D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
W/chromium( 5315): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PhoneWindow( 5315): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5315): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1022): Focus entered window: 5315
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5315): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5315): Initialized EGL, version 1.4
D/OpenGLRenderer( 5315): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5315): Enabling debug mode 0
V/ActivityThread( 5315): updateVisibility : ActivityRecord{1f6554fe token=android.os.BinderProxy@6b67a80 {com.example.hello/com.example.hello.MainActivity}} show : true
D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
W/IInputConnectionWrapper( 5315): showStatusIcon on inactive InputConnection
I/Timeline( 5315): Timeline: Activity_idle id: android.os.BinderProxy@6b67a80 time:84641
I/ActivityManager( 1022): Displayed Component not be shown by security: +613ms (total +688ms)
I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{342aa7b5 u0 com.example.hello/.MainActivity t19} time:84651
W/ActivityManager( 1022): mDVFSHelper.release()
I/SurfaceFlinger(  258): id=11 Removed iello (7/9)
I/SurfaceFlinger(  258): id=11 Removed iello (-2/9)
I/SamsungIME( 1787): getCurrentCandidateView
D/SamsungIME( 1787): Dismiss ExpandCandiate
W/BindingManager( 5315): Cannot call determinedVisibility() - never saw a connection for the pid: 5315
I/chromium( 5315): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/SamsungIME( 1787): getDebugLevel  : 0x4f4c
I/SamsungIME( 1787): getDebugLevel  : 0x4f4c
I/SamsungIME( 1787): KeybaordView init() : load resources
I/SamsungIME( 1787): getCurrentKeyboard
I/SamsungIME( 1787): getTextKeyboard
D/SamsungIME( 1787): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 5315): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 5315): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/jxcore_app_log( 5315): JniHelper::setJavaVM(0xb6fe0448), pthread_self() = -1224835480
E/SMD     (  296): DCD OFF
W/jxcore-log( 5315): Initializing JXcore engine
W/jxcore-log( 5315): JXcore engine is ready
E/audit   ( 1784): type=1400 msg=audit(1452552511.835:203): avc:  denied  { ioctl } for  pid=5364 comm="Thread-912" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1784):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1784): type=1300 msg=audit(1452552511.835:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9d4b28f8 items=0 ppid=322 ppcomm=main pid=5364 auid=4294967295 uid=10346 gid=10346 euid=10346 suid=10346 fsuid=10346 egid=10346 sgid=10346 fsgid=10346 ses=4294967295 tty=(none) comm="Thread-912" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1784): type=1320 msg=audit(1452552511.835:203): 
,W/jxcore-log( 5315): Starting JXcore engine,
,W/jxcore-log( 5315): Platform android,
W/jxcore-log( 5315): 
W/jxcore-log( 5315): Process ARCH arm
W/jxcore-log( 5315): 
,I/jxcore-log( 5315): JXcore Cordova bridge is ready!,
I/jxcore-log( 5315): 
W/jxcore-log( 5315): JXcore engine is started
,E/jxcore  ( 5315): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 5315): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/PhoneWindow( 5315): *FMB* installDecor mIsFloating : true
,D/PhoneWindow( 5315): *FMB* installDecor flags : 8388610
,D/InputDispatcher( 1022): Focus left window: 5315
,D/InputDispatcher( 1022): Focus entered window: 5315
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,D/PhoneWindow( 5315): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5315): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=4, NainActivit
D/SRIB_DCS( 5315): log_dcs ThreadedRenderer::initialize entered! 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 270,
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged,
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,I/PowerManagerService( 1022): [PWL] Off : 50s ago,
,V/AlarmManager( 1022): waitForAlarm result :4,
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10011
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5376): MountEmulatedStorage()
,E/Zygote  ( 5376): v2
I/libpersona( 5376): KNOX_SDCARD checking this for 10102
,I/libpersona( 5376): KNOX_SDCARD not a persona
,I/SELinux ( 5376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1022): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5376 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 5376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5376): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5376): TimaSignature is unavailable
,D/ActivityThread( 5376): Added TimaKeyStore provider
,W/ResourcesManager( 5376): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 54964(3MB) AllocSpace objects, 24(498KB) LOS objects, 33% free, 23MB/35MB, paused 2.103ms total 169.115ms
,I/Babel_SMS( 5376): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5376): MmsConfig.loadMmsSettings
I/Babel_SMS( 5376): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 5376): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5376): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5376): MmsConfig.loadFromResources
,E/Babel_SMS( 5376): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5376): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/QCamera2Factory(  287): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  287): getCameraInfo: X
,W/QCamera2Factory(  287): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  287): getCameraInfo: X
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5376): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5376): startup - clean
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 5376): deleted: false for 0
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4747): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4747): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4747): [1] 5.onFinished: Scheduling replication attempt 2.
,W/VideoCapabilities( 5376): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5376): Unsupported mime audio/evrc
,W/AudioCapabilities( 5376): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5376): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5376): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5376): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5376): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5376): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5376): Unsupported mime audio/evrc
,W/VideoCapabilities( 5376): Unsupported mime video/wvc1
,W/VideoCapabilities( 5376): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5376): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5376): Unsupported mime video/wvc1
,W/VideoCapabilities( 5376): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5376): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5376): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5376): Unsupported mime video/mp43
,W/VideoCapabilities( 5376): Unsupported mime video/sorenson
,W/VideoCapabilities( 5376): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5376): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5376): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5376): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5376): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5376): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1022): Killing 4361:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,I/vclib   ( 5376): onServiceConnected
,W/Babel   ( 5376): Attempted to change video mute state without an active call.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1022): failed to open /acct/uid_10035/pid_4361/cgroup.procs: No such file or directory,
,E/SQLiteLog( 1698): (10) POSIX Error : 11 SQLite Error : 3850,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/FactoryTest( 4648): Not factory mode
D/FactoryTest( 4648): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4648): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4648): still no open session command from host, so toast
,W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4648): Timeline: Activity_launch_request id:com.android.settings time:106757
,E/PersonaManagerService( 1022): inState():  stateMachine is null !!
,I/PersonaManagerService( 1022): PersonaId don't exist
,I/ActivityManager( 1022): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1022): mDVFSHelper.acquire()
,D/PersonaManager( 1022): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1022): Focused application set to: xxxx
,D/InputDispatcher( 1022): Focus left window: 5315
,E/MTPRx   ( 4648): started activity for popup
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 4648): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4648): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4648): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4648): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4648): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4648): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4648): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/InputDispatcher( 1022): Focused application set to: xxxx
,D/InputDispatcher( 1022): Focus entered window: 5315
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,D/SettingsReceiverActivity( 4648): dev.kiessupport is : TRUE
,D/PhoneWindow( 4648): *FMB* installDecor mIsFloating : true
,D/PhoneWindow( 4648): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
,V/ActivityThread( 5315): updateVisibility : ActivityRecord{1f6554fe token=android.os.BinderProxy@6b67a80 {com.example.hello/com.example.hello.MainActivity}} show : true
,I/Timeline( 5315): Timeline: Activity_idle id: android.os.BinderProxy@6b67a80 time:106940
,D/PersonaManager( 1022): isKioskContainerExistOnDevice
,E/Watchdog( 1022): !@Sync 3
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  296): DCD OFF
,W/ActivityManager( 1022): mDVFSHelper.release()
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,V/AlarmManager( 1022): waitForAlarm result :4
,V/AlarmManager( 1022): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1022): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1022): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1698): Explicit concurrent mark sweep GC freed 20544(1179KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.160ms total 52.412ms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4747): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4747): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4747): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1022): [PWL] Off : 75s ago
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1022): !@Sync 4,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  296): DCD OFF,
,V/AlarmManager( 1022): waitForAlarm result :4
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4747): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4747): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4747): [1] 5.onFinished: Scheduling replication attempt 4.
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1022): [PWL] Off : 105s ago
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1022): waitForAlarm result :4
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4747): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4747): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4747): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  296): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1022): !@Sync 5
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,V/AlarmManager( 1022): waitForAlarm result :4,
D/NtpTrustedTime( 1022): forceRefresh() from cache miss
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1022): forceRefresh Fail.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000,
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4747): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4747): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4747): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  296): DCD OFF,
,I/PowerManagerService( 1022): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged,
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/Watchdog( 1022): !@Sync 6,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/Watchdog( 1022): !@Sync 7,
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 180s ago
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,V/AlarmManager( 1022): waitForAlarm result :8
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  296): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,V/AlarmManager( 1022): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
D/NtpTrustedTime( 1022): forceRefresh() from cache miss
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1022): forceRefresh Fail.
D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10011
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  296): DCD OFF
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 5472): 
D/AndroidRuntime( 5472): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5472): CheckJNI is OFF
D/AndroidRuntime( 5472): readGMSProperty: start
D/AndroidRuntime( 5472): readGMSProperty: already setted!!
D/AndroidRuntime( 5472): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5472): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5472): readGMSProperty: end
D/AndroidRuntime( 5472): addProductProperty: start
E/AffinityControl( 5472): AffinityControl: registerfunction enter
D/AndroidRuntime( 5472): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1022): START PACKAGE DELETE: observer{41182830}
D/PackageManager( 1022): pkg{<packageName>}
D/PackageManager( 1022): user{0}
D/PackageManager( 1022): caller{2000}
D/PackageManager( 1022): flags{3}
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1022): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1022): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1022): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1022): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1022): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1022): !@killApplicatoin: 10346, uninstall pkg
I/ActivityManager( 1022): Force stopping com.example.hello appid=10346 user=-1: uninstall pkg
I/ActivityManager( 1022): Killing 5315:com.example.hello/u0a346 (adj 0): stop com.example.hello cause uninstall pkg
W/PackageSettings( 1022): Skipping PackageSetting{35c22e29 com.test.thalitest/10338} due to missing metadata
I/WindowState( 1022): WIN DEATH: Window{3e543676 u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger(  258): id=13 Removed NainActivit (7/9)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/9)
D/InputDispatcher( 1022): Focus left window: 5315
D/InputDispatcher( 1022): Focus entered window: 5315
I/SurfaceFlinger(  258): id=12 Removed NainActivit (5/8)
I/WindowState( 1022): WIN DEATH: Window{3931547f u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
D/InputDispatcher( 1022): Focus left window: 5315
I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1022):   Force finishing activity ActivityRecord{342aa7b5 u0 com.example.hello/.MainActivity t19}
D/InputDispatcher( 1022): Focused application released
I/ActivityManager( 1022): Force stopping com.example.hello appid=10346 user=0: pkg removed
W/ActivityManager( 1022): CustomStartingWindow se packge removed so remove capture also
W/ActivityManager( 1022): Spurious death for ProcessRecord{29d9510f 5315:com.example.hello/u0a346}, curProc for 5315: null
I/art     ( 3688): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 1.197ms total 28.189ms
I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1787): mOCRHelper is null
W/GeofencerStateMachine( 1641): Ignoring removeGeofence because network location is disabled.
I/art     ( 4132): Explicit concurrent mark sweep GC freed 22861(1688KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 1.782ms total 64.613ms
I/KLMS-2.5.123: ( 3465): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 23:51:12 GMT+01:00 2016
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3465): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1022): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1022): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1022): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5485): MountEmulatedStorage()
I/libpersona( 5485): KNOX_SDCARD checking this for 10090
E/Zygote  ( 5485): v2
I/libpersona( 5485): KNOX_SDCARD not a persona
I/SELinux ( 5485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5485 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 5485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/EnterpriseDeviceManagerService( 1022): Package has changed for user 0
W/TextServicesManagerService( 1022): no available spell checker services found
D/EnterpriseDeviceManagerService( 1022): Admin package name: com.google.android.gms
E/SELinux ( 5485): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3465): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3465): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.123: ( 3465): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.123: ( 3465): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/TimaKeyStoreProvider( 5485): TimaSignature is unavailable
D/ActivityThread( 5485): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3465): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3465): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3465): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1022): mCursor = null
D/RegisteredServicesCache( 1439): empty dynamic service
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     ( 1022): Explicit concurrent mark sweep GC freed 40850(3MB) AllocSpace objects, 61(976KB) LOS objects, 33% free, 23MB/35MB, paused 2.735ms total 217.811ms
I/art     ( 1022): WaitForGcToComplete blocked for 212.863ms for cause Explicit
D/elm:15121( 5485): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 5485): ELMEngine.ELMEngine( context ).
D/elm:15121( 5485): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 5485): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 5485): ElmAgentService : onCreate()
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:15121( 5485): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 5485): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5485): MDMBridge.getInstance()
D/elm:15121( 5485): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 5485): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.123: ( 3465): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3465): KLMSIntentService(): onDestroy()
D/elm:15121( 5485): ElmAgentService : onDestroy().
I/ActivityManager( 1022): Killing 4310:com.google.android.music:main/u0a108 (adj 15): empty #31
D/RCPManagerService( 1022): PackageReceiver onReceive()
I/HarmonyEASService( 1022): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1022): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
W/ResourceType( 1022): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1022): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     ( 1022): Explicit concurrent mark sweep GC freed 12886(659KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.801ms total 176.358ms
D/PackageManager( 1022): delete codoeFile: 
D/AASAuninstall( 1022): userId = 0, info.removedAppID = -1, info.uid = 10346, packageName = com.example.hello
I/AASA_removePackage( 1022): UID=10346 Target=com.example.hello
D/PackageManager( 1022): result of delete: 1{41182830}
D/AndroidRuntime( 5472): Shutting down VM
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1022): clearDefaults: com.example.hello
I/CrashAnrDetector( 1022): onPackageRemoved : com.example.hello
W/libprocessgroup( 1022): failed to open /acct/uid_10108/pid_4310/cgroup.procs: No such file or directory
D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1022): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1022): uID is 10346
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1022): uID is 10346
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
D/SSRM:aZ ( 1022): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.example.hello
D/TaskPersister( 1022): removeObsoleteFile: deleting file=19_task.xml
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
I/PCWCLIENTTRACE_PushUtil( 5062): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5062): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5062): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5062): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5172): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5172): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10346 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 4376): PackagesMonitor onReceive :com.example.hello
D/Mms/FreeMessageStatusReceiver( 4231): onReceive, action : android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1022): enable value -1
I/TactileAssist( 1022): internal enable value -1
I/TactileAssist( 1022): intensity value -1
I/TactileAssist( 1022): saveAppList value true
D/Mms/FreeMessageReceiverService( 4231): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4231): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1022): List of disabled apps :
D/Compatibility( 5155): onReceive() it will make start service
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5155): onHandleIntent()
D/Compatibility( 5155): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10346, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5155): found: 2
D/Compatibility( 5155): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5155): skipping ResolveInfo{1a391d50 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5155): considering ResolveInfo{d200b49 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5155): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5155): enabling receiver ResolveInfo{1d8b3c4e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/Zygote  ( 5508): MountEmulatedStorage()
E/Zygote  ( 5508): v2
I/libpersona( 5508): KNOX_SDCARD checking this for 10055
I/libpersona( 5508): KNOX_SDCARD not a persona
I/SELinux ( 5508): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/Compatibility( 5155): enabling receiver ResolveInfo{32fca16f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/ActivityManager( 1022): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5508 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5508): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5508): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5155): enabling receiver ResolveInfo{399abe7c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5155): enabling receiver ResolveInfo{3cd51305 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/Compatibility( 5155): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 5508): TimaSignature is unavailable
D/ActivityThread( 5508): Added TimaKeyStore provider
W/art     ( 5472): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/UserAnalysis.PlaceProvider( 5508): PlaceProvider onCreate()
D/UserAnalysis.SecureDbManager( 5508): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 5508): SecurePlaceDbHelper() 
D/UserAnalysis( 5508): Create SecureDbHelper
D/IntelligenceServiceApplication( 5508): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 5508): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/ContextImpl( 5191): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/IntelligenceServiceApplication( 5508): no applications having user consent for prediction
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
V/PlaceDetection v1.0.19 ( 5508): [PlaceDetection::stopService] Service stopped.
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
V/PlaceDetection v1.0.19 ( 5508): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
W/FileUtils( 5508): Failed to chmod(/data/data/com.samsung.android.intelligenceservice/databases/privacy): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Zygote  ( 5526): MountEmulatedStorage()
E/Zygote  ( 5526): v2
I/libpersona( 5526): KNOX_SDCARD checking this for 1000
I/libpersona( 5526): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5526 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/FileUtils( 5191): Failed to chmod(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteLog( 5191): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 5191): (3850) statement aborts at 16: [DELETE FROM AMData WHERE appname=?] disk I/O error
W/System.err( 5191): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
I/SELinux ( 5526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/System.err( 5191): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/System.err( 5191): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
W/System.err( 5191): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/System.err( 5191): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 5191): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
W/System.err( 5191): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:161)
W/System.err( 5191): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
W/System.err( 5191): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/ActivityManager( 1022): Killing 4883:com.sec.android.diagmonagent/1000 (adj 15): empty #31
W/System.err( 5191): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5191): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5191): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 5508): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/predictor.db" with flag (131138) and mode_t (0) due to error (30)
I/SELinux ( 5526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SQLiteDatabase( 5508): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/predictor.db'.
E/SQLiteDatabase( 5508): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5508): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5508): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5508): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5508): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.removePlaceCategories(PlaceCategoryManager.java:65)
E/SQLiteDatabase( 5508): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:150)
E/SQLiteDatabase( 5508): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
E/SQLiteDatabase( 5508): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
E/SQLiteDatabase( 5508): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5508): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5508): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5508): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5508): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5508): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5508): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5508): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 5508): Shutting down VM
E/AndroidRuntime( 5508): FATAL EXCEPTION: main
E/AndroidRuntime( 5508): Process: com.samsung.android.intelligenceservice, PID: 5508
E/AndroidRuntime( 5508): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5508): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5508): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 5508): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 5508): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5508): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5508): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5508): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 5508): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 5508): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 5508): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 5508): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 5508): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5508): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5508): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.removePlaceCategories(PlaceCategoryManager.java:65)
E/AndroidRuntime( 5508): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:150)
E/AndroidRuntime( 5508): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
E/AndroidRuntime( 5508): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
E/AndroidRuntime( 5508): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5508): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5508): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5508): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 5508): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5508): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5508): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 5508): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SELinux ( 5526): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
E/DropBoxManagerService( 1022): Can't write: system_app_crash
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop161.tmp: open failed: EROFS (Read-only file system)
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
I/Process ( 5508): Sending signal. PID: 5508 SIG: 9
D/TimaKeyStoreProvider( 5526): TimaSignature is unavailable
D/ActivityThread( 5526): Added TimaKeyStore provider
W/ResourcesManager( 5526): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/RCPManager( 5526):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 1022):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 1022): queryAllProviders():  providerCallBack is not register for 0
D/FilterInstaller( 5210): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
W/ContextImpl( 5210): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
E/lowmemorykiller(  255): Error writing /proc/5508/oom_score_adj; errno=22

```
