#### Test 50388019831b9e1_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
E/SMD     (  288): DCD OFF
,D/AndroidRuntime( 5270): 
D/AndroidRuntime( 5270): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5270): CheckJNI is OFF
D/AndroidRuntime( 5270): readGMSProperty: start
D/AndroidRuntime( 5270): readGMSProperty: already setted!!
D/AndroidRuntime( 5270): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5270): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5270): readGMSProperty: end
D/AndroidRuntime( 5270): addProductProperty: start
E/AffinityControl( 5270): AffinityControl: registerfunction enter
D/AndroidRuntime( 5270): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5282 uid=10346 gids={50346, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/libpersona( 5282): KNOX_SDCARD checking this for 10346
D/InputDispatcher( 1018): Focused application set to: xxxx
I/libpersona( 5282): KNOX_SDCARD not a persona
E/Zygote  ( 5282): MountEmulatedStorage()
E/Zygote  ( 5282): v2
D/InputDispatcher( 1018): Focus left window: 1476
I/SELinux ( 5282): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/AndroidRuntime( 5270): Shutting down VM
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 5282): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, iello
E/SELinux ( 5282): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5282): TimaSignature is unavailable
D/ActivityThread( 5282): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1018): Display changed displayId=0
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/Launcher( 1476): onTrimMemory. Level: 20
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/ActivityThread( 1476): updateVisibility : ActivityRecord{4a7db00 token=android.os.BinderProxy@c4e8f55 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
I/WebViewFactory( 5282): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5282): Time to load native libraries: 2 ms (timestamps 6177-6179)
I/LibraryLoader( 5282): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5282): Binding Chromium to main looper Looper (main, tid 1) {2dc0fd07}
I/LibraryLoader( 5282): Expected native library version number "",actual native library version number ""
I/chromium( 5282): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 5270): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/BrowserStartupController( 5282): Initializing chromium process, singleProcess=true,
,W/art     ( 5282): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5282): ApplicationContext is null in ApplicationStatus,
,W/chromium( 5282): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5282): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5282): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5282): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5282): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5282): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5282): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5282): Local Branch: 
I/Adreno-EGL( 5282): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5282): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5282):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5282): 171432352: getState() :  mService = null. Returning STATE_OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10011
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/NtpTrustedTime( 1018): forceRefresh Fail.
E/Zygote  ( 5322): MountEmulatedStorage()
E/Zygote  ( 5322): v2
I/libpersona( 5322): KNOX_SDCARD checking this for 10102
I/libpersona( 5322): KNOX_SDCARD not a persona
I/SELinux ( 5322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5322 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/art     ( 5282): Attempt to remove local handle scope entry from IRT, ignoring
I/SELinux ( 5322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5322): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/AwContents( 5282): onDetachedFromWindow called when already detached. Ignoring
,D/TimaKeyStoreProvider( 5322): TimaSignature is unavailable
,D/ActivityThread( 5322): Added TimaKeyStore provider
,D/PhoneWindow( 5282): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5282): *FMB* installDecor flags : 8456448
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/SystemWebViewEngine( 5282): CordovaWebView is running on device made by: samsung
,W/art     ( 5282): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5282): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 5322): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/OpenGLRenderer( 5282): Render dirty regions requested: true
,I/PowerManagerService( 1018): [PWL] Off : 30s ago
,I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{189987d4 u0 com.example.hello/.MainActivity t19}
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1941, ws=null) (elapsedTime=52228)
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/chromium( 5282): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5282): updateVisibility : ActivityRecord{27c38ac9 token=android.os.BinderProxy@19853a93 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/PhoneWindow( 5282): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5282): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1018): Focus entered window: 5282
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 5282): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5282): Initialized EGL, version 1.4
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 5282): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5282): Enabling debug mode 0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
,I/ActivityManager( 1018): Displayed Component not be shown by security: +612ms (total +714ms)
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{189987d4 u0 com.example.hello/.MainActivity t19} time:86701
W/ActivityManager( 1018): mDVFSHelper.release()
,I/SurfaceFlinger(  257): id=11 Removed iello (7/9)
,I/SurfaceFlinger(  257): id=11 Removed iello (-2/9)
,W/IInputConnectionWrapper( 5282): showStatusIcon on inactive InputConnection
,I/Timeline( 5282): Timeline: Activity_idle id: android.os.BinderProxy@19853a93 time:86722
,I/Babel_SMS( 5322): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5322): MmsConfig.loadMmsSettings
I/Babel_SMS( 5322): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 5322): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5322): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5322): MmsConfig.loadFromResources
,E/Babel_SMS( 5322): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5322): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,I/SamsungIME( 1772): getCurrentCandidateView
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  283): getCameraInfo: X
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5322): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5322): startup - clean
,I/Babel   ( 5322): deleted: false for 0
,D/SamsungIME( 1772): Dismiss ExpandCandiate
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/BindingManager( 5282): Cannot call determinedVisibility() - never saw a connection for the pid: 5282
,I/chromium( 5282): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/VideoCapabilities( 5322): Unrecognized profile 2130706433 for video/avc
,I/SamsungIME( 1772): getDebugLevel  : 0x4f4c
,W/AudioCapabilities( 5322): Unsupported mime audio/evrc
,W/AudioCapabilities( 5322): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5322): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5322): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5322): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5322): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5322): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5322): Unsupported mime audio/evrc
,W/VideoCapabilities( 5322): Unsupported mime video/wvc1
,W/VideoCapabilities( 5322): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5322): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5322): Unsupported mime video/wvc1
,W/VideoCapabilities( 5322): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5322): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5322): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5322): Unsupported mime video/mp43
,W/VideoCapabilities( 5322): Unsupported mime video/sorenson
,W/VideoCapabilities( 5322): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5322): Unsupported profile 4 for video/mp4v-es
,D/JsMessageQueue( 5282): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1772): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1772): KeybaordView init() : load resources
,E/AndroidProtocolHandler( 5282): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/VideoCapabilities( 5322): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5322): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5322): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5322): Unrecognized profile 2130706433 for video/avc
I/ActivityManager( 1018): Killing 4295:com.google.android.music:main/u0a108 (adj 15): empty #31
,I/vclib   ( 5322): onServiceConnected
,W/Babel   ( 5322): Attempted to change video mute state without an active call.
,I/SamsungIME( 1772): getCurrentKeyboard
I/SamsungIME( 1772): getTextKeyboard
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1772): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/libprocessgroup( 1018): failed to open /acct/uid_10108/pid_4295/cgroup.procs: No such file or directory
,D/jxcore_app_log( 5282): JniHelper::setJavaVM(0xb85fb448), pthread_self() = -1196039040
,D/JX-Cordova( 5282): jxcore cordova android initializing
,W/jxcore-log( 5282): Initializing JXcore engine
W/jxcore-log( 5282): JXcore engine is ready
,W/jxcore-log( 5282): Starting JXcore engine
,E/audit   ( 1797): type=1400 msg=audit(1451921655.431:203): avc:  denied  { ioctl } for  pid=5282 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1797):  SEPF_SM-A300FU_5.0.2_0027
,E/audit   ( 1797): type=1300 msg=audit(1451921655.431:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=bed49d58 items=0 ppid=309 ppcomm=main pid=5282 auid=4294967295 uid=10346 gid=10346 euid=10346 suid=10346 fsuid=10346 egid=10346 sgid=10346 fsgid=10346 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1797): type=1320 msg=audit(1451921655.431:203): 
,W/jxcore-log( 5282): Platform android
W/jxcore-log( 5282): 
W/jxcore-log( 5282): Process ARCH arm
W/jxcore-log( 5282): 
,I/jxcore-log( 5282): JXcore Cordova bridge is ready!,
I/jxcore-log( 5282): 
W/jxcore-log( 5282): JXcore engine is started
,E/jxcore-log( 5282): >> samsung-SM-A300FU
E/jxcore-log( 5282): 
,I/jxcore-log( 5282): Total memory 1451114496
I/jxcore-log( 5282): 
,I/jxcore-log( 5282): Free memory 30990336
I/jxcore-log( 5282): 
,I/jxcore-log( 5282): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5282): 
I/jxcore-log( 5282): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5282): 
,I/jxcore-log( 5282): userPath [ 'www' ]
I/jxcore-log( 5282): 
,I/jxcore-log( 5282): Size 540 960
I/jxcore-log( 5282): 
,I/jxcore-log( 5282): Screen Brightness 160
I/jxcore-log( 5282): 
,E/jxcore-log( 5282): Dummy Error Log.
E/jxcore-log( 5282): 
,E/SQLiteLog( 1686): (10) POSIX Error : 11 SQLite Error : 3850
,I/jxcore-log( 5282): getBuffer is called!!!!
I/jxcore-log( 5282): 
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BluetoothAdapter( 5282): disable()
,E/BluetoothManagerService( 1018): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: false pid=5282, uid=10346
,D/SettingsProvider( 1018): name = wifi_on
,I/jxcore-log( 5282): ****TEST TOOK:  5062  ms ****
I/jxcore-log( 5282): 
,I/jxcore-log( 5282): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5282): 
,D/AndroidRuntime( 5363): 
D/AndroidRuntime( 5363): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5363): CheckJNI is OFF,
D/AndroidRuntime( 5363): readGMSProperty: start
D/AndroidRuntime( 5363): readGMSProperty: already setted!!,
D/AndroidRuntime( 5363): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5363): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5363): readGMSProperty: end
D/AndroidRuntime( 5363): addProductProperty: start
,E/AffinityControl( 5363): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5363): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{724456581}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1018): !@killApplicatoin: 10346, uninstall pkg,
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10346 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 5282:com.example.hello/u0a346 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1018): Skipping PackageSetting{23101bdf com.test.thalitest/10338} due to missing metadata
,I/WindowState( 1018): WIN DEATH: Window{211cf3d2 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  257): id=12 Removed NainActivit (6/8)
,D/InputDispatcher( 1018): Focus left window: 5282
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{189987d4 u0 com.example.hello/.MainActivity t19}
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/InputDispatcher( 1018): Focused application released
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10346 user=0: pkg removed
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1018): Spurious death for ProcessRecord{2458b2da 5282:com.example.hello/u0a346}, curProc for 5282: null
,I/art     ( 3755): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 658us total 22.713ms
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010,
,E/SamsungIME( 1772): mOCRHelper is null
,I/art     ( 4106): Explicit concurrent mark sweep GC freed 19454(1237KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 1.477ms total 57.200ms
,I/KLMS-2.5.123: ( 3425): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 04 16:34:21 GMT+01:00 2016
,D/RegisteredServicesCache( 1441): empty dynamic service
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 65155(3MB) AllocSpace objects, 21(450KB) LOS objects, 33% free, 23MB/35MB, paused 3.697ms total 196.091ms
I/art     ( 1018): WaitForGcToComplete blocked for 189.291ms for cause Explicit
,D/RCPManagerService( 1018): PackageReceiver onReceive()
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10346
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10346
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
D/TaskPersister( 1018): removeObsoleteFile: deleting file=19_task.xml
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 13114(676KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.932ms total 166.156ms
,I/art     ( 1018): WaitForGcToComplete blocked for 333.905ms for cause Explicit
,D/PackageManager( 1018): delete codoeFile: 
,D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10346, packageName = com.example.hello
,I/AASA_removePackage( 1018): UID=10346 Target=com.example.hello
,D/PackageManager( 1018): result of delete: 1{724456581}
,D/AndroidRuntime( 5363): Shutting down VM
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 4034(286KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.275ms total 137.310ms
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,W/GeofencerStateMachine( 1632): Ignoring removeGeofence because network location is disabled.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3425): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
W/TextServicesManagerService( 1018): no available spell checker services found
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 5376): MountEmulatedStorage()
E/Zygote  ( 5376): v2
I/libpersona( 5376): KNOX_SDCARD checking this for 10090
I/libpersona( 5376): KNOX_SDCARD not a persona
,I/KLMS-2.5.123: ( 3425): KLMSIntentService(): onCreate()
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5376 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 5376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3425): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/SELinux ( 5376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 5376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/KLMS-2.5.123: ( 3425): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3425): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3425): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3425): KLMSIntentService(): listeningToPackageRemoved().START
,I/art     (  309): Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 23.914ms
,I/KLMS-2.5.123: ( 3425): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/TimaKeyStoreProvider( 5376): TimaSignature is unavailable,
D/ActivityThread( 5376): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 4(112B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 567us total 17.641ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.465ms
,D/elm:15121( 5376): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5376): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5376): MDMBridge.setEnterpriseBridge()
,I/KLMS-2.5.123: ( 3425): KLMSIntentService(): listeningToPackageRemoved().END
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,W/art     ( 5363): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,D/elm:15121( 5376): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 5376): ElmAgentService : onCreate()
,I/KLMS-2.5.123: ( 3425): KLMSIntentService(): onDestroy()
,D/elm:15121( 5376): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 5376): MainReceiver.listeningToPackageRemoved()
,D/elm:15121( 5376): MDMBridge.getInstance()
D/elm:15121( 5376): MDMBridge.getAllLicenseInfoFromSDK()
,I/PCWCLIENTTRACE_PushUtil( 5045): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5045): sales region : global
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
I/PCWCLIENTTRACE_PushUtil( 5045): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5045): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 5376): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SA      ( 5201): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5201): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10346 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,D/elm:15121( 5376): ElmAgentService : onDestroy().
,I/ActivityManager( 1018): Killing 4866:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackagesMonitor( 4363): PackagesMonitor onReceive :com.example.hello
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
D/UsbSettingsManager( 1018): clearDefaults: com.example.hello
I/CrashAnrDetector( 1018): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4866/cgroup.procs: No such file or directory
,D/Mms/FreeMessageStatusReceiver( 4205): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/Mms/FreeMessageReceiverService( 4205): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4205): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1018): enable value -1,
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
,I/TactileAssist( 1018): saveAppList value true
,I/TactileAssist( 1018): List of disabled apps :
,D/Compatibility( 5077): onReceive() it will make start service
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5077): onHandleIntent()
,D/Compatibility( 5077): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10346, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5077): found: 2
,D/Compatibility( 5077): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5077): skipping ResolveInfo{de662a3 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
,D/Compatibility( 5077): considering ResolveInfo{a37d9a0 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5077): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5077): enabling receiver ResolveInfo{fd69959 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5077): enabling receiver ResolveInfo{14ee991e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/Zygote  ( 5397): MountEmulatedStorage()
,E/Zygote  ( 5397): v2
I/libpersona( 5397): KNOX_SDCARD checking this for 10055
I/libpersona( 5397): KNOX_SDCARD not a persona
,I/SELinux ( 5397): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5397): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5397 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 5397): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/Compatibility( 5077): enabling receiver ResolveInfo{277285ff com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/Compatibility( 5077): enabling receiver ResolveInfo{12d0efcc com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5077): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/TimaKeyStoreProvider( 5397): TimaSignature is unavailable
,D/ActivityThread( 5397): Added TimaKeyStore provider

```
