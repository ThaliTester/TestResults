#### Test 56151093c886730_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
,E/SMD     (  292): DCD OFF
--------- beginning of system
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/AndroidRuntime( 5418): 
D/AndroidRuntime( 5418): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5418): CheckJNI is OFF
D/AndroidRuntime( 5418): readGMSProperty: start
D/AndroidRuntime( 5418): readGMSProperty: already setted!!
D/AndroidRuntime( 5418): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5418): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5418): readGMSProperty: end
D/AndroidRuntime( 5418): addProductProperty: start
E/AffinityControl( 5418): AffinityControl: registerfunction enter
D/AndroidRuntime( 5418): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5430): MountEmulatedStorage()
E/Zygote  ( 5430): v2
I/libpersona( 5430): KNOX_SDCARD checking this for 10338
I/libpersona( 5430): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5430 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1477
I/SELinux ( 5430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/AndroidRuntime( 5418): Shutting down VM
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
I/SELinux ( 5430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
E/SELinux ( 5430): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, uhalitest
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5430): TimaSignature is unavailable
D/ActivityThread( 5430): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1477): updateVisibility : ActivityRecord{74d5077 token=android.os.BinderProxy@1158eca9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1477): onTrimMemory. Level: 20
I/WebViewFactory( 5430): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5430): Time to load native libraries: 1 ms (timestamps 4943-4944)
I/LibraryLoader( 5430): Expected native library version number "",actual native library version number ""
W/art     ( 5418): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 5430): Binding Chromium to main looper Looper (main, tid 1) {353b5cb5}
,I/LibraryLoader( 5430): Expected native library version number "",actual native library version number ""
,I/chromium( 5430): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5430): Initializing chromium process, singleProcess=true
,W/art     ( 5430): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5430): ApplicationContext is null in ApplicationStatus
,W/chromium( 5430): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5430): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5430): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5430): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5430): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5430): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5430): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5430): Local Branch: 
I/Adreno-EGL( 5430): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5430): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5430):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5430): 266980247: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5430): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5430): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5430): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5430): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5430): CordovaWebView is running on device made by: samsung
,W/art     ( 5430): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5430): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{16e5f49e u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 5430): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false,
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,W/chromium( 5430): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5430): updateVisibility : ActivityRecord{323ec887 token=android.os.BinderProxy@b1426a1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 5430): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5430): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1018): Focus entered window: 5430
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5430): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5430): Initialized EGL, version 1.4
D/OpenGLRenderer( 5430): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5430): Enabling debug mode 0
D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
I/Timeline( 5430): Timeline: Activity_idle id: android.os.BinderProxy@b1426a1 time:155485
W/IInputConnectionWrapper( 5430): showStatusIcon on inactive InputConnection
I/ActivityManager( 1018): Displayed Component not be shown by security: +706ms (total +49s126ms)
W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{16e5f49e u0 com.test.thalitest/.MainActivity t20} time:155496
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SurfaceFlinger(  258): id=11 Removed uhalitest (7/9)
I/SurfaceFlinger(  258): id=11 Removed uhalitest (-2/9)
I/SamsungIME( 1788): getCurrentCandidateView
D/SamsungIME( 1788): Dismiss ExpandCandiate
I/SamsungIME( 1788): getDebugLevel  : 0x4f4c
I/SamsungIME( 1788): getDebugLevel  : 0x4f4c
W/BindingManager( 5430): Cannot call determinedVisibility() - never saw a connection for the pid: 5430
I/SamsungIME( 1788): KeybaordView init() : load resources
I/SamsungIME( 1788): getCurrentKeyboard
I/SamsungIME( 1788): getTextKeyboard
D/SamsungIME( 1788): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 5430): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 5430): JniHelper::setJavaVM(0xb84df448), pthread_self() = -1197251832
D/JX-Cordova( 5430): jxcore cordova android initializing
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,E/SMD     (  292): DCD OFF
,W/jxcore-log( 5430): Initializing JXcore engine
W/jxcore-log( 5430): JXcore engine is ready
,W/jxcore-log( 5430): Starting JXcore engine
,E/audit   ( 1798): type=1400 msg=audit(1453034356.519:203): avc:  denied  { ioctl } for  pid=5430 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1798):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1798): type=1300 msg=audit(1453034356.519:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=beb44d58 items=0 ppid=322 ppcomm=main pid=5430 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1798): type=1320 msg=audit(1453034356.519:203): 
,W/jxcore-log( 5430): Platform android
W/jxcore-log( 5430): 
W/jxcore-log( 5430): Process ARCH arm
W/jxcore-log( 5430): 
,I/jxcore-log( 5430): JXcore Cordova bridge is ready!
I/jxcore-log( 5430): 
,W/jxcore-log( 5430): JXcore engine is started
I/Choreographer( 5430): Skipped 154 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5430): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5430): Toggling radios to true
I/jxcore-log( 5430): 
,D/BluetoothAdapter( 5430): enable()
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=5430, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 1018): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5430, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
W/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
W/BluetoothManagerService( 1018): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/BluetoothManagerService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
,E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 1018): name = bluetooth_on
,E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5481): MountEmulatedStorage(),
I/ActivityManager( 1018): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5481 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
E/Zygote  ( 5481): v2
I/libpersona( 5481): KNOX_SDCARD checking this for 1002
I/libpersona( 5481): KNOX_SDCARD not a persona
,I/SELinux ( 5481): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled,
D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
,I/SELinux ( 5481): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5481): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/WifiService( 1018): setWifiEnabled: true pid=5430, uid=10338
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=5430, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1018): Failed getting userId using ActivityManagerNative
W/WifiService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5430, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1018): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1018): 	at android.os.Binder.execTransact(Binder.java:461),
D/SettingsProvider( 1018): name = wifi_on
,I/WifiService( 1018): disconnect: pid=5430, uid=10338
,I/jxcore-log( 5430): Radios toggled
I/jxcore-log( 5430): 
,I/jxcore-log( 5430): My device name is: samsung-SM-A300FU,
I/jxcore-log( 5430): 
,E/WifiHW  ( 1018): ##################### set firmware type 0 #####################
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/TimaKeyStoreProvider( 5481): TimaSignature is unavailable
,D/ActivityThread( 5481): Added TimaKeyStore provider
,W/ResourcesManager( 5481): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 5481): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.,
,I/BluetoothA2dpSinkServiceJni( 5481): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 5481): Adding GattService
,D/BtSettings.ProfileConfig( 5481): Adding HeadsetService
,D/BtSettings.ProfileConfig( 5481): Adding A2dpService
D/BtSettings.ProfileConfig( 5481): Adding HidService
D/BtSettings.ProfileConfig( 5481): Adding HealthService
,D/BtSettings.ProfileConfig( 5481): Adding PanService
D/BtSettings.ProfileConfig( 5481): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 5481): Adding SapService
,D/BtSettings.ProfileConfig( 5481): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 5481): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 5481): Adding SapClientService
,D/BtSettings.ProfileConfig( 5481): Adding HidDevService
I/BtSettings.ProfileConfig( 5481): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.gatt.GattService,
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1,
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/BluetoothAdapterState( 5481): make
I/bluedroid( 5481): init
I/BluetoothAdapterState( 5481): Entering OffState
,I/bte_conf( 5481): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5481): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 5481): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5481): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
E/bt-btif ( 5481): btif_fetch_local_ble_random_bdaddr
I/bluedroid( 5481): get_profile_interface socket
I/bluedroid( 5481): get_profile_interface map_client
D/BluetoothAdapterService( 5481): checkAddrForIOP: Loading from conf,
,I/GKI_LINUX( 5481): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5481): Address is:08:EC:A9:50:75:41
,E/BluetoothServiceJni( 5481): populateRssiValuesNative
I/bluedroid( 5481): getModelRssiValues
E/BluetoothServiceJni( 5481): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/BluetoothAdapterProperties( 5481): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 5481): Name is: A3-1
,D/SettingsProvider( 1018): name = bluetooth_name
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/bluedroid( 5481): config_hci_snoop_log
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothManagerService( 1018): Ble is always on enable gatt
,I/BluetoothManagerService( 1018): enableGattForLeMode, doBind called
,E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
D/SecContentProvider( 1018): uri = 3 selection = isBluetoothEnabled
,I/BtGatt.JNI( 5481): classInitNative(L900): classInitNative: Success!
,D/BluetoothAdapterState( 5481): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothAdapterProperties( 5481): Setting state to 11
I/BluetoothAdapterState( 5481): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 5481): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5481): updateAdapterState state is 11
,D/BluetoothAdapterService( 5481): Autoconnection is available 
D/BluetoothAdapterService( 5481): updateAdapterState prevState = 10newState = 11
,W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1018): [BT Setting State] State =11
,D/BluetoothSecureManager( 5481): getInstant: null
,D/BluetoothSecureManager( 5481): calling getMethod for getService
D/BluetoothSecureManager( 5481): calling getService
D/BluetoothSecureManager( 5481): getService return binder: android.os.BinderProxy@9991f0
,D/BluetoothSecureManagerService( 1018): isSecureModeEnabled
,D/BluetoothSecureManagerService( 1018): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 5481): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5481): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,W/BluetoothAdapterService( 5481): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/BluetoothTile( 1174): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1174):  getBluetoothState : 11
,W/BluetoothAdapterService( 5481): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5481): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,I/SamsungIME( 1788): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/BluetoothAdapterService( 5481): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5481): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5481): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothTile( 1174):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1174): onStateChanged: Bluetooth
,W/BluetoothAdapterService( 5481): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5481): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5481): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5481): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5481): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine( 5481): make
,D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1174): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
W/BluetoothAdapterService( 5481): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5481): Not skipping com.android.bluetooth.gatt.GattService
,I/BluetoothBondStateMachine( 5481): StableState(): Entering Off State
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5481): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5481): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 5481): handleDebugAction() action=null
,D/BtGatt.GattService( 5481): Received start request. Starting profile...
,D/BtGatt.GattService( 5481): start()
D/BtGatt.GattService( 5481): start()
,I/bluedroid( 5481): get_profile_interface gatt
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 5481): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3383febb
D/BtGatt.AdvertiseManager( 5481): advertise manager created
,W/BluetoothAdapterService( 5481): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5481): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5481): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5481): Not skipping com.android.bluetooth.hid.HidService
,D/BtGatt.GattService( 5481): mStartError = false
,D/BluetoothAdapterService( 5481): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3383febb
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5481): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BluetoothNotiBroadcastReceiver( 1290): onReceive
,D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5481): Not skipping com.android.bluetooth.hdp.HealthService
,D/HeadsetService( 5481): Received start request. Starting profile...
D/HeadsetService( 5481): start()
,I/BluetoothHeadsetServiceJni( 5481): classInitNative: succeeds
,D/HeadsetStateMachine( 5481): make
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,V/BluetoothStatusReceiver( 1174): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1174): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,E/HeadsetStateMachine( 5481): # of Max HF connection is 2
,W/BluetoothAdapterService( 5481): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5481): Not skipping com.android.bluetooth.pan.PanService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5481): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5481): Not skipping com.android.bluetooth.map.BluetoothMapService
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5523): MountEmulatedStorage()
,E/Zygote  ( 5523): v2
I/libpersona( 5523): KNOX_SDCARD checking this for 10055
I/libpersona( 5523): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5523 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
I/SELinux ( 5523): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/bluedroid( 5481): get_profile_interface handsfree
,I/SELinux ( 5523): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5523): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5481): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5481): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5481): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5481): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5481): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5481): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5481): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5481): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5481): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5481): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5481): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 5481): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/DualScoManager( 5481): Instantiating Dual Sco Manager
I/DualScoManager( 5481): Set HeadsetServiceHelper
D/BluetoothAtMessage( 5481): createCMTIContentObservers
,D/SettingsProvider( 1018): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 5481): Enter Disconnected: -2
,D/HeadsetService( 5481): mStartError = false
D/BluetoothAdapterService( 5481): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3383febb
,D/HeadsetStateMachine( 5481): Clear mHeadsetBrsf
D/HeadsetStateMachine( 5481): map size, before remove : 0
D/HeadsetStateMachine( 5481): map size, after remove: 0
,D/A2dpService( 5481): Received start request. Starting profile...
D/A2dpService( 5481): start()
D/TimaKeyStoreProvider( 5523): TimaSignature is unavailable
,I/BluetoothAvrcpServiceJni( 5481): classInitNative: succeeds
,I/bluedroid( 5481): get_profile_interface avrcp
D/ActivityThread( 5523): Added TimaKeyStore provider
,D/Tethering( 1018): interfaceAdded wlan0
,D/BluetoothA2dp( 1018): Proxy object connected
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
I/WifiHW  (  279): wifi_change_fw_path(): fwpath = sta
D/SoftapController(  279): Softap fwReload - Ok
,E/Tethering( 1018): No numeric data,
D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/Tethering( 1018): clearTetheredNotification()
,D/Tethering( 1018): InitialState.processMessage what=4
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceStatusChanged p2p0, false
,E/Tethering( 1018): No numeric data
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,D/Tethering( 1018): interfaceAdded p2p0
,D/Tethering( 1018): p2p0 is not a tetherable iface, ignoring
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,V/NetworkStats( 1018): performPollLocked() took 3ms
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,V/NetworkStats( 1018): performPollLocked() took 3ms
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,D/UserAnalysis.PlaceProvider( 5523): PlaceProvider onCreate()
,D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1174): updateTetherState():false, false
,D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1174): updateTetherState():false, false
,E/RemoteController( 5481): Cannot set synchronization mode on an unregistered RemoteController
,D/CommandListener(  279): Setting iface cfg
D/CommandListener(  279): Trying to bring down wlan0
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,I/Avrcp   ( 5481):  Updating now playing list upon AVRCP Start
,D/BluetoothMediaBrowser( 5481):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 5481): classInitNative: succeeds
D/A2dpStateMachine( 5481): make
,D/UserAnalysis.SecureDbManager( 5523): Key for secure DB is newly created
,E/WifiHW  ( 1018): supplicant_name : p2p_supplicant
,D/WifiMonitor( 1018): startMonitoring(wlan0) with mConnected = false,
,E/WifiHW  ( 1018): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory,
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
I/bluedroid( 5481): get_profile_interface a2dp
I/GKI_LINUX( 5481): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/UserAnalysis.SecurePlaceDbHelper( 5523): SecurePlaceDbHelper() 
D/UserAnalysis( 5523): Create SecureDbHelper
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,E/bt-btif ( 5481): warning : media task started media_task_refcnt 1 ,
,D/A2dpService( 5481): mStartError = false
D/BluetoothAdapterService( 5481): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3383febb
E/BluetoothAdapterService(864288443)( 5481): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
D/HotspotTile( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1174): Wifi onReceive(2)
D/A2dpStateMachine( 5481): Enter Disconnected: -2
,D/STATUSBAR-QSTileView( 1174): onStateChanged: Wi-Fi
D/HotspotTile( 1174): onReceive : 2, 0
,D/BluetoothMediaBrowser( 5481): no now playing list
,D/BluetoothMediaBrowser( 5481):  getNowPlayingId now playing id : -1
,I/BluetoothHidServiceJni( 5481): classInitNative: succeeds
,D/HidService( 5481): Received start request. Starting profile...
,D/HidService( 5481): start()
I/bluedroid( 5481): get_profile_interface hidhost
D/HidService( 5481): setHidService(): set to: null
D/HidService( 5481): mStartError = false
D/BluetoothAdapterService( 5481): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3383febb
,I/BluetoothHealthServiceJni( 5481): classInitNative: succeeds,
D/WifiCredService( 1290): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/HealthService( 5481): Received start request. Starting profile...
D/HealthService( 5481): start()
,I/bluedroid( 5481): get_profile_interface health
,D/HealthService( 5481): mStartError = false
,D/BluetoothAdapterService( 5481): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3383febb
,I/BluetoothPanServiceJni( 5481): classInitNative(L105): succeeds
,D/PanService( 5481): Received start request. Starting profile...,
D/PanService( 5481): start()
D/BluetoothPanServiceJni( 5481): initializeNative(L110): pan
I/bluedroid( 5481): get_profile_interface pan
,D/BluetoothPan( 1018): BluetoothPAN Proxy object connected
D/PanService( 5481): mStartError = false
D/BluetoothAdapterService( 5481): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3383febb
D/HeadsetStateMachine( 5481): Try to query the phonestate on bind
,D/IntelligenceServiceApplication( 5523): onCreate()
,I/Telecom ( 1430): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1430): BluetoothPhoneService: handleMessage(7) / param 0
I/Telecom ( 1430): BluetoothPhoneService: updateHeadsetWithCallState
,I/wpa_supplicant( 5543): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 5543): Successfully initialized wpa_supplicant
,I/SecureStorage( 5543): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/Telecom ( 1430): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1430): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/ActivityManager( 1018): Killing 4860:com.wssyncmldm/1000 (adj 15): empty #31
,I/Telecom ( 1430): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1430): Proxy not attached to service
,I/Telecom ( 1430): BluetoothPhoneService: Result of Message : true
D/HeadsetStateMachine( 5481): Proxy object connected
D/HeadsetPhoneState( 5481): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 5481): Disconnected process message: 11
,I/SecureStorage( 5543): [INFO]: SPID(0x00000000)This device supports Secure Storage
,D/IntelligenceServiceApplication( 5523): no applications having user consent for prediction
,D/BluetoothMapService( 5481): Received start request. Starting profile...
,D/BluetoothMapService( 5481): start()
,V/PlaceDetection v1.0.19 ( 5523): [PlaceDetection::stopService] Service stopped.
,D/BluetoothMapService( 5481): mStartError = false
D/BluetoothAdapterService( 5481): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3383febb
I/SecureStorage(  410): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5543
I/SecureStorage(  410): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 5543): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 5543): ssSupport state is = 1
I/wpa_supplicant( 5543): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5543): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  410): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5543
I/SecureStorage(  410): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
I/BluetoothSAPServiceJni( 5481): classInitNative(L204): succeeds
,D/SapService( 5481): Received start request. Starting profile...
,D/SapService( 5481): start()
D/BluetoothSAPServiceJni( 5481): initializeNative(L209): sap
I/bluedroid( 5481): get_profile_interface sap
D/SapService( 5481): mStartError = false
D/BluetoothAdapterService( 5481): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3383febb
,D/HeadsetPhoneState( 5481): sendDeviceDataStateChanged
,D/HeadsetPhoneState( 5481): Signal level : previous=0 curr=0
D/HeadsetStateMachine( 5481): Disconnected process message: 18
E/BluetoothAdapterService(864288443)( 5481): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService( 5481): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5481): Disconnected process message: 10
D/BluetoothA2dp( 5481): Proxy object connected
D/BluetoothAdapterService( 5481): Bluetooth A2dp source service connected
D/HeadsetPhoneState( 5481): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 5481): Disconnected process message: 11
E/BluetoothAdapterService(864288443)( 5481): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,V/PlaceDetection v1.0.19 ( 5523): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/BluetoothAdapterService(864288443)( 5481): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(864288443)( 5481): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(864288443)( 5481): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,D/AuthorizationBluetoothService( 1688): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5551 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,E/Zygote  ( 5551): MountEmulatedStorage()
E/Zygote  ( 5551): v2,
I/libpersona( 5551): KNOX_SDCARD checking this for 10141
I/libpersona( 5551): KNOX_SDCARD not a persona
,I/SELinux ( 5551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5551): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3305): Starting #2,
,I/Hs20UtilService( 3305): Message received 5011
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4860/cgroup.procs: No such file or directory
,E/Zygote  ( 5562): MountEmulatedStorage()
E/Zygote  ( 5562): v2
I/libpersona( 5562): KNOX_SDCARD checking this for 1000
I/libpersona( 5562): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5562 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 5562): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5562): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5562): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/art     (  322): Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 697us total 37.971ms,
,D/TimaKeyStoreProvider( 5551): TimaSignature is unavailable,
D/ActivityThread( 5551): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 5562): TimaSignature is unavailable
,D/ActivityThread( 5562): Added TimaKeyStore provider
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 28.092ms
,W/ResourcesManager( 5551): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5551): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5551): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5551): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 630us total 19.762ms,
,D/SecurityLogAgent( 5562): KnoxConfiguration : Current State = 1,
I/SecureStorage(  410): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 5543): [INFO]: SPID(0x00000001)Processing data has been completed
,D/SecurityLogAgent( 5562): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5562): StateMachine : Current State = 1
,D/SecurityLogAgent( 5562): StateMachine : Changed Current State = 1
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/ActivityManager( 1018): Killing 4881:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/wpa_supplicant( 5543): Ctrl_iface: loading cred from phone
,I/SecureStorage( 5543): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,I/SecureStorage( 5543): [INFO]: SPID(0x00000001)This device supports Secure Storage
,I/SecureStorage(  410): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5543
I/SecureStorage(  410): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5543): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5543): ssSupport state is = 1
,I/wpa_supplicant( 5543): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5543): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5543): SIM READ ERROR
I/wpa_supplicant( 5543): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5543): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5543): SIM READ ERROR
I/wpa_supplicant( 5543): Blacklist: Clear (all) 
,I/wpa_supplicant( 5543): wpa_default_ap_write_once
I/wpa_supplicant( 5543): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5543): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5543): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 5543): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5543): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/BluetoothAdapterService(864288443)( 5481): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,I/wpa_supplicant( 5543): rfkill: Cannot open RFKILL control device
E/BluetoothAdapterService(864288443)( 5481): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/ActivityManager( 1018): Killing 3940:com.sec.spp.push/u0a32 (adj 15): empty #31
,D/BluetoothAdapterState( 5481): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5481): enable
,I/bt_hci_bdroid( 5481): init
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
I/GKI_LINUX( 5481): gki_task_entry task_id=0 [BTU] starting
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/bt_vendor( 5481): bt-vendor : init
I/bt_vendor( 5481): bt-vendor : get_bt_soc_type
E/bt_vendor( 5481): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 5481): init: Local BD Address : 41:75:50:a9:ec:08
D/bt_userial_mct( 5481): userial_init
,I/bt_vendor( 5481): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 5481): Starting hciattach daemon
I/bt_vendor( 5481): try to set false
,I/bt_vendor( 5481): bt-vendor : BT_VND_OP_POWER_CTRL: On,
I/bt_vendor( 5481): Starting hciattach daemon
I/bt_vendor( 5481): try to set true
,I/qcom-bluetooth( 5595): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/wpa_supplicant( 5543): wlan0: Setting scan request: 0 sec 100000 usec
,I/qcom-bluetooth( 5601): /system/etc/init.qcom.bt.sh: Transport : smd ,
,I/qcom-bluetooth( 5602): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,I/qcom-bluetooth( 5604): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/qcom-bluetooth( 5605): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/qcom-bluetooth( 5606): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/qcom-bluetooth( 5607): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 43624(2MB) AllocSpace objects, 30(480KB) LOS objects, 33% free, 23MB/35MB, paused 2.774ms total 172.289ms,
,D/BadgeProvider( 5141): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_3940/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_4881/cgroup.procs: No such file or directory
,I/wpa_supplicant( 5543): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 5543): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,D/Launcher.Model( 1477): reloadBadges entered.
D/BadgeProvider( 5141): sendNotify entered. [uri] : content://com.sec.badge/apps/1,
D/BadgeProvider( 5141): sendNotify, [notify] : null
D/BadgeProvider( 5141): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5141): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5141): update, [UpdateCount] : 1
,I/SecureStorage( 5543): [INFO]: SPID(0x00000001)This device supports Secure Storage,
I/SecureStorage(  410): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5543
I/SecureStorage(  410): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,I/SecureStorage( 5543): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5543): ssSupport state is = 1
I/wpa_supplicant( 5543): Ctrl_iface: loading cred from phone
I/SecureStorage( 5543): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,I/SecureStorage( 5543): [INFO]: SPID(0x00000001)This device supports Secure Storage
,I/SecureStorage(  410): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5543
I/SecureStorage(  410): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5543): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5543): ssSupport state is = 1
I/wpa_supplicant( 5543): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5543): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5543): SIM READ ERROR
I/wpa_supplicant( 5543): wpa_default_ap_write_once
I/wpa_supplicant( 5543): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5543): rfkill: Cannot open RFKILL control device
,I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceStatusChanged p2p0, false
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/wpa_supplicant( 5543): p2p0: State: DISCONNECTED -> INACTIVE,
I/wpa_supplicant( 5543): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 5543): p2p0: State: INACTIVE -> DISCONNECTED,
I/wpa_supplicant( 5543): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5543): Skip scan - bUseNetwork false
,E/SMD     (  292): DCD OFF,
,I/qcom-bluetooth( 5615): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:75:41 ,
,I/qcom-bluetooth( 5616): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,D/Tethering( 1018): interfaceLinkStateChanged p2p0, false,
I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceStatusChanged p2p0, false
,I/bt_vendor( 5481): bluetooth satus is on,
D/bt_userial_mct( 5481): userial_open(port:0)
I/bt_vendor( 5481): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 5481): Done intiailizing UART
,I/bt_vendor( 5481): Done intiailizing UART
I/bt_userial_mct( 5481): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 5481): Bluetooth Firmware and transport layer are initialized
,D/bt_userial_mct( 5481): Entering userial_read_thread()
,I/        ( 5481): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 5481): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5481): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5481): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5481): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5481): BTE_InitTraceLevels -- TRC_A2D
,I/        ( 5481): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5481): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5481): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5481): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5481): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5481): BTE_InitTraceLevels -- TRC_SDP
,I/        ( 5481): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5481): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5481): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5481): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5481): BTE_InitTraceLevels -- TRC_PROTOCOL
,W/bt-l2cap( 5481): l2c_link_processs_ble_num_bufs 16
,E/bt-btm  ( 5481): BTM_SecRegister:p_cb_info->p_le_callback == 0xa4442ead 
,E/bt-btm  ( 5481): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4442ead 
,E/WifiStateMachine( 1018): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 5543): HOTSPOT20_ENABLE called
I/wpa_supplicant( 5543): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5543): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5543): SIM READ ERROR
,I/wpa_supplicant( 5543): Blacklist: Clear (all) 
,D/BluetoothAdapterProperties( 5481): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,E/bt-btif ( 5481): Calling BTA_HhEnable
,E/bt-btif ( 5481): btif_storage_get_adapter_property service_mask:0x2120048
,D/BluetoothAdapterProperties( 5481): Address is:08:EC:A9:50:75:41
E/BluetoothServiceJni( 5481): populateRssiValuesNative
I/bluedroid( 5481): getModelRssiValues
,E/BluetoothServiceJni( 5481): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5481): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 5481): Name is: A3-1
,I/wpa_supplicant( 5543): wlan0: Setting scan request: 0 sec 0 usec
,D/SettingsProvider( 1018): name = bluetooth_name
,D/BluetoothAdapterProperties( 5481): Scan Mode:20
,D/BluetoothAdapterProperties( 5481): Discoverable Timeout:120
D/BluetoothAdapterProperties( 5481): LE Address is:C8:D9:53:A0:EA:82
E/bt-btif ( 5481): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1,
E/bt-btif ( 5481): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 5481): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 5481): btif_sock_init: !vhci_init
D/IOP_DB_BT( 5481): db_open: file /etc/bluetooth/iop_bt.db
,E/bt_mct  ( 5481): hci lib postload completed
,I/wpa_supplicant( 5543): Skip scan - bUseNetwork false,
,D/IOP_DB_BT( 5481): db_open: db_open : handle 3028299792l, read 13894 bytes onto local cache
D/IOP_DB_BT( 5481): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5481): db_query: result 1
I/        ( 5481): iop_db_open: iop_db_open status 0
D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
D/bte_conf( 5481): Device ID record 1 : primary
D/bte_conf( 5481):   vendorId            = 0075
,D/bte_conf( 5481):   vendorIdSource      = 0001
D/bte_conf( 5481):   product             = 0100
D/bte_conf( 5481):   version             = 0200
D/bte_conf( 5481):   clientExecutableURL = 
D/bte_conf( 5481):   serviceDescription  = 
D/bte_conf( 5481):   documentationURL    = 
D/bte_conf( 5481): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 5481): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiConfigStore( 1018): Loading config and enabling all networks 
D/STATUSBAR-WifiQuickSettingButton( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1174): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 1174): onStateChanged: Wi-Fi
,D/HotspotTile( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1174): onReceive : 3, 0
,E/WifiConfigStore( 1018): Not a HS20
,D/WifiCredService( 1290): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/BluetoothAdapterState( 5481): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5481): ScanMode =  20
D/BluetoothAdapterProperties( 5481): State =  11
,D/SecContentProvider( 1018): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 5481): Setting state to 12,
I/BluetoothAdapterState( 5481): Bluetooth adapter state changed: 11-> 12
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/SettingsProvider( 1018): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3305): Starting #3
I/Hs20UtilService( 3305): Message received 5011
,D/SecurityLogAgent( 5562): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5562): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5562): StateMachine : Current State = 1
D/SecurityLogAgent( 5562): StateMachine : Changed Current State = 1
,D/BluetoothAdapterProperties( 5481): Scan Mode:21
D/BluetoothAdapterProperties( 5481): Discoverable Timeout:120
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 5481): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5481): updateAdapterState state is 12
,E/WifiConfigStore( 1018): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapter( 1430): onBluetoothStateChange: up=true
D/WifiNative-wlan0( 1018): callSECApiInt - ID [65]
D/BluetoothAdapterService( 5481): Autoconnection is available 
D/BluetoothAdapterService( 5481): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5481): starting service from this receiver
,D/BluetoothAdapter( 1430): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1174): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1174): onBluetoothStateChange: Bluetooth is on
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapter( 1438): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1438): onBluetoothStateChange: Bluetooth is on
I/BluetoothAdapterState( 5481): Entering On State from state = 11
,D/BluetoothAdapter( 1654): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1654): onBluetoothStateChange: Bluetooth is on
D/BluetoothA2dp( 1018): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 5481): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5481): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1449): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1449): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1018): onBluetoothStateChange: up=true
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/BluetoothAdapter( 1018): onBluetoothStateChange: Bluetooth is on
D/BluetoothA2dp( 5481): onBluetoothStateChange: up=true
,D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 5543): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5543): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 5543): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5543): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5543): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 5543): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5543): First Scan Start
,I/wpa_supplicant( 5543): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-wlan0( 1018): Setting external_sim to 1
,D/WifiStateMachine( 1018): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1018): startHal
E/wifi    ( 1018): getStaticLongField sWifiHalHandle 0x9d94788c
I/WifiNative-HAL( 1018): Could not start hal
,D/BluetoothAdapter( 5430): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5430): onBluetoothStateChange: Bluetooth is on
W/Settings( 5385): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1018): [BT Setting State] State =12
I/InputMethodManagerService( 1018): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/BluetoothPbapService( 5481): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): P2pDisabledState{ what=131203 }
,D/CommandListener(  279): Setting iface cfg
D/CommandListener(  279): Trying to bring up p2p0
,D/WifiMonitor( 1018): startMonitoring(p2p0) with mConnected = true
D/BluetoothTile( 1174):  onBluetoothStateChange:
,D/WifiP2pService( 1018): P2pEnablingState
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1174): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1174):  getBluetoothState : 12
,I/SamsungIME( 1788): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/WifiP2pService( 1018): P2pEnablingState{ what=147457 }
D/WifiP2pService( 1018): P2p socket connection successful
D/WifiP2pService( 1018): P2pEnabledState
,D/BluetoothHeadset( 1430): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@dc1da49, true
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/BluetoothHeadset( 1430): registerMessageListener
,E/WifiStateMachine( 1018): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiP2pService( 1018): sending p2p connection changed broadcast: IDLE
D/WifiScanningService( 1018): SCAN_AVAILABLE : 3
,D/WifiScanningService( 1018): DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1018): startHal
D/WifiP2pService( 1018): create mNetworkAgent
E/wifi    ( 1018): getStaticLongField sWifiHalHandle 0x9ed859bc
I/WifiNative-HAL( 1018): Could not start hal
E/WifiScanningService( 1018): could not start HAL
E/WifiStateMachine( 1018): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1018): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1018): invaild command id : 215
,D/HeadsetService( 5481): registerMessageListener
,D/HeadsetService( 5481): registerMessageListener
D/HeadsetStateMachine( 5481): Disconnected process message: 70
D/RttService( 1018): SCAN_AVAILABLE : 3
D/RttService( 1018): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/Telecom ( 1430): BluetoothPhoneService: handleMessage(7) / param null
D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/HeadsetStateMachine( 5481): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1595168
I/Telecom ( 1430): BluetoothPhoneService: updateHeadsetWithCallState
,E/WifiStateMachine( 1018): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 1018): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,E/WifiStateMachine( 1018): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=true
D/WifiNative-wlan0( 1018): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1018): invaild command id : 215
D/PhoneStatusBar( 1174): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,I/wpa_supplicant( 5543): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,I/wpa_supplicant( 5543): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,E/wpa_supplicant( 5543): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine( 1018): Failed to set frequency band 0
I/Telecom ( 1430): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1430): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1430): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayController( 1018): disconnect
D/WifiDisplayController( 1018): updateConnection
D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/BluetoothPbapService( 5481): Handler(): got msg=1
,D/HeadsetStateMachine( 5481): Disconnected process message: 9
,D/HeadsetStateMachine( 5481): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/SecContentProvider( 1018): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/AllShareCastTile( 1174): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1174): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/audio_hw_primary(  284): adev_set_parameters: enter: A2dpSuspended=false,
V/voice   (  284): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
E/HeadsetStateMachine( 5481): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,V/BluetoothPbapService( 5481): PBAP Service initSocket try: 0
,D/BluetoothMapMasInstance( 5481): set MAP SDP message type : 1
,W/BluetoothAdapter( 5481): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5481): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,D/BluetoothSocket( 5481): bindListen(), new LocalSocket 
D/BluetoothSocket( 5481): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5481): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29403cbd
W/BluetoothAdapter( 5481): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 5481): channel: 19
,D/BluetoothPbapService( 5481): PBAP Socket is BluetoothServerSocket
,D/BluetoothSocket( 5481): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 5481): bindListen(), new LocalSocket 
D/BluetoothSocket( 5481): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5481): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a09a2b2
,D/BluetoothSocket( 5481): channel: 5
,D/LocalBluetoothProfileManager( 1290): Adding local A2DP profile
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1290): Adding local HEADSET profile
,E/BluetoothHeadset( 1290): BTStateChangeCB is registed
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 1290): BluetoothHeadset service is binded
,D/BluetoothMap( 1290): Create BluetoothMap proxy object
,D/WifiNative-p2p0( 1018): p2pGetDeviceAddress
D/WifiNative-p2p0( 1018): p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,D/WifiDisplayController( 1018): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiP2pService( 1018): DeviceAddress: 0a:75:42
,D/WifiDisplayController( 1018): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A3-1
D/WifiDisplayController( 1018):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):  primary type: 10-0050F204-5
D/WifiDisplayController( 1018):  secondary type: null
D/WifiDisplayController( 1018):  wps: 0
D/WifiDisplayController( 1018):  grpcapab: 0
D/WifiDisplayController( 1018):  devcapab: 0
D/WifiDisplayController( 1018):  status: 3
D/WifiDisplayController( 1018):  wfdInfo: null
D/WifiDisplayController( 1018):  groupownerAddress: null
D/WifiDisplayController( 1018):  GOdeviceName: null
D/WifiDisplayController( 1018):  interfaceAddress: 
D/WifiDisplayController( 1018):  SConnectInfo : null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/Bluetoothsap( 1290): bindService called to Bluetooth SAP Service
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/WifiP2pService( 1018): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 1018): InactiveState
,D/WifiP2pService( 1018): InactiveState{ what=143376 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 5543): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService( 1018): updateNetworkInfo()
D/WifiP2pService( 1018): InactiveState{ what=143376 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143376 }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1290): PANU : true
,W/LocalBluetoothProfileManager( 1290): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1290): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1290): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1290): onReceive
,D/BluetoothA2dp( 1290): Proxy object connected
D/A2dpProfile( 1290): Bluetooth service connected
,V/BluetoothStatusReceiver( 1174): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1174): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/HeadsetProfile( 1290): Bluetooth service connected
,D/BluetoothMap( 1290): Proxy object connected
,D/MapProfile( 1290): Bluetooth service connected
D/BluetoothMap( 1290): getConnectedDevices()
,D/BluetoothAdapterService( 5481): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3383febb
,D/BtConfig.SecureMode( 5481): isSecureModeOn:false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/AuthorizationBluetoothService( 1688): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPbap( 1290): Proxy object connected
,D/PbapServerProfile( 1290): Bluetooth service connected
,D/Bluetoothsap( 1290): BluetoothSAP Proxy object connected
D/SapProfile( 1290): Bluetooth service connected
,D/Bluetoothsap( 1290): getConnectedDevices()
,D/BluetoothInputDevice( 1290): Proxy object connected
D/HidProfile( 1290): Bluetooth service connected
,D/BluetoothPan( 1290): BluetoothPAN Proxy object connected
,D/PanProfile( 1290): Bluetooth service connected
,D/SecContentProvider( 1018): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/NearbySettings( 1290): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1290): DMSUtil.isNetworkConnected - flag-null, state-null
,W/BluetoothAdapter( 5481): getBluetoothService() called with no BluetoothManagerCallback
I/NearbySettings( 1290): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1290): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1290): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1290): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1290): MountReceiver.mPrefHandler - 7002
D/BluetoothSocket( 5481): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
,D/BluetoothSocket( 5481): bindListen(), new LocalSocket 
D/BluetoothSocket( 5481): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5481): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22c0d9ac
D/BluetoothSocket( 5481): channel: 12
I/BtOppRfcommListener( 5481): Accept thread started.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5639): MountEmulatedStorage()
,I/libpersona( 5639): KNOX_SDCARD checking this for 10064
E/Zygote  ( 5639): v2
I/libpersona( 5639): KNOX_SDCARD not a persona
,I/SELinux ( 5639): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5639): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5639): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5639 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5639): TimaSignature is unavailable
,D/ActivityThread( 5639): Added TimaKeyStore provider
,W/ResourcesManager( 5639): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/FileShare-Client( 5639): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 5639): ClientBroadcastReceiver.onReceive - disconnected
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/FileShare-Client( 5639): Outbound.stopDelayTimer - 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5654): MountEmulatedStorage(),
E/Zygote  ( 5654): v2
I/libpersona( 5654): KNOX_SDCARD checking this for 10065
I/libpersona( 5654): KNOX_SDCARD not a persona
I/SELinux ( 5654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5654 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5654): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 4566:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31,
,D/TimaKeyStoreProvider( 5654): TimaSignature is unavailable
,D/ActivityThread( 5654): Added TimaKeyStore provider
,D/FileShare-Server( 5654): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1018): Killing 4989:com.samsung.helphub/1000 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_4566/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4989/cgroup.procs: No such file or directory
,I/wpa_supplicant( 5543): nl80211: Received scan results (7 BSSes),
I/wpa_supplicant( 5543): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5543): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5543): Trying to associate with  'G700'
I/wpa_supplicant( 5543): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 5543): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1018): didn't find BSSID Trying to associate with SSID 'NG700'
I/WifiNative-HAL( 1018): startHal
E/wifi    ( 1018): getStaticLongField sWifiHalHandle 0x9d9478ac
I/WifiNative-HAL( 1018): Could not start hal
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8e567c8
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1192925048)
,E/wpa_supplicant( 5543): Cmd 35605 not handled
,I/wpa_supplicant( 5543): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 5543): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 5543): Associated with C0.AA.48
I/wpa_supplicant( 5543): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5543): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5543): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
,I/wpa_supplicant( 5543): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 5543): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 5543): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 5543): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 5543): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5543): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5543): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 5543): Blacklist: Clear (temp) 
I/wpa_supplicant( 5543): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,E/Tethering( 1018): No numeric data
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1174): updateTetherState():false, false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,V/NetworkStats( 1018): performPollLocked() took 4ms
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/NtpTrustedTime( 1018): forceRefresh Fail.
D/WifiNative-wlan0( 1018): callSECApiVoid - ID [50]
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1192925048) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
,I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8e567c8
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} },
D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null,
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3305): Starting #4
,I/Hs20UtilService( 3305): Message received 5007
,D/NearbySettings( 1290): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1290): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1290): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/NearbySettings( 1290): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1290): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1290): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1290): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  279): Setting iface cfg
,E/WifiStateMachine( 1018): Start Dhcp Watchdog 1
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiNative-wlan0( 1018): do suspend false
,D/WifiP2pService( 1018): InactiveState{ what=143375 },
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 },
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/dhcpcd  ( 5675): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5675): version 5.5.6 starting,
,E/dhcpcd  ( 5675): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5675): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 5675): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5675): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 5675): bssid match
,I/dhcpcd  ( 5675): wlan0: rebinding lease of 192.168.1.132,
,I/dhcpcd  ( 5675): wlan0: acknowledged 192.168.1.132 from 192.168.1.1,
,I/dhcpcd  ( 5675): wlan0: leased 192.168.1.132 for 86400 seconds,
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 },
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1018): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1018): VerifyingLinkState enter
D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1018): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 1018): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService( 1018): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService( 1018): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,E/ConnectivityService( 1018): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1018): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 1018): LTETest block dns file not exists
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502],
,E/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,E/ConnectivityService( 1018): updateNetworkInfo()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3305): Starting #5
,I/Hs20UtilService( 3305): Message received 5007
,E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1018): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/ConnectivityService( 1018):    accepting network in place of null
,D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1018): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,D/TelephonyNetworkFactory( 1449): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/TelephonyNetworkFactory( 1449): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/System.out( 1018): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1018): (HTTPLog)-Static: isShipBuild true
I/System.out( 1018): (HTTPLog)-Thread-171-568584180: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 1018): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 1000
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NearbySettings( 1290): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,I/NearbySettings( 1290): MountReceiver.onReceive - Keep current state
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1018): mBoosterFLAG : 0
I/WifiTrafficPoller( 1018): current booster mode : FullMode
D/WifiNative-wlan0( 1018): callSECApiVoid - ID [212]
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1018): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
V/NetworkStats( 1018): updateIfacesLocked()
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 1000
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,V/NetworkStats( 1018): performPollLocked() took 4ms
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
,D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
,D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3305): Starting #6
,I/Hs20UtilService( 3305): Message received 5007
,D/NearbySettings( 1290): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1290): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1290): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1290): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1290): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1290): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3305): Starting #7
I/Hs20UtilService( 3305): Message received 5007
,D/NearbySettings( 1290): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1290): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1018): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/NtpTrustedTime( 1018): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1453034362027 mCachedNtpElapsedRealtime : 162502 mCachedNtpCertainty : 19
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1018): mCursor = null
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=4, Uoast
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 12:39:22 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453034361484], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453034361465]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,D/SRIB_DCS( 1174): log_dcs ThreadedRenderer::initialize entered! ,
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
,D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
,D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/AlarmManagerService( 1018): Setting time of day to sec=1453034362
D/AlarmManagerService( 1018): Trying to open a file
,D/AlarmManagerService( 1018): File Open Success
D/AlarmManagerService( 1018): File Close Success
I/AlarmManagerService( 1018): DRM_TIME_PATH CHMOD 666 for resetState done 
W/AlarmManagerService( 1018): Unable to set rtc to 1453034362: Invalid argument
,V/AlarmManager( 1018): waitForAlarm result :65536
,D/WifiStateMachine( 1018): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,V/AlarmManager( 1018): No more alarm at this time.nowELAPSED=162946 batch.start=164266
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,I/PCWCLIENTTRACE_PushUtil( 5021): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5021): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5021): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5021): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_SET
I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
D/SettingsProvider( 1018): name = lockscreen_zoom_panning_effect
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,E/Zygote  ( 5716): MountEmulatedStorage()
,E/Zygote  ( 5716): v2
I/libpersona( 5716): KNOX_SDCARD checking this for 10108
I/libpersona( 5716): KNOX_SDCARD not a persona
,I/SELinux ( 5716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5716 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5716): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5716): TimaSignature is unavailable
,D/ActivityThread( 5716): Added TimaKeyStore provider
,I/DowntimeConditions( 1018): android.intent.action.TIME_SET ignored because schedule turned off.
,W/Settings( 1018): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/KeyguardEffectViewUtil( 1174): isStrongPowerSavingMode() :false
,D/KeyguardEffectViewController( 1174): isPreloadedWallpaper=true
,I/GeometricMosaic_Keyguard( 1174): update
,D/KeyguardEffectViewUtil( 1174): getCurrentWallpaper() mWallpaperPath :null
,I/DrmEventService( 1018):  no response from SecureClock 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5731): MountEmulatedStorage(),
E/Zygote  ( 5731): v2
,I/libpersona( 5731): KNOX_SDCARD checking this for 10071
I/libpersona( 5731): KNOX_SDCARD not a persona,
,I/ActivityManager( 1018): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=5731 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 5731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5731): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5731): TimaSignature is unavailable
,D/ActivityThread( 5731): Added TimaKeyStore provider
,I/art     ( 1174): Background partial concurrent mark sweep GC freed 4324(244KB) AllocSpace objects, 6(148KB) LOS objects, 40% free, 18MB/30MB, paused 1.037ms total 103.730ms,
,E/SMD     (  292): DCD OFF,
,I/jxcore-log( 5430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5430): 
,I/KeyguardEffectViewUtil( 1174): set current wallpaper info
,D/SettingsProvider( 1018): name = keyguard_current_wallpaper_type
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,E/GpsLocationProvider( 1018): No APN found to select.
,D/SettingsProvider( 1018): name = keyguard_current_wallpaper_file_path
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,I/MusicStore( 5716): Database version: 120
,D/SettingsProvider( 1018): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5716): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5716): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5716): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/TEST    ( 1174): run!!!
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/GeometricMosaic_Renderer( 1174): setBackgroundBitmap
,W/ResourcesManager( 5716): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5716): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,V/JNIHelp ( 5716): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/KeyguardEffectViewController( 1174): isPreloadedWallpaper=true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 5731): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/DriveInitializer( 1920): Background init thread started
,W/ActivityThread( 5716): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5716): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38d973c2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5716): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5716): GMSCore installation verified
,I/BooksApp( 5731): Created application version: 3.6.9 (30609)
,I/ConfigStore( 5716): Config Database version: 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/DriveInitializer( 1920): Awaiting to be initialized
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1920): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Auth.Api.Credentials( 1920): [CredentialSyncAdapter] Unknown sync event.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 70
,I/MediaRouter( 5716): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,W/DriveInitializer( 1920): Background init thread ended
,V/MusicLeanback( 5716): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5716): type=WIFI subType= reason=null isConnected=true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/NetworkMonitor( 5716): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5784): MountEmulatedStorage()
,E/Zygote  ( 5784): v2
I/libpersona( 5784): KNOX_SDCARD checking this for 10001
I/libpersona( 5784): KNOX_SDCARD not a persona
,I/SELinux ( 5784): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5784): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5784): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5784 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 65491(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 3.740ms total 194.325ms
,D/TimaKeyStoreProvider( 5784): TimaSignature is unavailable
,D/ActivityThread( 5784): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 5731): Starting books sync for 61035162, extras: ade
,I/GHttpClientFactory( 5716): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 5430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5430): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 5716): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/jxcore-log( 5430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5430): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/jxcore-log( 5430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5430): 
,I/jxcore-log( 5430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5430): 
,I/jxcore-log( 5430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5430): 
,I/jxcore-log( 5430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5430): 
,I/art     ( 1688): Explicit concurrent mark sweep GC freed 5605(259KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 997us total 46.016ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5806): MountEmulatedStorage()
,E/Zygote  ( 5806): v2
I/libpersona( 5806): KNOX_SDCARD checking this for 1000
I/libpersona( 5806): KNOX_SDCARD not a persona
,I/SELinux ( 5806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=5806 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5004:com.google.android.apps.docs/u0a87 (adj 15): empty #31,
,I/SELinux ( 5806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5806): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5806): TimaSignature is unavailable
,D/ActivityThread( 5806): Added TimaKeyStore provider
,E/SQLiteLog( 5731): (284) automatic index on view_volumes(volume_id)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1018): waitForAlarm result :4
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 5806): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/BooksConfig( 5731): GmsCore Version = 7.8.99 (2134222-434)
,W/libprocessgroup( 1018): failed to open /acct/uid_10087/pid_5004/cgroup.procs: No such file or directory
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/login_manager
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/login_manager without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/Auth.Api.Credentials( 1920): [SyncManager] Error during the sync.
E/Auth.Api.Credentials( 1920): com.google.android.gms.auth.ad: BadAuthentication
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.common.server.s.b(SourceFile:59)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.common.server.s.a(SourceFile:294)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.common.server.s.a(SourceFile:201)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.auth.b.a.a(SourceFile:316)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.auth.api.credentials.be.a.b.b(SourceFile:285)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.auth.api.credentials.sync.c.a(SourceFile:384)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:114)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.auth.api.credentials.sync.a.a(SourceFile:131)
E/Auth.Api.Credentials( 1920): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
E/Auth.Api.Credentials( 1920): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/DIAGMON_AGENT( 5806): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5806): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5806): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 5806): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5806): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 5806): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/PicasaService( 4331): start picasa sync
,D/PicasaService( 4331): end picasa sync
,W/ResourcesManager( 1174): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1174): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/KnoxNotification( 1174): ----- inflateViews : modified publicViewLocal -----
,I/DBG_POLICYDM( 5090): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/KnoxNotification( 1174): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1174): PersonaID is invalid or persona doesn't exists. : 0
,I/DBG_POLICYDM( 5090): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/SQLiteLog( 1688): (10) POSIX Error : 11 SQLite Error : 3850
,I/DBG_POLICYDM( 5090): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5090): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Zygote  ( 5830): MountEmulatedStorage()
,E/Zygote  ( 5830): v2
,I/libpersona( 5830): KNOX_SDCARD checking this for 10008
I/libpersona( 5830): KNOX_SDCARD not a persona
,I/SELinux ( 5830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=5830 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5830): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5731): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,D/TimaKeyStoreProvider( 5830): TimaSignature is unavailable
,D/ActivityThread( 5830): Added TimaKeyStore provider
,E/BooksSync( 5731): Soft error
E/BooksSync( 5731): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5731): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5731): Sync error
E/BooksSync( 5731): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5731): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5731): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 22283, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ActivityManager( 1018): Killing 4959:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_4959/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 4635:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 5054:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #32
,I/FOTA_Client( 5830): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 5830): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/ActivityManager( 1018): Killing 5075:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3356): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 13:39:24 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3356): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): onCreate()
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3356): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.123: ( 3356): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 5848): MountEmulatedStorage()
,E/Zygote  ( 5848): v2
I/libpersona( 5848): KNOX_SDCARD checking this for 10031
I/libpersona( 5848): KNOX_SDCARD not a persona
,I/SELinux ( 5848): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5848): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5848 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 5848): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3356): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3356): StateImplV2(): networkChangeListener().START
,D/TimaKeyStoreProvider( 5848): TimaSignature is unavailable
,D/ActivityThread( 5848): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3356): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3356): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3356): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): onDestroy()
,W/libprocessgroup( 1018): failed to open /acct/uid_10029/pid_4635/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10148/pid_5054/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_5075/cgroup.procs: No such file or directory
,I/jxcore-log( 5430): Test app app.js loaded
I/jxcore-log( 5430): 
,I/Choreographer( 5430): Skipped 378 frames!  The application may be doing too much work on its main thread.
,I/DBG_POLICYDM( 5090): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/chromium( 5430): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SA      ( 5117): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5117): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 5117): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5090): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 5090): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5090): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 5090): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,I/DBG_POLICYDM( 5090): [com.policydm.XDMApplication(246/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/SA      ( 5117): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5090): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 5090): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 5117): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5117): [OR] == isSIMCardReady false ==
,I/SA      ( 5117): [SCU] == networkStateCheck == true
,I/SA      ( 5117): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5117): isChinaCountryCode : false
I/SA      ( 5117): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 5117): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5090): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5090): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5090): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/SA      ( 5117): [OR] GetMyCountryZoneTask
,I/SA      ( 5117): [OR] onReceive END
,I/ActivityManager( 1018): Killing 4168:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/accuweather( 1542): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5117): [SRS] prepareGetMyCountryZone
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,D/daemonapp( 1590): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 9
,I/SA      ( 5117): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5117): [SSP] query invoked
,D/accuweather( 1542): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1542): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1542): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1542): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5117): [TPMU] GetMccFromDB : null
,D/accuweather( 1542): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5117): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5117): [TPM] isNoProxy(default) : true
,D/accuweather( 1542): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5090): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,E/Zygote  ( 5875): MountEmulatedStorage(),
I/libpersona( 5875): KNOX_SDCARD checking this for 10121
E/Zygote  ( 5875): v2
I/libpersona( 5875): KNOX_SDCARD not a persona
I/SELinux ( 5875): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_POLICYDM( 5090): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/SELinux ( 5875): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/DBG_POLICYDM( 5090): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,E/SELinux ( 5875): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=5875 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/DBG_POLICYDM( 5090): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5090): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/01/18/13:05:31
,I/DBG_POLICYDM( 5090): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/01/17/13:39:24
,I/DBG_POLICYDM( 5090): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5090): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,E/File    ( 5117): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5090): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5090): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5090): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5090): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5090): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5090): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,D/TimaKeyStoreProvider( 5875): TimaSignature is unavailable
I/DBG_POLICYDM( 5090): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
D/ActivityThread( 5875): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5090): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,W/ResourcesManager( 5875): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5875): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5875): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/libprocessgroup( 1018): failed to open /acct/uid_10011/pid_4168/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,D/QuickConnect( 5875): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 5875): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/DBG_POLICYDM( 5090): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,I/QuickConnect( 5875): PeriphStartReceiver.onReceive - no need to start
,I/DBG_POLICYDM( 5090): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 5562): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5562): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5562): StateMachine : Current State = 1
,D/SecurityLogAgent( 5562): StateMachine : Changed Current State = 1
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/ActivityManager( 1018): Killing 4972:com.android.mms/u0a41 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,I/iu.SyncManager( 1920): SYNC; picasa accounts
,D/NetworkLogImpl( 1920): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1920): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 1920): num queued entries: 0
,I/iu.UploadsManager( 1920): num updated entries: 0
,I/iu.SyncManager( 1920): NEXT; no task
,D/CountryDetector( 1018): No listener is left
,D/ChimeraCfgMgr( 1920): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1920): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_4972/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5899): MountEmulatedStorage(),
E/Zygote  ( 5899): v2
I/libpersona( 5899): KNOX_SDCARD checking this for 10032,
I/libpersona( 5899): KNOX_SDCARD not a persona
,I/SELinux ( 5899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=5899 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/SELinux ( 5899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5899): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/System.out( 5385): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5385): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5385): (HTTPLog)-Static: isShipBuild true
I/System.out( 5385): (HTTPLog)-Thread-926-809962022: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5385): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10102
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5899): TimaSignature is unavailable
,D/ActivityThread( 5899): Added TimaKeyStore provider
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/System.out( 5385): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 5385): connection state changed from UNKNOWN to CONNECTED
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/SPPClientService( 5899): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5899): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5899): PushLog.txt file is not deleted.
,D/SPPClientService( 5899): PushLog.txt file is not deleted.
E/SPPClientService( 5899): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/SPPClientService( 5899): [SystemStateMoniter] Current Time : 165458
,D/SPPClientService( 5899): ============PushLog. stop!
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,E/SPPClientService( 5899): [SystemStateMoniter] No Connect : false
,D/PersonaManager( 1174): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5921): MountEmulatedStorage()
E/Zygote  ( 5921): v2
I/libpersona( 5921): KNOX_SDCARD checking this for 10110
I/libpersona( 5921): KNOX_SDCARD not a persona
,I/SELinux ( 5921): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5921): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5921): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5921 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Kids    ( 1920): [AccountUtils] Account not ready
W/Kids    ( 1920): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1920): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1920): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1920): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1920): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1920): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1920): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1920): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1920): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1920): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1920): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1920): 	at java.lang.Thread.run(Thread.java:818)
,I/art     (  322): Explicit concurrent mark sweep GC freed 8670(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 23.759ms
D/TimaKeyStoreProvider( 5921): TimaSignature is unavailable
D/ActivityThread( 5921): Added TimaKeyStore provider
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.709ms
,D/GCM     ( 1688): Connected
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 568us total 16.645ms
,D/GCM     ( 1688): Message class com.google.f.a.a.p
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5921): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5921): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 5921): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5921):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5921):   adb logcat -s GAv4
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5921): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5921): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 5921): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5921): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5921): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager( 1018): Killing 5141:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,I/SA      ( 5117): [RC New] Execute method=[GET] start
,I/SurfaceFlinger(  258): id=13 Removed Uoast (8/9),
I/SurfaceFlinger(  258): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 166057
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10049}) (elapsedTime=3480)
,I/SA      ( 5117): [RC New] Security=[true]
,I/System.out( 5117): Thread-865(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5117): Thread-865(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5117): Thread-865(ApacheHTTPLog):isShipBuild true
I/System.out( 5117): Thread-865(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5117): Thread-865(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10036
,I/dhcpcd  ( 5675): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 5675): wlan0: sendmsg: Cannot assign requested address
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10068/pid_5141/cgroup.procs: No such file or directory
,I/WebViewFactory( 5921): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 5921): Time to load native libraries: 1 ms (timestamps 6131-6132)
I/LibraryLoader( 5921): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5921): Binding Chromium to main looper Looper (main, tid 1) {1c02d4f1}
,I/LibraryLoader( 5921): Expected native library version number "",actual native library version number ""
,I/chromium( 5921): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5921): Initializing chromium process, singleProcess=true
,W/art     ( 5921): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5921): ApplicationContext is null in ApplicationStatus
,W/chromium( 5921): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5921): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5921): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5921): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5921): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5921): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5921): Local Branch: 
I/Adreno-EGL( 5921): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5921): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5921):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/SMD     (  292): DCD OFF
,W/AudioManagerAndroid( 5921): Requires BLUETOOTH permission
,I/NSApplication( 5921): Starting up...
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5976): MountEmulatedStorage()
E/Zygote  ( 5976): v2
I/libpersona( 5976): KNOX_SDCARD checking this for 10077
,I/libpersona( 5976): KNOX_SDCARD not a persona
,I/SELinux ( 5976): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5976 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5976): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Killing 5151:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
E/SELinux ( 5976): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5976): TimaSignature is unavailable
,D/ActivityThread( 5976): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_5151/cgroup.procs: No such file or directory
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
,D/btif_config_util( 5481): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,V/HeadsetService( 5481): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5481): Disconnected process message: 10
D/WaitQueueForNetworkActivate( 5323): notifyNetworkActivated
,W/ContextImpl( 5323): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/SA      ( 5117): [RC New] [v2liruge] api execute + 733
,I/SA      ( 5117): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5117): AsyncTask #1 calls detatch()
,I/SA      ( 5117): [ODM] saveOpenData( GEO_IP, PL )
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5323): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5323): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5323): exit::IDLE
D/InitializeManagerStateMachine( 5323): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5323): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5323): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5323): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5323): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5323): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5323): entry::SUCCESS
D/hcjo    ( 5323): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5323): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 5323): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5323): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5323): exit::SUCCESS
,D/InitializeManagerStateMachine( 5323): entry::IDLE
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 27578(1313KB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 23MB/35MB, paused 2.517ms total 147.880ms
,I/SA      ( 5117): [OCP] update openData : PL
,I/splitIntent( 1018): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 1018): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,I/SA      ( 5117): [TPMU] getNetworkMcc : 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/SA      ( 5117): [SCU] saveMccToPreferece Start
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/SA      ( 5117): [SCU] RegionMCC : 260
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SA      ( 5117): [SSP] query invoked
,I/SA      ( 5117): [TPMU] GetMccFromDB : null
I/SA      ( 5117): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5117): [SCU] saveMccToPreferece End
I/SA      ( 5117): [RC New] executeRequest [v2liruge] end. 952,
I/SA      ( 5117): [RC New] Execute end
I/SA      ( 5117): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5117): [OR] GetMyCountryZoneTask Success
,E/Zygote  ( 6000): MountEmulatedStorage()
E/Zygote  ( 6000): v2
I/libpersona( 6000): KNOX_SDCARD checking this for 10058
I/libpersona( 6000): KNOX_SDCARD not a persona
,I/SELinux ( 6000): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6000): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6000): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6000 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6015): MountEmulatedStorage()
E/Zygote  ( 6015): v2,
I/libpersona( 6015): KNOX_SDCARD checking this for 10131
I/libpersona( 6015): KNOX_SDCARD not a persona
,I/SELinux ( 6015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6015 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6015): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/FOTA_Client( 5830): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 5830): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
D/daemonapp( 1590): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1590): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1590): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 6000): TimaSignature is unavailable
,D/ActivityThread( 6000): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5179:com.wsomacp/u0a23 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3356): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Sun Jan 17 13:39:26 GMT+01:00 2016
,D/daemonapp( 1590): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/daemonapp( 1590): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/TimaKeyStoreProvider( 6015): TimaSignature is unavailable
,D/ActivityThread( 6015): Added TimaKeyStore provider
,D/daemonapp( 1590): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1590): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1590): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1590): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1590): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1590): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1590): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.5.123: ( 3356): KLMSAbstractReciever(): onReceive().END.
,I/SA      ( 5117): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/daemonapp( 1590): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3356): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/daemonapp( 1590): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1590): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1590): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/KLMS-2.5.123: ( 3356): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/daemonapp( 1590): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ResourcesManager( 6015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,E/daemonapp( 1590): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.123: ( 3356): StateImplV2(): dateTimeChanged().START : Sun Jan 17 13:39:26 GMT+01:00 2016
,D/comdaemonstockapp( 1590): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1590): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,W/libprocessgroup( 1018): failed to open /acct/uid_10023/pid_5179/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3356): StateImplV2(): dateTimeChanged().END
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): onDestroy()
,E/Zygote  ( 6032): MountEmulatedStorage()
,E/Zygote  ( 6032): v2
I/libpersona( 6032): KNOX_SDCARD checking this for 10041
I/libpersona( 6032): KNOX_SDCARD not a persona
,I/SELinux ( 6032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=6032 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux ( 6032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6032): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6032): TimaSignature is unavailable
,D/ActivityThread( 6032): Added TimaKeyStore provider
,D/daemonapp( 1590): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/ExternalOEMControlProvider( 6000): onCreate
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ResourcesManager( 6032): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6032): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6032): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6032): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/accuweather( 1542): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1542): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ Time Manager ( 6000): Time Difference not stored. TIME_DIFFERENCE
,I/ActivityManager( 1018): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6053 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6053): MountEmulatedStorage(),
E/Zygote  ( 6053): v2
I/libpersona( 6053): KNOX_SDCARD checking this for 10081
I/libpersona( 6053): KNOX_SDCARD not a persona
I/SELinux ( 6053): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6053): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6053): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/Zygote  ( 6067): MountEmulatedStorage()
E/Zygote  ( 6067): v2
I/libpersona( 6067): KNOX_SDCARD checking this for 10037
I/libpersona( 6067): KNOX_SDCARD not a persona
,I/SELinux ( 6067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6067): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6067 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/TimaKeyStoreProvider( 6053): TimaSignature is unavailable
,D/ActivityThread( 6053): Added TimaKeyStore provider
,D/Mms/MmsApp( 6032): [start]    onCreate() consume time = 0.0
,D/SecurityLogAgent( 5562): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5562): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5562): StateMachine : Current State = 1
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6067): TimaSignature is unavailable
V/AlarmManager( 1018): waitForAlarm result :4
D/ActivityThread( 6067): Added TimaKeyStore provider
,W/ResourcesManager( 6053): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6053): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6053): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6053): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6053): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6084 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,E/Zygote  ( 6084): MountEmulatedStorage()
E/Zygote  ( 6084): v2
I/libpersona( 6084): KNOX_SDCARD checking this for 10153
I/libpersona( 6084): KNOX_SDCARD not a persona
I/SELinux ( 6084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6084): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6084): TimaSignature is unavailable
,D/ActivityThread( 6084): Added TimaKeyStore provider
,W/ResourcesManager( 6067): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 6084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6100): MountEmulatedStorage()
,E/Zygote  ( 6100): v2
I/libpersona( 6100): KNOX_SDCARD checking this for 1000
I/libpersona( 6100): KNOX_SDCARD not a persona
,I/SELinux ( 6100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6100 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5199:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,I/SELinux ( 6100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6100): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/art     ( 6032): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 157.726ms
,D/TimaKeyStoreProvider( 6100): TimaSignature is unavailable
,D/ActivityThread( 6100): Added TimaKeyStore provider
,I/CalendarProvider2( 6067): CalendarProvider2.onCreate() called
,D/SettingsProvider( 1018): name = next_alarm_formatted
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10081
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/libprocessgroup( 1018): failed to open /acct/uid_10048/pid_5199/cgroup.procs: No such file or directory
,D/TimeService( 6100): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453034367015
D/        ( 6100): TimeServiceNative: User Time to be set is 1453034367015
D/QC-time-services( 6100): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6100): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6100): Lib:time_genoff_operation: pargs->ts_val = 1453034367015
,D/QC-time-services(  337): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 6100): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  337): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453034367015
D/QC-time-services(  337): Daemon:genoff_opr: Base = 2, val = 1453034367015, operation = 0
,D/QC-time-services(  337): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/14/70 6:24:37
D/QC-time-services(  337): Daemon:Value read from RTC seconds = 16784677000
D/QC-time-services(  337): Daemon:new time 1453034367015 
D/QC-time-services(  337): Daemon: delta 1436249690015 genoff 1436249690015 
D/QC-time-services(  337): Daemon:genoff_persistent_update: Writing genoff = 1436249690015 to memory
D/QC-time-services(  337): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  337): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/Mms/TelephonyPermission( 6032): start operation mode monitor
,D/Mms/ArtClassLoader( 6032): init before art
,W/ResourcesManager( 6032): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 6032): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 6032): isDefault true
,D/Mms/MmsApp( 6032): onCreate() com.android.mms
,D/QC-time-services(  337): Updating the TOD offset
D/QC-time-services(  337): Daemon:genoff_persistent_update: Writing genoff = 1436249690015 to memory
D/QC-time-services(  337): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  337): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  337): Daemon:Update to modem bit set
E/QC-time-services( 6100): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  337): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  337): Daemon: Base = 2, Value being sent to MODEM = 1120284890015
,I/ActivityManager( 1018): Killing 5225:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,E/QC-time-services(  337): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  337): Daemon: Time-services: Waiting to acceptconnection
,D/Mms/MmsApp( 6032): [start]    initCountryIso consume time = 321.037709
,D/CountryDetector( 1018): The first listener is added
,D/Mms/MmsApp( 6032): [end]    initCountryIso consume time = 10.464114
D/Mms/MmsConfig( 6032): [start]    MmsConfig.init() consume time = 0.120469
,D/Mms/MmsConfig( 6032): before partial update
,D/Mms/MmsConfig( 6032): Load Resize quality : 80
,W/art     ( 6053): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 166.842ms
,D/EasySignUpManager_1.0.1( 6032): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 6032): isAuth is false
D/Mms/MmsConfig( 6032): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1449): query,matched:2117, calling pid = 6032,
,D/TP/MmsSmsProvider( 1449): match 2117:Elapsed time : 1.137 ms
,D/EasySignUpManager_1.0.1( 6032): isAuth is false
D/EasySignUpManager_1.0.1( 6032): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 6032): mps_code.dat does not exist
E/CscParser( 6032): customer_path =/system/csc/customer.xml
E/CscParser( 6032): fileName + /system/csc/customer.xml
,E/CscParser( 6032): mps_code.dat does not exist
E/CscParser( 6032): customer_path =/system/csc/customer.xml
E/CscParser( 6032): fileName + /system/csc/customer.xml
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5225/cgroup.procs: No such file or directory
,D/CscParser( 6032): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 6032):  enable multiwindow = false
,E/Mms/MessageUtils( 6032): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 6032): updateCountryIso : update country iso info 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsConfig( 6032): [end]    init() consume time = 138.60401
D/Mms/Contact( 6032): [start]    init() consume time = 0.654532
,E/Zygote  ( 6125): MountEmulatedStorage()
,E/Zygote  ( 6125): v2
I/libpersona( 6125): KNOX_SDCARD checking this for 10090
I/libpersona( 6125): KNOX_SDCARD not a persona
,I/SELinux ( 6125): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6125 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
I/SELinux ( 6125): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1018): Killing 5242:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #31
,E/SELinux ( 6125): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/TP/MmsSmsProvider( 1449): query,matched:13, calling pid = 6032
,D/TP/MmsSmsProvider( 1449): match 13:Elapsed time : 1.080 ms
,D/Mms/Contact( 6032): [end]    init consume time = 40.762812
,D/TimaKeyStoreProvider( 6125): TimaSignature is unavailable
,D/ActivityThread( 6125): Added TimaKeyStore provider
,D/Mms/DraftCache( 6032): [start]    rebuildCache consume time = 12.502552
,D/Mms/MethodReflector( 6032): getSubId is called
D/Mms/TelephonyUtils( 6032): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 6032): getTelephonyProperty is called
D/Mms/DownloadManager( 6032): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6032): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6032): auto download without roaming -> true
D/Mms/DownloadManager( 6032): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 6032): getSubId is called
,D/Mms/ArtClassLoader( 6032): init [DONE] art
,D/TP/MmsSmsProvider( 1449): query,matched:12, calling pid = 6032
,D/Mms/MethodReflector( 6032): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 6032): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 6032): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 6032): getTelephonyProperty is called
D/Mms/DownloadManager( 6032): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 6032): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 6032): auto download without roaming -> true
D/Mms/DownloadManager( 6032): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 6032): auto download during roaming secondary -> false
D/Mms/DownloadManager( 6032): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 1449): match 12:Elapsed time : 2.803 ms
,D/ComposerPerformance( 6032): 1453034367310 ms / [DONE] Composer constructor
,E/CII     ( 6032): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 6032): ReservationManager()
,D/Mms/DraftCache( 6032): [end]    rebuildCache consume time = 21.979219
,I/Mms/ReservationManager( 6032): resetAfterConnected()
,D/Mms/Conversation( 6032): [start]    init() consume time = 4.924375
,D/TP/MmsSmsProvider( 1449): query,matched:7, calling pid = 6032
,D/elm:15121( 6125): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
D/TP/MmsSmsProvider( 1449): match 7:Elapsed time : 1.423 ms
,D/TP/MmsSmsProvider( 1449): deleteConversation threadId: 9223372036854775807,
D/elm:15121( 6125): ELMEngine.ELMEngine( context ).
D/TP/MmsSmsProvider( 1449): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1449): updateThread(), thread_id = 9223372036854775807
D/elm:15121( 6125): MDMBridge.setEnterpriseBridge()
V/TP/MmsSmsDatabaseHelper( 1449): sUpgradeVersion = 0, db.getVersion() = 81
W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/Mms/ReservationManager( 6032): getReservedSendMessageCount(): retMessageCount=0
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6125): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
D/TP/MmsSmsProvider( 1449): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1449): need read changed broadcast:false
,D/Mms/MmsApp( 6032): [end]    onCreate() consume time = 14.439583
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 6125): ElmAgentService : onCreate()
,D/elm:15121( 6125): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/Mms/DownloadManager( 6032): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 6032): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 6032): getSubId is called
D/Mms/TelephonyUtils( 6032): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 6032): getTelephonyProperty is called
D/Mms/DownloadManager( 6032): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6032): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6032): auto download without roaming -> true
D/Mms/DownloadManager( 6032): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 6032): mAutoDownload ------> true
,D/elm:15121( 6125): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15121( 6125): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:15121( 6125): ModuleBase.ModifySetAlarm(),
D/elm:15121( 6125): MDMBridge.getInstance()
D/elm:15121( 6125): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 6147): MountEmulatedStorage()
I/libpersona( 6147): KNOX_SDCARD checking this for 10130
E/Zygote  ( 6147): v2
I/libpersona( 6147): KNOX_SDCARD not a persona
I/SELinux ( 6147): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6147): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6147 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,E/SELinux ( 6147): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/Mms/Conversation( 6032): [end]    init consume time = 22.886563
D/Mms/MessagingNotification( 6032): [start]    init() consume time = 0.115625
,D/elm:15121( 6125): ElmAgentService : onDestroy().
,I/ActivityManager( 1018): Killing 5260:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,D/Mms/MessagingNotification( 6032): [end]    init consume time = 11.960521
,I/ActivityManager( 1018): Killing 5304:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
,D/Mms/Synchronizer( 6032): [start]    doSync consume time = 4.288802
,D/Mms/SpamFilter( 6032): [start]    SpamFilter fill() begin consume time = 7.294323
,D/TP/MmsSmsProvider( 1449): query,matched:0, calling pid = 6032
V/TP/MmsSmsProvider( 1449): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1449): match 0:Elapsed time : 1.008 ms
,D/TP/MmsSmsProvider( 1449): update, matched:300, calling pid = 6032
V/TP/MmsSmsProvider( 1449): syncDBData start
,V/TP/MmsSmsProvider( 1449): syncDBData sms end
V/TP/MmsSmsProvider( 1449): syncDBData mms end
V/TP/MmsSmsProvider( 1449): syncDBData end
,D/TimaKeyStoreProvider( 6147): TimaSignature is unavailable
,D/ActivityThread( 6147): Added TimaKeyStore provider
,D/Mms/Synchronizer( 6032): [end]    doSync consume time = 10.698489
D/TP/MmsSmsProvider( 1449): query,matched:400, calling pid = 6032
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6147): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6147): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/Zygote  ( 6164): MountEmulatedStorage()
,E/Zygote  ( 6164): v2
I/libpersona( 6164): KNOX_SDCARD checking this for 10068
I/libpersona( 6164): KNOX_SDCARD not a persona
I/SELinux ( 6164): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6164 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,D/Mms/SpamFilter( 6032): [end]    SpamFilter fill() finished consume time = 28.133281
I/SELinux ( 6164): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6164): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 4925:com.android.defcontainer/u0a3 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5242/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10052/pid_5304/cgroup.procs: No such file or directory
,I/splitIntent( 1018): Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/art     (  322): Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 25.162ms
I/ActivityManager( 1018): Killing 5523:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/TimaKeyStoreProvider( 6164): TimaSignature is unavailable
,D/ActivityThread( 6164): Added TimaKeyStore provider
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 19.033ms
,W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_5260/cgroup.procs: No such file or directory
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 700us total 16.976ms
,D/BadgeProvider( 6164): onCreate
D/BadgeProvider( 6164): DatabaseHelper
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5021): mConnectivityHandler : connected
,W/libprocessgroup( 1018): failed to open /acct/uid_10003/pid_4925/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10055/pid_5523/cgroup.procs: No such file or directory
,D/Mms/MessagingNotification( 6032): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1449): query,matched:26, calling pid = 6032
,D/TP/SmsProvider( 1449): match 26:Elapsed time : 1.444 ms
,D/TP/MmsSmsProvider( 1449): query,matched:6, calling pid = 6032
,W/PCWCLIENTTRACE_AccountUtil( 5021): [hasSamungAccount] - No Samsung Account
,D/TP/MmsSmsProvider( 1449): match 6:Elapsed time : 3.512 ms
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Watchdog( 1018): !@Sync 5
,E/Zygote  ( 6181): MountEmulatedStorage()
E/Zygote  ( 6181): v2
I/libpersona( 6181): KNOX_SDCARD checking this for 10023
I/libpersona( 6181): KNOX_SDCARD not a persona
,I/SELinux ( 6181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6181): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6181 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6181): TimaSignature is unavailable
,D/ActivityThread( 6181): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 5639:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5021): [GetString-S]
,I/ReactiveServiceManager( 5021): Supported : 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 9
,I/OMACP   ( 6181): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/libprocessgroup( 1018): failed to open /acct/uid_10064/pid_5639/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 9
E/terrier ( 1018): handleString: Failed to handle string(-4)
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5021): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5021): [GetString-E]
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PCWCLIENTTRACE_PushUtil( 5021): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5021): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5021): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5021): [ensureRegistration] - No Samsung account
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/Mms/Omacp( 6032): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/DBG_POLICYDM( 5090): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 6181): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1688): Vacuum at: now=1453034367721 tag=VacuumService
,I/DBG_POLICYDM( 5090): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5090): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/PerfProfileCollectorService( 1920): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 1920): removeStateFiles() called
,D/PerfProfileCollectorService( 1920): User is not opt-in to Usage & Diagnostics.
,E/DBG_POLICYDM( 5090): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,I/ActivityManager( 1018): Killing 5654:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/DBG_POLICYDM( 5090): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_POLICYDM( 5090): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10065/pid_5654/cgroup.procs: No such file or directory
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 16114(729KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.474ms total 134.806ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4703): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4703): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4703): [1] 5.onFinished: Scheduling replication attempt 5.
,I/GoogleURLConnFactory( 1688): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,W/Uploader( 1688): No account for auth token provided
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1688): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false,
I/System.out( 1688): (HTTPLog)-Static: isShipBuild true
I/System.out( 1688): (HTTPLog)-Thread-205-440911939: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
,I/ActivityManager( 1018): Killing 5021:com.sec.pcw.device/1000 (adj 15): empty #31
,I/System.out( 1688): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,I/qtaguid ( 1688): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5731): Thread[GAThread,5,main]: No campaign data found.
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5021/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/CalendarProvider2( 6067): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6210): MountEmulatedStorage(),
E/Zygote  ( 6210): v2
I/libpersona( 6210): KNOX_SDCARD checking this for 10011
I/libpersona( 6210): KNOX_SDCARD not a persona
I/SELinux ( 6210): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6210 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
I/SELinux ( 6210): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6210): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
D/TimaKeyStoreProvider( 6210): TimaSignature is unavailable
D/ActivityThread( 6210): Added TimaKeyStore provider
,I/MusicLeanback( 5716): Conditions not met for autocaching. okToAttempt=false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/Uploader( 1688):  no longer exists, so no auth token.
I/MusicLeanback( 5716): Stop autocaching.
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/ResourcesManager( 6210): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6210): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6210): VM with version 2.1.0 has multidex support
,I/MultiDex( 6210): install
I/MultiDex( 6210): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6210): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/ActivityThread( 6210): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6210): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15774675: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6210): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
,I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1688): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1688): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1920): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/WearableService( 6210): callingUid 10011, callindPid: 6210
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
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SMD     (  292): DCD OFF
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1920): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1654): [181] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 5716): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5716): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/ActivityManager( 1018): Killing 5784:com.sec.android.cloudagent/u0a1 (adj 15): empty #31
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
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/libprocessgroup( 1018): failed to open /acct/uid_10001/pid_5784/cgroup.procs: No such file or directory
,E/SQLiteLog( 1688): (10) POSIX Error : 11 SQLite Error : 3850
,I/Mms/MmsApp( 6032):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 6032): [start]    fillCache consume time = 1911.973958
D/Mms/ComposeMessageFragment( 6032): fillCache, easy = false
,D/AbsListView( 6032): Get MotionRecognitionManager
,D/MotionRecognitionService( 1018):  ssp status : false
,D/Mms/ComposeMessageFragment( 6032): [end]    fillCache consume time = 92.781198
,D/Mms/BubbleViewCache( 6032): fillCache bubble = 1
,I/dhcpcd  ( 5675): wlan0: sending IPv6 Router Solicitation
,D/SSRM:n  ( 1018): SIOP:: AP = 320
,E/SMD     (  292): DCD OFF,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,D/Finsky  ( 4703): [770] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4703): [770] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/dhcpcd  ( 5675): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 5675): wlan0: no IPv6 Routers available
,I/ActivityManager( 1018): Killing 5806:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5806/cgroup.procs: No such file or directory
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5481): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5481): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5323): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5323): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5323): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5323): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5323): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5323): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5323): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5323): entry::IDLE
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5481): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5481): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 140s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5481): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5481): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
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
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4703): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4703): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4703): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5481): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5481): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  292): DCD OFF
,I/BooksSync( 5731): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5731): GmsCore Version = 7.8.99 (2134222-434)
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
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
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
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5731): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5731): Soft error
E/BooksSync( 5731): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5731): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5731): Sync error
E/BooksSync( 5731): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5731): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5731): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 195264, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1688): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/Watchdog( 1018): !@Sync 7
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 8
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 5731): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5731): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5731): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5731): Soft error
E/BooksSync( 5731): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5731): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5731): Sync error
E/BooksSync( 5731): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5731): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 5731): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284760, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 40268(2MB) AllocSpace objects, 53(861KB) LOS objects, 33% free, 24MB/36MB, paused 2.495ms total 150.042ms
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 9
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :4
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 1018): initializing...
I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 10
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,E/SMD     (  292): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5481): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5481): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 10
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,I/jxcore-log( 5430): --= Surplus to requirements =--
I/jxcore-log( 5430): 
,I/jxcore-log( 5430): ****TEST TOOK:  ms ****
I/jxcore-log( 5430): 
I/jxcore-log( 5430): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5430): 
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,D/AndroidRuntime( 6320): 
D/AndroidRuntime( 6320): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6320): CheckJNI is OFF,
D/AndroidRuntime( 6320): readGMSProperty: start
D/AndroidRuntime( 6320): readGMSProperty: already setted!!
D/AndroidRuntime( 6320): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6320): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6320): readGMSProperty: end
D/AndroidRuntime( 6320): addProductProperty: start
,E/AffinityControl( 6320): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6320): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{590424644}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1018): !@killApplicatoin: 10338, uninstall pkg
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 5430:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1018): Skipping PackageSetting{3179bb4e com.example.hello/10346} due to missing metadata
,I/WindowState( 1018): WIN DEATH: Window{383c7780 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1018): Focus left window: 5430
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{16e5f49e u0 com.test.thalitest/.MainActivity t20},
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
W/ActivityManager( 1018): Spurious death for ProcessRecord{2b67e72d 5430:com.test.thalitest/u0a338}, curProc for 5430: null
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{16e5f49e u0 com.test.thalitest/.MainActivity t20 f}
W/ActivityManager( 1018): Duplicate finish request for ActivityRecord{16e5f49e u0 com.test.thalitest/.MainActivity t20 f}
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1018): Focused application released
,I/art     ( 3645): Explicit concurrent mark sweep GC freed 2947(177KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 872us total 26.926ms
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1788): mOCRHelper is null
,W/GeofencerStateMachine( 1654): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3356): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 13:42:06 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3356): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
,I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,D/elm:15121( 6125): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6125): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6125): ElmAgentService : onCreate()
,D/elm:15121( 6125): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6125): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6125): MDMBridge.getInstance()
D/elm:15121( 6125): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): onCreate()
,D/elm:15121( 6125): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3356): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3356): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/elm:15121( 6125): ElmAgentService : onDestroy().
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
I/KLMS-2.5.123: ( 3356): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/RegisteredServicesCache( 1438): empty dynamic service
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 16061(1456KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 3.436ms total 184.872ms
,I/art     ( 1018): WaitForGcToComplete blocked for 174.841ms for cause Explicit
,D/RCPManagerService( 1018): PackageReceiver onReceive()
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
I/KLMS-2.5.123: ( 3356): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3356): KLMSIntentService(): onDestroy()
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 10081(461KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.282ms total 155.953ms
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10338
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10338
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=20_task.xml
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6334): MountEmulatedStorage()
I/libpersona( 6334): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6334): v2
I/libpersona( 6334): KNOX_SDCARD not a persona
I/SELinux ( 6334): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PackageManager( 1018): delete codoeFile: 
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/SELinux ( 6334): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6334 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 6334): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AASA_removePackage( 1018): UID=10338 Target=com.test.thalitest
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/PackageManager( 1018): result of delete: 1{590424644}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
,D/AndroidRuntime( 6320): Shutting down VM
,D/TimaKeyStoreProvider( 6334): TimaSignature is unavailable
D/ActivityThread( 6334): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 6334): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 6334): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6334): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 6334): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6334): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6334): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6334): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6349 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 4331:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,E/Zygote  ( 6349): MountEmulatedStorage()
I/libpersona( 6349): KNOX_SDCARD checking this for 10029
E/Zygote  ( 6349): v2
I/libpersona( 6349): KNOX_SDCARD not a persona
I/SELinux ( 6349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
I/SELinux ( 6349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
E/SELinux ( 6349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5481): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5481): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/TimaKeyStoreProvider( 6349): TimaSignature is unavailable
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/ActivityThread( 6349): Added TimaKeyStore provider
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,I/FeatureConfig( 6349): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 5117): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5117): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1018): Killing 5848:com.sec.android.soagent/u0a31 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ResourcesManager( 6349): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,W/ResourcesManager( 6349): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/BroadcastQueue( 1018): Exception when sending broadcast to ComponentInfo{com.sec.android.gallery3d/com.sec.android.gallery3d.app.PackagesMonitor}
W/BroadcastQueue( 1018): android.os.TransactionTooLargeException
W/BroadcastQueue( 1018): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1018): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1018): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1018): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1018): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1018): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6349): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6349): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 6367): MountEmulatedStorage()
E/Zygote  ( 6367): v2
I/libpersona( 6367): KNOX_SDCARD checking this for 10039
I/libpersona( 6367): KNOX_SDCARD not a persona
,I/SELinux ( 6367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6367 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 6367): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 6349): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6349): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/art     ( 6320): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ResourcesManager( 6349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6349): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6367): TimaSignature is unavailable
,D/ActivityThread( 6367): Added TimaKeyStore provider
,W/ResourcesManager( 6349): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10039/pid_4331/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10031/pid_5848/cgroup.procs: No such file or directory
,W/ResourcesManager( 6349): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6367): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6367): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6367): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6367): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6367): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6367): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6367): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6349): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6349): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 6349): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
W/ResourcesManager( 6349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6349): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6349): system/finder_cp/cpdata.xml file not found
,E/SQLiteLog( 6367): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/SQLiteDatabase( 6367): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 6367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6367): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6367): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 6367): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 6367): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6367): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6367): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6367): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6367): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6367): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6367): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6367): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)

```
