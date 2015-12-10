#### Test 50650278c0f6ec2_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
E/SMD     (  288): DCD OFF
D/AndroidRuntime( 5404): 
D/AndroidRuntime( 5404): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5404): CheckJNI is OFF
D/AndroidRuntime( 5404): readGMSProperty: start
D/AndroidRuntime( 5404): readGMSProperty: already setted!!
D/AndroidRuntime( 5404): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5404): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5404): readGMSProperty: end
D/AndroidRuntime( 5404): addProductProperty: start
E/AffinityControl( 5404): AffinityControl: registerfunction enter
D/AndroidRuntime( 5404): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1015): mDVFSHelper.acquire()
D/FocusedStackFrame( 1015): Set to : 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
E/Zygote  ( 5416): MountEmulatedStorage()
E/Zygote  ( 5416): v2
I/libpersona( 5416): KNOX_SDCARD checking this for 10338
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/libpersona( 5416): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5416 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 1460
D/AndroidRuntime( 5404): Shutting down VM
I/SELinux ( 5416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5416): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, uhalitest
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5416): TimaSignature is unavailable
D/ActivityThread( 5416): Added TimaKeyStore provider
V/WindowManager( 1015): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1015): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1460): updateVisibility : ActivityRecord{21f6fbfd token=android.os.BinderProxy@15baae59 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1460): onTrimMemory. Level: 20
I/WebViewFactory( 5416): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5416): Time to load native libraries: 1 ms (timestamps 4783-4784)
I/LibraryLoader( 5416): Expected native library version number "",actual native library version number ""
W/art     ( 5404): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 5416): Binding Chromium to main looper Looper (main, tid 1) {19d28a3a}
,I/LibraryLoader( 5416): Expected native library version number "",actual native library version number ""
,I/chromium( 5416): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5416): Initializing chromium process, singleProcess=true,
W/art     ( 5416): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5416): ApplicationContext is null in ApplicationStatus
,W/chromium( 5416): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5416): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5416): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5416): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5416): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5416): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5416): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5416): Local Branch: 
I/Adreno-EGL( 5416): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5416): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5416):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5416): 79250676: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5416): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5416): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5416): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5416): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5416): CordovaWebView is running on device made by: samsung
,W/art     ( 5416): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5416): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1015): Activity pause timeout for ActivityRecord{2ee626f5 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 5416): Render dirty regions requested: true
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,W/chromium( 5416): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5416): updateVisibility : ActivityRecord{37b1d324 token=android.os.BinderProxy@50186b6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 5416): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5416): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit,
,D/InputDispatcher( 1015): Focus entered window: 5416
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5416): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5416): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5416): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5416): Enabling debug mode 0
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,I/ActivityManager( 1015): Displayed Component not be shown by security: +667ms (total +49s727ms)
W/ActivityManager( 1015): mDVFSHelper.release()
I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{2ee626f5 u0 com.test.thalitest/.MainActivity t20} time:155303
,W/IInputConnectionWrapper( 5416): showStatusIcon on inactive InputConnection,
I/Timeline( 5416): Timeline: Activity_idle id: android.os.BinderProxy@50186b6 time:155313
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (-2/9)
,I/SamsungIME( 1791): getCurrentCandidateView
,D/SamsungIME( 1791): Dismiss ExpandCandiate
,W/BindingManager( 5416): Cannot call determinedVisibility() - never saw a connection for the pid: 5416
,I/SamsungIME( 1791): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1791): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1791): KeybaordView init() : load resources
,I/SamsungIME( 1791): getCurrentKeyboard
,I/SamsungIME( 1791): getTextKeyboard
,D/SamsungIME( 1791): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5416): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5416): JniHelper::setJavaVM(0xb8ea4448), pthread_self() = -1187007616
,D/JX-Cordova( 5416): jxcore cordova android initializing
,I/PowerManagerService( 1015): [PWL] Off : 105s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,W/jxcore-log( 5416): Initializing JXcore engine
W/jxcore-log( 5416): JXcore engine is ready
,W/jxcore-log( 5416): Starting JXcore engine
,E/audit   ( 1789): type=1400 msg=audit(1449748676.343:203): avc:  denied  { ioctl } for  pid=5416 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1789):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1789): type=1300 msg=audit(1449748676.343:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=bed1ed58 items=0 ppid=304 ppcomm=main pid=5416 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1789): type=1320 msg=audit(1449748676.343:203): 
,W/jxcore-log( 5416): Platform android
W/jxcore-log( 5416): 
W/jxcore-log( 5416): Process ARCH arm
W/jxcore-log( 5416): 
E/SMD     (  288): DCD OFF
I/jxcore-log( 5416): JXcore Cordova bridge is ready!
I/jxcore-log( 5416): 
W/jxcore-log( 5416): JXcore engine is started
I/chromium( 5416): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 5416): Toggling radios to true
I/jxcore-log( 5416): 
D/BluetoothAdapter( 5416): enable()
W/ActivityManager( 1015): Permission Denial: getCurrentUser() from pid=5416, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1015): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1015): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5416, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1015): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/BluetoothManagerService( 1015): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
W/BluetoothManagerService( 1015): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
W/BluetoothManagerService( 1015): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/BluetoothManagerService( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
D/SettingsProvider( 1015): name = bluetooth_on
E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5467 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
E/Zygote  ( 5467): MountEmulatedStorage()
E/Zygote  ( 5467): v2
I/libpersona( 5467): KNOX_SDCARD checking this for 1002
I/libpersona( 5467): KNOX_SDCARD not a persona
D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1015): mCursor = null
I/SELinux ( 5467): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/WifiService( 1015): setWifiEnabled: true pid=5416, uid=10338
W/ActivityManager( 1015): Permission Denial: getCurrentUser() from pid=5416, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5467): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5467): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/WifiService( 1015): Failed getting userId using ActivityManagerNative
W/WifiService( 1015): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5416, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1015): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1015): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1015): name = wifi_on
I/WifiService( 1015): disconnect: pid=5416, uid=10338
E/WifiHW  ( 1015): ##################### set firmware type 0 #####################
I/jxcore-log( 5416): Radios toggled
I/jxcore-log( 5416): 
D/TimaKeyStoreProvider( 5467): TimaSignature is unavailable
D/ActivityThread( 5467): Added TimaKeyStore provider
W/ResourcesManager( 5467): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 5467): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/BluetoothA2dpSinkServiceJni( 5467): register_com_android_bluetooth_a2dp_sink
D/BtSettings.ProfileConfig( 5467): Adding GattService
D/BtSettings.ProfileConfig( 5467): Adding HeadsetService
D/BtSettings.ProfileConfig( 5467): Adding A2dpService
D/BtSettings.ProfileConfig( 5467): Adding HidService
D/BtSettings.ProfileConfig( 5467): Adding HealthService
D/BtSettings.ProfileConfig( 5467): Adding PanService
D/BtSettings.ProfileConfig( 5467): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 5467): Adding SapService
D/BtSettings.ProfileConfig( 5467): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 5467): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 5467): Adding SapClientService
D/BtSettings.ProfileConfig( 5467): Adding HidDevService
I/BtSettings.ProfileConfig( 5467): *********Initializing Bluetooth Profile Settings*******
D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider( 1015): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text,
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService,
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed,
D/SettingsProvider( 1015): ret = -1
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002,
D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 5467): make
,I/bluedroid( 5467): init
,I/BluetoothAdapterState( 5467): Entering OffState
,I/bte_conf( 5467): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5467): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5467): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5467): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 5467): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 5467): get_profile_interface socket
I/bluedroid( 5467): get_profile_interface map_client
,D/BluetoothAdapterService( 5467): checkAddrForIOP: Loading from conf
,I/GKI_LINUX( 5467): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5467): Address is:08:EC:A9:50:75:41
E/BluetoothServiceJni( 5467): populateRssiValuesNative
I/bluedroid( 5467): getModelRssiValues
E/BluetoothServiceJni( 5467): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5467): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 5467): Name is: A3-1
,D/SettingsProvider( 1015): name = bluetooth_name
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/bluedroid( 5467): config_hci_snoop_log
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothManagerService( 1015): Ble is always on enable gatt
,I/BluetoothManagerService( 1015): enableGattForLeMode, doBind called
,E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 1015): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState( 5467): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 5467): Setting state to 11
,I/BluetoothAdapterState( 5467): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5467): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5467): updateAdapterState state is 11
,D/BluetoothAdapterService( 5467): Autoconnection is available 
D/BluetoothAdapterService( 5467): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 5467): getInstant: null
,I/BtGatt.JNI( 5467): classInitNative(L900): classInitNative: Success!
,D/BluetoothSecureManager( 5467): calling getMethod for getService
W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1015): [BT Setting State] State =11
,D/BluetoothSecureManager( 5467): calling getService
,D/BluetoothSecureManager( 5467): getService return binder: android.os.BinderProxy@59fbc60
,D/BluetoothSecureManagerService( 1015): isSecureModeEnabled
,D/BluetoothSecureManagerService( 1015): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 5467): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5467): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5467): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5467): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5467): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5467): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5467): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5467): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,I/SamsungIME( 1791): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/BluetoothAdapterService( 5467): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5467): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5467): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5467): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5467): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 5467): make
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 11
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.gatt.GattService
,I/BluetoothBondStateMachine( 5467): StableState(): Entering Off State
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=false
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1177): onStateChanged: Bluetooth
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 5467): handleDebugAction() action=null
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.GattService( 5467): Received start request. Starting profile...
D/BtGatt.GattService( 5467): start()
D/BtGatt.GattService( 5467): start()
I/bluedroid( 5467): get_profile_interface gatt
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
D/BtGatt.AdvertiseManager( 5467): advertise manager created
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.a2dp.A2dpService
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5467): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.hid.HidService
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BtGatt.GattService( 5467): mStartError = false
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.hdp.HealthService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.pan.PanService
,D/HeadsetService( 5467): Received start request. Starting profile...
D/HeadsetService( 5467): start()
,I/BluetoothHeadsetServiceJni( 5467): classInitNative: succeeds
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,D/HeadsetStateMachine( 5467): make
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothNotiBroadcastReceiver( 1296): onReceive
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
E/HeadsetStateMachine( 5467): # of Max HF connection is 2
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5467): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/Tethering( 1015): interfaceAdded wlan0
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5467): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5467): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5467): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5467): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5467): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5467): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,V/BluetoothStatusReceiver( 1177): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1177): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,W/BluetoothAdapterService( 5467): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 5467): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,I/bluedroid( 5467): get_profile_interface handsfree
,E/Tethering( 1015): No numeric data
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
,I/WifiHW  (  278): wifi_change_fw_path(): fwpath = sta
,D/Tethering( 1015): interfaceStatusChanged wlan0, false
D/SoftapController(  278): Softap fwReload - Ok
,E/Zygote  ( 5511): MountEmulatedStorage()
,E/Zygote  ( 5511): v2
I/libpersona( 5511): KNOX_SDCARD checking this for 10055
,I/libpersona( 5511): KNOX_SDCARD not a persona
,I/SELinux ( 5511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5511 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 5511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1015): clearTetheredNotification()
D/Tethering( 1015): InitialState.processMessage what=4
E/SELinux ( 5511): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Tethering( 1015): No numeric data
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss,
,D/Tethering( 1015): interfaceAdded p2p0
,D/Tethering( 1015): p2p0 is not a tetherable iface, ignoring
D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1015): clearTetheredNotification()
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
I/DualScoManager( 5467): Instantiating Dual Sco Manager
I/DualScoManager( 5467): Set HeadsetServiceHelper
D/BluetoothAtMessage( 5467): createCMTIContentObservers
,D/Tethering( 1015): interfaceLinkStateChanged p2p0, false
D/Tethering( 1015): interfaceStatusChanged p2p0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged p2p0, false
D/SettingsProvider( 1015): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/TimaKeyStoreProvider( 5511): TimaSignature is unavailable
D/ActivityThread( 5511): Added TimaKeyStore provider
,D/HotspotTile( 1177): updateTetherState():false, false
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,D/CommandListener(  278): Setting iface cfg
D/CommandListener(  278): Trying to bring down wlan0
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/NtpTrustedTime( 1015): forceRefresh Fail.
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
D/HeadsetService( 5467): mStartError = false
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
D/HeadsetStateMachine( 5467): Enter Disconnected: -2
,D/BluetoothA2dp( 1015): Proxy object connected
D/HeadsetStateMachine( 5467): Clear mHeadsetBrsf
,D/A2dpService( 5467): Received start request. Starting profile...
D/A2dpService( 5467): start()
,D/HeadsetStateMachine( 5467): map size, before remove : 0
I/BluetoothAvrcpServiceJni( 5467): classInitNative: succeeds
,I/bluedroid( 5467): get_profile_interface avrcp
D/HeadsetStateMachine( 5467): map size, after remove: 0
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,V/NetworkStats( 1015): performPollLocked() took 13ms
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
D/NtpTrustedTime( 1015): forceRefresh Fail.
D/NtpTrustedTime( 1015): forceRefresh Fail.
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,V/NetworkStats( 1015): performPollLocked() took 3ms
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
,D/NtpTrustedTime( 1015): forceRefresh Fail.
,E/RemoteController( 5467): Cannot set synchronization mode on an unregistered RemoteController
,I/Avrcp   ( 5467):  Updating now playing list upon AVRCP Start
,D/BluetoothMediaBrowser( 5467):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 5467): classInitNative: succeeds
,D/A2dpStateMachine( 5467): make
,D/BluetoothMediaBrowser( 5467): no now playing list
,D/BluetoothMediaBrowser( 5467):  getNowPlayingId now playing id : -1
,D/UserAnalysis.PlaceProvider( 5511): PlaceProvider onCreate()
,I/bluedroid( 5467): get_profile_interface a2dp
,I/GKI_LINUX( 5467): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 5467): warning : media task started media_task_refcnt 1 
,D/A2dpService( 5467): mStartError = false
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,D/A2dpStateMachine( 5467): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 5467): classInitNative: succeeds
,E/WifiHW  ( 1015): supplicant_name : p2p_supplicant
,D/HidService( 5467): Received start request. Starting profile...,
D/HidService( 5467): start()
I/bluedroid( 5467): get_profile_interface hidhost
D/HidService( 5467): setHidService(): set to: null
D/HidService( 5467): mStartError = false
,D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
I/BluetoothHealthServiceJni( 5467): classInitNative: succeeds
,D/WifiMonitor( 1015): startMonitoring(wlan0) with mConnected = false
,D/HealthService( 5467): Received start request. Starting profile...
D/HealthService( 5467): start()
,I/bluedroid( 5467): get_profile_interface health
D/HealthService( 5467): mStartError = false
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,I/BluetoothPanServiceJni( 5467): classInitNative(L105): succeeds,
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(2)
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi,
,D/UserAnalysis.SecureDbManager( 5511): Key for secure DB is newly created
,D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/UserAnalysis.SecurePlaceDbHelper( 5511): SecurePlaceDbHelper() 
D/UserAnalysis( 5511): Create SecureDbHelper
,D/PanService( 5467): Received start request. Starting profile...
D/BluetoothPan( 1015): BluetoothPAN Proxy object connected
D/PanService( 5467): start()
D/BluetoothPanServiceJni( 5467): initializeNative(L110): pan
I/bluedroid( 5467): get_profile_interface pan
D/PanService( 5467): mStartError = false
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
D/WifiCredService( 1296): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1177): onReceive : 2, 0
,D/BluetoothMapService( 5467): Received start request. Starting profile...
,D/BluetoothMapService( 5467): start()
,D/BluetoothMapService( 5467): mStartError = false
,D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,I/BluetoothSAPServiceJni( 5467): classInitNative(L204): succeeds
,D/SapService( 5467): Received start request. Starting profile...
,D/SapService( 5467): start()
D/BluetoothSAPServiceJni( 5467): initializeNative(L209): sap
,I/bluedroid( 5467): get_profile_interface sap
D/SapService( 5467): mStartError = false
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,D/HeadsetStateMachine( 5467): Proxy object connected
,D/HeadsetPhoneState( 5467): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 5467): Try to query the phonestate on bind
D/HeadsetStateMachine( 5467): Disconnected process message: 11
,I/wpa_supplicant( 5533): [wpa_supplicant_init]: use SECRIL
,I/wpa_supplicant( 5533): Successfully initialized wpa_supplicant
,I/SecureStorage( 5533): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 5533): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/Telecom ( 1410): BluetoothPhoneService: queryPhoneState,
I/Telecom ( 1410): BluetoothPhoneService: handleMessage(7) / param 0
I/Telecom ( 1410): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1410): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1410): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/SecureStorage(  360): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5533
I/SecureStorage(  360): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 5533): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 5533): ssSupport state is = 1
I/wpa_supplicant( 5533): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5533): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  360): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5533
I/SecureStorage(  360): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
,I/Telecom ( 1410): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/IntelligenceServiceApplication( 5511): onCreate()
,W/BluetoothHeadset( 1410): Proxy not attached to service
,I/Telecom ( 1410): BluetoothPhoneService: Result of Message : true
D/HeadsetPhoneState( 5467): sendDeviceDataStateChanged
,D/HeadsetPhoneState( 5467): Signal level : previous=0 curr=0
D/HeadsetStateMachine( 5467): Disconnected process message: 18
,E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothA2dp( 5467): Proxy object connected
,D/BluetoothAdapterService( 5467): Bluetooth A2dp source service connected
V/HeadsetService( 5467): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5467): Disconnected process message: 10
D/HeadsetPhoneState( 5467): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5,
D/HeadsetStateMachine( 5467): Disconnected process message: 11
E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true,
E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,I/ActivityManager( 1015): Killing 4890:com.wssyncmldm/1000 (adj 15): empty #31
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5537): MountEmulatedStorage()
,E/Zygote  ( 5537): v2
I/libpersona( 5537): KNOX_SDCARD checking this for 10141
,I/libpersona( 5537): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5537 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/IntelligenceServiceApplication( 5511): no applications having user consent for prediction
,I/SELinux ( 5537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
V/PlaceDetection v1.0.19 ( 5511): [PlaceDetection::stopService] Service stopped.
,E/SELinux ( 5537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,V/PlaceDetection v1.0.19 ( 5511): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/TimaKeyStoreProvider( 5537): TimaSignature is unavailable
,D/ActivityThread( 5537): Added TimaKeyStore provider
,W/ResourcesManager( 5537): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 5537): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5537): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5537): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4890/cgroup.procs: No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/SecureStorage(  360): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
,E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true,
E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,I/SecureStorage( 5533): [INFO]: SPID(0x00000001)Processing data has been completed
,D/AuthorizationBluetoothService( 1688): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapterState( 5467): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5467): enable
,I/ActivityManager( 1015): Killing 4909:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/GKI_LINUX( 5467): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 5467): init
,I/bt_vendor( 5467): bt-vendor : init
I/bt_vendor( 5467): bt-vendor : get_bt_soc_type
E/bt_vendor( 5467): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 5467): init: Local BD Address : 41:75:50:a9:ec:08
D/bt_userial_mct( 5467): userial_init
,D/BadgeProvider( 5184): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/bt_vendor( 5467): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 5467): Starting hciattach daemon
I/bt_vendor( 5467): try to set false
,I/Hs20UtilService( 3355): Starting #2
I/bt_vendor( 5467): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 5467): Starting hciattach daemon
I/bt_vendor( 5467): try to set true
,I/Hs20UtilService( 3355): Message received 5011
,I/qcom-bluetooth( 5565): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 5533): Ctrl_iface: loading cred from phone
I/SecureStorage( 5533): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,E/Zygote  ( 5569): MountEmulatedStorage()
,E/Zygote  ( 5569): v2
I/libpersona( 5569): KNOX_SDCARD checking this for 1000
I/libpersona( 5569): KNOX_SDCARD not a persona,
,I/SELinux ( 5569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/SecureStorage( 5533): [INFO]: SPID(0x00000001)This device supports Secure Storage,
E/SELinux ( 5569): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SecureStorage(  360): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5533
I/SecureStorage(  360): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5533): [INFO]: SPID(0x00000001)SS Daemon is running,
I/wpa_supplicant( 5533): ssSupport state is = 1
I/wpa_supplicant( 5533): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 5533): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5533): SIM READ ERROR
I/wpa_supplicant( 5533): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5533): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5533): SIM READ ERROR
I/wpa_supplicant( 5533): Blacklist: Clear (all) 
,I/wpa_supplicant( 5533): wpa_default_ap_write_once
I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5569 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/wpa_supplicant( 5533): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5533): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 5533): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 5533): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5533): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
I/wpa_supplicant( 5533): rfkill: Cannot open RFKILL control device
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/art     (  304): Explicit concurrent mark sweep GC freed 8734(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 23.822ms
,D/BadgeProvider( 5184): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5184): sendNotify, [notify] : null
D/BadgeProvider( 5184): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5184): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5184): update, [UpdateCount] : 1
,D/Launcher.Model( 1460): reloadBadges entered.
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 26.154ms
,I/qcom-bluetooth( 5587): /system/etc/init.qcom.bt.sh: Transport : smd 
,D/TimaKeyStoreProvider( 5569): TimaSignature is unavailable,
D/ActivityThread( 5569): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 16.876ms
,I/qcom-bluetooth( 5588): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 5590): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5591): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/wpa_supplicant( 5533): wlan0: Setting scan request: 0 sec 100000 usec,
,I/qcom-bluetooth( 5592): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/qcom-bluetooth( 5593): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,D/SecurityLogAgent( 5569): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5569): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 5569): StateMachine : Current State = 1
,D/SecurityLogAgent( 5569): StateMachine : Changed Current State = 1
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1015): failed to open /acct/uid_10139/pid_4909/cgroup.procs: No such file or directory
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 35472(2MB) AllocSpace objects, 30(480KB) LOS objects, 33% free, 23MB/34MB, paused 2.604ms total 166.075ms,
,I/wpa_supplicant( 5533): wlan0: State: DISCONNECTED -> DISCONNECTED
I/SecureStorage( 5533): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage,
,I/SecureStorage( 5533): [INFO]: SPID(0x00000001)This device supports Secure Storage
,I/SecureStorage(  360): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5533
I/SecureStorage(  360): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5533): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5533): ssSupport state is = 1
,I/ActivityManager( 1015): Killing 3949:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/wpa_supplicant( 5533): Ctrl_iface: loading cred from phone
I/SecureStorage( 5533): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,I/SecureStorage( 5533): [INFO]: SPID(0x00000001)This device supports Secure Storage
I/SecureStorage(  360): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5533
I/SecureStorage(  360): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5533): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5533): ssSupport state is = 1
I/wpa_supplicant( 5533): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5533): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5533): SIM READ ERROR
I/wpa_supplicant( 5533): wpa_default_ap_write_once
I/wpa_supplicant( 5533): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5533): rfkill: Cannot open RFKILL control device
,D/Tethering( 1015): interfaceLinkStateChanged p2p0, false
D/Tethering( 1015): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1015): interfaceLinkStateChanged p2p0, false
D/Tethering( 1015): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged p2p0, false
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/wpa_supplicant( 5533): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 5533): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/qcom-bluetooth( 5600): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:75:41 ,
,W/libprocessgroup( 1015): failed to open /acct/uid_10032/pid_3949/cgroup.procs: No such file or directory
,I/qcom-bluetooth( 5601): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_vendor( 5467): bluetooth satus is on,
D/bt_userial_mct( 5467): userial_open(port:0)
I/bt_vendor( 5467): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 5467): Done intiailizing UART
,I/bt_vendor( 5467): Done intiailizing UART
I/bt_userial_mct( 5467): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 5467): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 5467): Entering userial_read_thread()
,I/wpa_supplicant( 5533): p2p0: State: INACTIVE -> DISCONNECTED,
I/wpa_supplicant( 5533): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5533): Skip scan - bUseNetwork false
,D/Tethering( 1015): interfaceLinkStateChanged p2p0, false
D/Tethering( 1015): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged p2p0, false
,E/WifiStateMachine( 1015): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,I/        ( 5467): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 5467): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5467): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5467): BTE_InitTraceLevels -- TRC_AVDT
,I/        ( 5467): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5467): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5467): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5467): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5467): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5467): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5467): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5467): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5467): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5467): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5467): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5467): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5467): BTE_InitTraceLevels -- TRC_PROTOCOL
,D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 5533): HOTSPOT20_ENABLE called
I/wpa_supplicant( 5533): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5533): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5533): SIM READ ERROR
I/wpa_supplicant( 5533): Blacklist: Clear (all) 
,I/wpa_supplicant( 5533): wlan0: Setting scan request: 0 sec 0 usec,
,I/wpa_supplicant( 5533): Skip scan - bUseNetwork false,
D/WifiNative-wlan0( 1015): callSECApiInt - ID [210]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(3)
D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
,D/HotspotTile( 1177): onReceive : 3, 0
,D/WifiConfigStore( 1015): Loading config and enabling all networks 
,D/WifiCredService( 1296): Action received :android.net.wifi.WIFI_STATE_CHANGED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3355): Starting #3
,I/Hs20UtilService( 3355): Message received 5011
,D/SecurityLogAgent( 5569): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5569): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5569): StateMachine : Current State = 1
D/SecurityLogAgent( 5569): StateMachine : Changed Current State = 1
,E/WifiConfigStore( 1015): Not a HS20
,E/WifiConfigStore( 1015): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-wlan0( 1015): callSECApiInt - ID [65]
,W/bt-l2cap( 5467): l2c_link_processs_ble_num_bufs 16
,D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 5533): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5533): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5533): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5533): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5533): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 5533): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5533): First Scan Start
,I/wpa_supplicant( 5533): Scan requested (ret=0) - scan timeout 30 seconds
,E/bt-btm  ( 5467): BTM_SecRegister:p_cb_info->p_le_callback == 0xa4451ead 
,E/bt-btm  ( 5467): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4451ead 
,D/WifiNative-wlan0( 1015): Setting external_sim to 1
,D/WifiStateMachine( 1015): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1015): startHal
E/wifi    ( 1015): getStaticLongField sWifiHalHandle 0x9d95988c
I/WifiNative-HAL( 1015): Could not start hal
,W/Settings( 3672): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiNative-wlan0( 1015): do suspend true
,D/WifiP2pService( 1015): P2pDisabledState{ what=131203 }
,E/WifiStateMachine( 1015): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,D/WifiScanningService( 1015): SCAN_AVAILABLE : 3
D/CommandListener(  278): Setting iface cfg
D/CommandListener(  278): Trying to bring up p2p0
,D/WifiScanningService( 1015): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1015): startMonitoring(p2p0) with mConnected = true
,I/WifiNative-HAL( 1015): startHal
E/wifi    ( 1015): getStaticLongField sWifiHalHandle 0x9e98d9bc
I/WifiNative-HAL( 1015): Could not start hal
,E/WifiStateMachine( 1015): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1015): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1015): invaild command id : 215
,D/RttService( 1015): SCAN_AVAILABLE : 3
D/RttService( 1015): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiScanningService( 1015): could not start HAL
E/WifiStateMachine( 1015): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1015): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1015): invaild command id : 215
,D/WifiP2pService( 1015): P2pEnablingState
,D/BluetoothAdapterProperties( 5467): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,D/WifiP2pService( 1015): P2pEnablingState{ what=147457 }
,D/WifiP2pService( 1015): P2p socket connection successful
,E/bt-btif ( 5467): BTA got event 0x518
,E/bt-btif ( 5467): btif_storage_get_adapter_property service_mask:0x2120048
,D/BluetoothAdapterProperties( 5467): Address is:08:EC:A9:50:75:41
E/BluetoothServiceJni( 5467): populateRssiValuesNative
I/bluedroid( 5467): getModelRssiValues
E/BluetoothServiceJni( 5467): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5467): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/WifiP2pService( 1015): P2pEnabledState
,I/wpa_supplicant( 5533): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,I/wpa_supplicant( 5533): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/wpa_supplicant( 5533): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService( 1015): sending p2p connection changed broadcast: IDLE
E/WifiStateMachine( 1015): Failed to set frequency band 0
D/BluetoothAdapterProperties( 5467): Name is: A3-1
,E/WifiStateMachine( 1015): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 1015): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/BluetoothAdapterProperties( 5467): Scan Mode:20
D/BluetoothAdapterProperties( 5467): Discoverable Timeout:120
D/WifiP2pService( 1015): create mNetworkAgent
,D/SettingsProvider( 1015): name = bluetooth_name
D/BluetoothAdapterProperties( 5467): LE Address is:C8:D9:53:A0:EA:82
,E/bt-btif ( 5467): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 5467): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif ( 5467): btif_sock_init: !radio_req && !rfc_init
E/bt_mct  ( 5467): hci lib postload completed
,E/bt-btif ( 5467): btif_sock_init: !vhci_init
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/IOP_DB_BT( 5467): db_open: file /etc/bluetooth/iop_bt.db
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/ConnectivityService( 1015): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1015): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1015): updateNetworkInfo()
D/WifiDisplayController( 1015): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1015): disconnect
D/WifiDisplayController( 1015): updateConnection
D/WifiDisplayController( 1015): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService( 1015): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/CSLegacyTypeTracker( 1015): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,D/IOP_DB_BT( 5467): db_open: db_open : handle 3028426768l, read 13894 bytes onto local cache
,D/IOP_DB_BT( 5467): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/WifiNative-p2p0( 1015): p2pGetDeviceAddress
,D/WifiNative-p2p0( 1015): p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
D/IOP_DB_BT( 5467): db_query: result 1
I/        ( 5467): iop_db_open: iop_db_open status 0
,D/bte_conf( 5467): Device ID record 1 : primary
D/bte_conf( 5467):   vendorId            = 0075
D/bte_conf( 5467):   vendorIdSource      = 0001
D/bte_conf( 5467):   product             = 0100
D/bte_conf( 5467):   version             = 0200
D/bte_conf( 5467):   clientExecutableURL = 
D/bte_conf( 5467):   serviceDescription  = 
D/bte_conf( 5467):   documentationURL    = 
D/bte_conf( 5467): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 5467): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDisplayController( 1015): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AllShareCastTile( 1177): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/BluetoothAdapterState( 5467): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5467): ScanMode =  20
D/BluetoothAdapterProperties( 5467): State =  11
,D/WifiP2pService( 1015): DeviceAddress: 0a:75:42
,D/SecContentProvider( 1015): uri = 3 selection = isDiscoverableEnabled
D/WifiDisplayController( 1015): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A3-1
D/WifiDisplayController( 1015):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiDisplayController( 1015):  primary type: 10-0050F204-5
D/WifiDisplayController( 1015):  secondary type: null
D/WifiDisplayController( 1015):  wps: 0
D/WifiDisplayController( 1015):  grpcapab: 0
D/WifiDisplayController( 1015):  devcapab: 0
D/WifiDisplayController( 1015):  status: 3
D/WifiDisplayController( 1015):  wfdInfo: null
D/WifiDisplayController( 1015):  groupownerAddress: null
D/WifiDisplayController( 1015):  GOdeviceName: null
D/WifiDisplayController( 1015):  interfaceAddress: 
D/WifiDisplayController( 1015):  SConnectInfo : null
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/BluetoothAdapterProperties( 5467): Setting state to 12
I/BluetoothAdapterState( 5467): Bluetooth adapter state changed: 11-> 12
,D/AllShareCastTile( 1177): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/BluetoothAdapterProperties( 5467): Scan Mode:21
D/BluetoothAdapterProperties( 5467): Discoverable Timeout:120
,D/SettingsProvider( 1015): name = bluetooth_a2dp_sink_mode
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
,V/NearbySettings( 1296): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - P2P: IDLE
D/WifiP2pService( 1015): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 1015): InactiveState
I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
D/WifiP2pService( 1015): InactiveState{ what=143376 }
,I/NearbySettings( 1296): MountReceiver.onReceive - Set preference state off
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,V/NearbySettings( 1296): MountReceiver.mPrefHandler - 7002
,D/BluetoothAdapterService( 5467): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5467): updateAdapterState state is 12
,D/WifiP2pService( 1015): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 5533): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/WifiP2pService( 1015): InactiveState{ what=143376 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143376 }
,I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5613 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5613): MountEmulatedStorage()
E/Zygote  ( 5613): v2
I/libpersona( 5613): KNOX_SDCARD checking this for 10064
I/libpersona( 5613): KNOX_SDCARD not a persona
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/SELinux ( 5613): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5613): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/BluetoothA2dp( 1015): onBluetoothStateChange: up=true
E/SELinux ( 5613): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothAdapterService( 5467): Autoconnection is available 
D/BluetoothAdapterService( 5467): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5467): starting service from this receiver
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapter( 1420): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1420): onBluetoothStateChange: Bluetooth is on
I/BluetoothAdapterState( 5467): Entering On State from state = 11
D/BluetoothAdapter( 5416): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5416): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1654): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1654): onBluetoothStateChange: Bluetooth is on
,D/BluetoothA2dp( 5467): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 5467): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5467): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1015): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1015): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1177): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1177): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1410): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1410): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1433): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1433): onBluetoothStateChange: Bluetooth is on
,W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1015): [BT Setting State] State =12
I/InputMethodManagerService( 1015): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/BluetoothPbapService( 5467): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothTile( 1177):  onBluetoothStateChange:
,D/BluetoothHeadset( 1410): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2593df3e, true
,D/BluetoothHeadset( 1410): registerMessageListener
,I/SamsungIME( 1791): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/HeadsetService( 5467): registerMessageListener
D/HeadsetService( 5467): registerMessageListener
,D/HeadsetStateMachine( 5467): Disconnected process message: 70
D/HeadsetStateMachine( 5467): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@28ae38bb
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1177):  getBluetoothState : 12
I/Telecom ( 1410): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1410): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1410): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1410): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1410): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,I/BluetoothPbapService( 5467): Handler(): got msg=1
,D/HeadsetStateMachine( 5467): Disconnected process message: 9
D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/HeadsetStateMachine( 5467): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/SecContentProvider( 1015): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/audio_hw_primary(  283): adev_set_parameters: enter: A2dpSuspended=false
,V/voice   (  283): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,E/HeadsetStateMachine( 5467): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/TimaKeyStoreProvider( 5613): TimaSignature is unavailable
,D/ActivityThread( 5613): Added TimaKeyStore provider
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,V/BluetoothPbapService( 5467): PBAP Service initSocket try: 0
,D/BluetoothMapMasInstance( 5467): set MAP SDP message type : 1
,W/BluetoothAdapter( 5467): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5467): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 5467): bindListen(), new LocalSocket 
D/BluetoothSocket( 5467): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5467): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e301fa2
,D/BluetoothSocket( 5467): channel: 19
D/BluetoothPbapService( 5467): PBAP Socket is BluetoothServerSocket
,W/ResourcesManager( 5613): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/BluetoothAdapter( 5467): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5467): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
,D/BluetoothSocket( 5467): bindListen(), new LocalSocket 
,D/BluetoothSocket( 5467): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5467): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d6d0433
D/BluetoothSocket( 5467): channel: 5
,D/FileShare-Client( 5613): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 5613): ClientBroadcastReceiver.onReceive - disconnected
,D/FileShare-Client( 5613): Outbound.stopDelayTimer - 
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5631): MountEmulatedStorage(),
,E/Zygote  ( 5631): v2
,I/libpersona( 5631): KNOX_SDCARD checking this for 10065
I/libpersona( 5631): KNOX_SDCARD not a persona
,I/SELinux ( 5631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5631 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1015): Killing 4598:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,E/SELinux ( 5631): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5631): TimaSignature is unavailable
,D/ActivityThread( 5631): Added TimaKeyStore provider
,D/FileShare-Server( 5631): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1015): Killing 5027:com.samsung.helphub/1000 (adj 15): empty #31
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/LocalBluetoothProfileManager( 1296): Adding local A2DP profile
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1296): Adding local HEADSET profile
,E/BluetoothHeadset( 1296): BTStateChangeCB is registed
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 1296): BluetoothHeadset service is binded
D/BluetoothMap( 1296): Create BluetoothMap proxy object
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/Bluetoothsap( 1296): bindService called to Bluetooth SAP Service
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1296): PANU : true
,W/LocalBluetoothProfileManager( 1296): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1296): LocalBluetoothProfileManager construction complete
,W/libprocessgroup( 1015): failed to open /acct/uid_10032/pid_4598/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5027/cgroup.procs: No such file or directory
,D/DockEventReceiver( 1296): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1296): onReceive
,D/BluetoothA2dp( 1296): Proxy object connected
D/A2dpProfile( 1296): Bluetooth service connected
,V/BluetoothStatusReceiver( 1177): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1177): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/HeadsetProfile( 1296): Bluetooth service connected
,D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,D/BtConfig.SecureMode( 5467): isSecureModeOn:false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothMap( 1296): Proxy object connected
D/MapProfile( 1296): Bluetooth service connected
,D/BluetoothMap( 1296): getConnectedDevices()
,D/BluetoothPbap( 1296): Proxy object connected
D/PbapServerProfile( 1296): Bluetooth service connected
D/Bluetoothsap( 1296): BluetoothSAP Proxy object connected
,D/SapProfile( 1296): Bluetooth service connected
D/Bluetoothsap( 1296): getConnectedDevices()
,D/BluetoothInputDevice( 1296): Proxy object connected
D/HidProfile( 1296): Bluetooth service connected
,D/AuthorizationBluetoothService( 1688): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPan( 1296): BluetoothPAN Proxy object connected
,D/PanProfile( 1296): Bluetooth service connected
,D/SecContentProvider( 1015): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/BluetoothAdapter( 5467): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5467): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
D/BluetoothSocket( 5467): bindListen(), new LocalSocket 
D/BluetoothSocket( 5467): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5467): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32698725
,D/BluetoothSocket( 5467): channel: 12
I/BtOppRfcommListener( 5467): Accept thread started.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/wpa_supplicant( 5533): nl80211: Received scan results (4 BSSes),
I/wpa_supplicant( 5533): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5533): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5533): Trying to associate with  'G700'
I/wpa_supplicant( 5533): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 5533): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1015): didn't find BSSID Trying to associate with SSID 'NG700'
,I/WifiNative-HAL( 1015): startHal
,E/wifi    ( 1015): getStaticLongField sWifiHalHandle 0x9d9598ac
I/WifiNative-HAL( 1015): Could not start hal
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8f027c8,
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1192221384)
,E/wpa_supplicant( 5533): Cmd 35605 not handled
,I/wpa_supplicant( 5533): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 5533): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 5533): Associated with C0.AA.48
I/wpa_supplicant( 5533): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5533): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5533): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,I/wpa_supplicant( 5533): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5533): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 5533): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 5533): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 5533): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5533): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5533): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 5533): Blacklist: Clear (temp) 
I/wpa_supplicant( 5533): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
E/Tethering( 1015): No numeric data
,D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1015): clearTetheredNotification()
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1015): forceRefresh Fail.
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,V/NetworkStats( 1015): performPollLocked() took 4ms
D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
,D/WifiNative-wlan0( 1015): callSECApiVoid - ID [50]
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
,D/NtpTrustedTime( 1015): forceRefresh Fail.
,E/WifiConfigStore( 1015): setLastSelectedConfiguration -1
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1192221384) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
,I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8f027c8
,D/ConnectivityService( 1015): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1015): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1015): updateNetworkInfo()
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3355): Starting #4
I/Hs20UtilService( 3355): Message received 5007
,D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1296): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1296): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1296): MountReceiver.mPrefHandler - 7002
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/AlarmManager( 1015): waitForAlarm result :8
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine( 1015): Start Dhcp Watchdog 1
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiNative-wlan0( 1015): do suspend false
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,E/dhcpcd  ( 5657): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 5657): version 5.5.6 starting
E/dhcpcd  ( 5657): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 5657): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 5657): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5657): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5657): bssid match
,I/dhcpcd  ( 5657): wlan0: rebinding lease of 192.168.1.132
,D/SSRM:n  ( 1015): SIOP:: AP = 310
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 5657): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,I/dhcpcd  ( 5657): wlan0: leased 192.168.1.132 for 86400 seconds
,E/WifiNative-wlan0( 1015): do suspend true
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1015): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1015): VerifyingLinkState enter
,D/WifiNative-wlan0( 1015): callSECApiInt - ID [210]
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1015): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 1015): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1015): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1015): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService( 1015): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService( 1015): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,E/ConnectivityService( 1015): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1015): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService( 1015): LTETest block dns file not exists
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,I/Hs20UtilService( 3355): Starting #5
,I/Hs20UtilService( 3355): Message received 5007
,E/ConnectivityService( 1015): updateNetworkInfo()
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1015): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
,E/WifiStateMachine( 1015): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 502],
E/WifiStateMachine( 1015): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Connected
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,D/ConnectivityService( 1015):    accepting network in place of null
,D/ConnectivityService( 1015): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/TelephonyNetworkFactory( 1433): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/TelephonyNetworkFactory( 1433): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1015): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1015): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/NearbySettings( 1296): MountReceiver.onReceive - Keep current state
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1015): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1015): (HTTPLog)-Static: isShipBuild true
I/System.out( 1015): (HTTPLog)-Thread-168-1051798979: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1015): mBoosterFLAG : 0
I/WifiTrafficPoller( 1015): current booster mode : FullMode
,D/WifiNative-wlan0( 1015): callSECApiVoid - ID [212]
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
,D/ConnectivityService( 1015): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1015): MasterInitialState.processMessage what=3
V/NetworkStats( 1015): updateIfacesLocked()
V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NetworkStats( 1015): performPollLocked() took 10ms
D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3355): Starting #6
,I/Hs20UtilService( 3355): Message received 5007
,D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1296): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1296): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3355): Starting #7
,I/Hs20UtilService( 3355): Message received 5007
,D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1296): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1015): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1015): mCursor = null
D/NtpTrustedTime( 1015): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449748681290 mCachedNtpElapsedRealtime : 161959 mCachedNtpCertainty : 12
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityYOffset
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/SecContentProvider2( 1015): mCursor = null
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,I/System.out( 1015): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1015): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1015): mCursor = null
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/SecContentProvider2( 1015): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1015): mCursor = null
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=4, Uoast
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 11:58:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449748681281], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449748681264]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
,D/PowerManagerService( 1015): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,D/ConnectivityService( 1015): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1015): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/SRIB_DCS( 1177): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
,D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5060): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5060): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5060): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5060): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1015): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1015): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/AlarmManagerService( 1015): Setting time of day to sec=1449748681
D/AlarmManagerService( 1015): Trying to open a file
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/AlarmManagerService( 1015): File Open Success
D/AlarmManagerService( 1015): File Close Success
I/AlarmManagerService( 1015): DRM_TIME_PATH CHMOD 666 for resetState done 
W/AlarmManagerService( 1015): Unable to set rtc to 1449748681: Invalid argument
V/AlarmManager( 1015): waitForAlarm result :65536
,E/Zygote  ( 5698): MountEmulatedStorage(),
I/ActivityManager( 1015): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5698 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5698): v2
I/libpersona( 5698): KNOX_SDCARD checking this for 10108
I/libpersona( 5698): KNOX_SDCARD not a persona
,I/SELinux ( 5698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5698): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/WifiStateMachine( 1015): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,I/DowntimeConditions( 1015): android.intent.action.TIME_SET ignored because schedule turned off.
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_SET
,W/Settings( 1015): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/TimaKeyStoreProvider( 5698): TimaSignature is unavailable
,D/ActivityThread( 5698): Added TimaKeyStore provider
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SettingsProvider( 1015): name = lockscreen_zoom_panning_effect
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10049
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
,V/AlarmManager( 1015): waitForAlarm result :4
V/AlarmManager( 1015): No more alarm at this time.nowELAPSED=162490 batch.start=163847
,I/DrmEventService( 1015):  no response from SecureClock 
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/KeyguardEffectViewUtil( 1177): isStrongPowerSavingMode() :false
,D/KeyguardEffectViewController( 1177): isPreloadedWallpaper=true
I/GeometricMosaic_Keyguard( 1177): update
,D/KeyguardEffectViewUtil( 1177): getCurrentWallpaper() mWallpaperPath :null
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5717): MountEmulatedStorage(),
E/Zygote  ( 5717): v2
,I/libpersona( 5717): KNOX_SDCARD checking this for 10071
I/libpersona( 5717): KNOX_SDCARD not a persona
,I/SELinux ( 5717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5717): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=5717 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5717): TimaSignature is unavailable
,D/ActivityThread( 5717): Added TimaKeyStore provider
,I/KeyguardEffectViewUtil( 1177): set current wallpaper info
,D/SettingsProvider( 1015): name = keyguard_current_wallpaper_type
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10049
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/SettingsProvider( 1015): name = keyguard_current_wallpaper_file_path
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10049
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/SettingsProvider( 1015): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10049
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/MusicStore( 5698): Database version: 120
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/GpsLocationProvider( 1015): No APN found to select.
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,D/TEST    ( 1177): run!!!
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GeometricMosaic_Renderer( 1177): setBackgroundBitmap
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5698): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/KeyguardEffectViewController( 1177): isPreloadedWallpaper=true
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5698): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5698): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/ResourcesManager( 5698): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5698): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5698): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/DriveInitializer( 1883): Background init thread started
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Auth.Api.Credentials( 1883): [CredentialSyncAdapter] Unknown sync event.
,W/ActivityThread( 5698): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5698): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ca7ac03: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5698): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5698): GMSCore installation verified
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigStore( 5698): Config Database version: 1
,W/DriveInitializer( 1883): Awaiting to be initialized
,W/GAV2    ( 5717): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1883): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,I/BooksApp( 5717): Created application version: 3.6.9 (30609)
,I/art     ( 1688): Explicit concurrent mark sweep GC freed 12513(691KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 973us total 48.354ms
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  288): DCD OFF
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/DriveInitializer( 1883): Background init thread ended
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1015): getStreamVolume 3 index 70
,I/MediaRouter( 5698): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5698): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5698): type=WIFI subType= reason=null isConnected=true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 64894(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 2.994ms total 185.318ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/NetworkMonitor( 5698): type=WIFI subType= reason=null isConnected=true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5771): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5771 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5771): v2
I/libpersona( 5771): KNOX_SDCARD checking this for 10001
I/libpersona( 5771): KNOX_SDCARD not a persona
,I/SELinux ( 5771): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5771): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5771): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5771): TimaSignature is unavailable
,D/ActivityThread( 5771): Added TimaKeyStore provider
,I/BooksSync( 5717): Starting books sync for 61035162, extras: ade
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 5698): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 5698): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4731): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4731): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4731): [1] 5.onFinished: Scheduling replication attempt 4.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/login_manager
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/login_manager without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Zygote  ( 5792): MountEmulatedStorage(),
E/Zygote  ( 5792): v2
I/libpersona( 5792): KNOX_SDCARD checking this for 1000
I/libpersona( 5792): KNOX_SDCARD not a persona
,I/SELinux ( 5792): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5792): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=5792 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5041:com.google.android.apps.docs/u0a87 (adj 15): empty #31
E/SELinux ( 5792): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5792): TimaSignature is unavailable
,D/ActivityThread( 5792): Added TimaKeyStore provider
,E/Auth.Api.Credentials( 1883): [SyncManager] Error during the sync.,
E/Auth.Api.Credentials( 1883): com.google.android.gms.auth.ad: BadAuthentication
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.common.server.s.b(SourceFile:59)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.common.server.s.a(SourceFile:294)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.common.server.s.a(SourceFile:201)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.auth.b.a.a(SourceFile:316)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.auth.api.credentials.be.a.b.b(SourceFile:285)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.auth.api.credentials.sync.c.a(SourceFile:384)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:114)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.auth.api.credentials.sync.a.a(SourceFile:131)
E/Auth.Api.Credentials( 1883): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
E/Auth.Api.Credentials( 1883): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/DIAGMON_AGENT( 5792): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
V/AlarmManager( 1015): waitForAlarm result :4
,E/SQLiteLog( 5717): (284) automatic index on view_volumes(volume_id)
,W/libprocessgroup( 1015): failed to open /acct/uid_10087/pid_5041/cgroup.procs: No such file or directory
,I/BooksConfig( 5717): GmsCore Version = 7.8.99 (2134222-434)
,D/PicasaService( 4365): start picasa sync
,D/PicasaService( 4365): end picasa sync
,I/DIAGMON_AGENT( 5792): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 5792): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
I/DIAGMON_AGENT( 5792): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 5792): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5792): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 5792): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 1688): (10) POSIX Error : 11 SQLite Error : 3850
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/WindowManager( 1015): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_POLICYDM( 5092): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,W/ResourcesManager( 1177): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1177): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5092): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5092): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5092): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/KnoxNotification( 1177): ----- inflateViews : modified publicViewLocal -----
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
,D/KnoxNotification( 1177): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1177): PersonaID is invalid or persona doesn't exists. : 0
,E/Zygote  ( 5816): MountEmulatedStorage(),
D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only,
,E/Zygote  ( 5816): v2
I/libpersona( 5816): KNOX_SDCARD checking this for 10008
I/StatusBar( 1177): Icon Only
I/libpersona( 5816): KNOX_SDCARD not a persona
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/SELinux ( 5816): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=5816 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
I/SELinux ( 5816): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5816): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5717): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5717): Soft error
E/BooksSync( 5717): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5717): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5717): Sync error
E/BooksSync( 5717): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5717): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 5717): Finished books sync
,D/TimaKeyStoreProvider( 5816): TimaSignature is unavailable
,D/ActivityThread( 5816): Added TimaKeyStore provider
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 21945, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager( 1015): Killing 4997:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,I/ActivityManager( 1015): Killing 5105:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 4656:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #32
,I/FOTA_Client( 5816): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 5816): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/ActivityManager( 1015): Killing 5128:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3376): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 12:58:03 GMT+01:00 2015
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3376): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3376): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3376): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3376): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 5834): MountEmulatedStorage(),
E/Zygote  ( 5834): v2
I/libpersona( 5834): KNOX_SDCARD checking this for 10031
I/SELinux ( 5834): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5834): KNOX_SDCARD not a persona
,I/SELinux ( 5834): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5834 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
E/SELinux ( 5834): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
I/KLMS-2.5.123: ( 3376): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3376): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3376): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,W/libprocessgroup( 1015): failed to open /acct/uid_10014/pid_4997/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3376): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3376): NetworkChangeOperations(): uploadRequestLog().START 
,D/TimaKeyStoreProvider( 5834): TimaSignature is unavailable
,D/ActivityThread( 5834): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3376): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3376): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3376): KLMSIntentService(): onDestroy()
,W/libprocessgroup( 1015): failed to open /acct/uid_10152/pid_5128/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10029/pid_4656/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10148/pid_5105/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5092): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5156): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5156): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 5156): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5156): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5092): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5092): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5092): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 5092): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,I/DBG_POLICYDM( 5092): [com.policydm.XDMApplication(246/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_POLICYDM( 5092): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 5092): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 5156): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5156): [OR] == isSIMCardReady false ==
,I/SA      ( 5156): [SCU] == networkStateCheck == true
,I/SA      ( 5156): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5156): isChinaCountryCode : false
I/SA      ( 5156): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5156): [OR] == networkStateCheck true ==
,I/SA      ( 5156): [OR] GetMyCountryZoneTask
,I/SA      ( 5156): [OR] onReceive END
,I/ActivityManager( 1015): Killing 4183:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,V/DownloadManager( 1225): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5092): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5092): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5092): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,D/accuweather( 1527): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5156): [SRS] prepareGetMyCountryZone
,D/SecContentProvider2( 1015): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1015): mCursor = null
,I/SA      ( 5156): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5156): [SSP] query invoked
,D/daemonapp( 1593): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 18
,I/SA      ( 5156): [TPMU] GetMccFromDB : null
I/SA      ( 5156): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5156): [TPM] isNoProxy(default) : true
D/accuweather( 1527): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1527): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1527): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1527): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1527): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1527): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/File    ( 5156): fail readDirectory() errno=2
,E/Zygote  ( 5861): MountEmulatedStorage()
,E/Zygote  ( 5861): v2
I/libpersona( 5861): KNOX_SDCARD checking this for 10121
I/libpersona( 5861): KNOX_SDCARD not a persona
,I/SELinux ( 5861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5861): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=5861 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,D/TimaKeyStoreProvider( 5861): TimaSignature is unavailable
D/ActivityThread( 5861): Added TimaKeyStore provider
,W/ResourcesManager( 5861): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5861): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5861): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,W/libprocessgroup( 1015): failed to open /acct/uid_10011/pid_4183/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5092): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 5092): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5092): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5092): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/12/10/14:45:39
,I/DBG_POLICYDM( 5092): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/12/10/12:58:03
,I/DBG_POLICYDM( 5092): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5092): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 5092): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/QuickConnect( 5861): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 5861): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/DBG_POLICYDM( 5092): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,I/QuickConnect( 5861): PeriphStartReceiver.onReceive - no need to start
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5092): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5092): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5092): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5092): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5092): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5092): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 5569): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5569): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5569): StateMachine : Current State = 1
,D/SecurityLogAgent( 5569): StateMachine : Changed Current State = 1
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,I/ActivityManager( 1015): Killing 5011:com.android.mms/u0a41 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
I/DBG_POLICYDM( 5092): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5092): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10011
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,I/iu.SyncManager( 1883): SYNC; picasa accounts
,D/CountryDetector( 1015): No listener is left
,D/NetworkLogImpl( 1883): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1883): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/libprocessgroup( 1015): failed to open /acct/uid_10041/pid_5011/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 1883): num queued entries: 0
,I/iu.UploadsManager( 1883): num updated entries: 0
,I/iu.SyncManager( 1883): NEXT; no task
,D/ChimeraCfgMgr( 1883): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,D/ChimeraCfgMgr( 1883): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,E/Zygote  ( 5885): MountEmulatedStorage(),
E/Zygote  ( 5885): v2
I/libpersona( 5885): KNOX_SDCARD checking this for 10032
I/libpersona( 5885): KNOX_SDCARD not a persona
,I/SELinux ( 5885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5885): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=5885 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,I/System.out( 3672): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 3672): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3672): (HTTPLog)-Static: isShipBuild true
I/System.out( 3672): (HTTPLog)-Thread-581-669761960: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3672): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10102
,D/TimaKeyStoreProvider( 5885): TimaSignature is unavailable
,D/ActivityThread( 5885): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 3672): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 3672): connection state changed from DISCONNECTED to CONNECTED
,E/SPPClientService( 5885): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5885): [PushClientApplication] Push log off : This is Ship build version
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/SPPClientService( 5885): PushLog.txt file is not deleted.
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/SPPClientService( 5885): PushLog.txt file is not deleted.
D/SPPClientService( 5885): ============PushLog. stop!
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,E/SPPClientService( 5885): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5885): [SystemStateMoniter] Current Time : 165042
,W/Kids    ( 1883): [AccountUtils] Account not ready
W/Kids    ( 1883): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1883): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1883): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1883): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1883): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1883): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1883): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1883): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1883): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1883): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1883): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1883): 	at java.lang.Thread.run(Thread.java:818)
,D/GCM     ( 1688): Connected
,E/SPPClientService( 5885): [SystemStateMoniter] No Connect : false
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/GCM     ( 1688): Message class com.google.f.a.a.p
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5906): MountEmulatedStorage()
E/Zygote  ( 5906): v2
I/libpersona( 5906): KNOX_SDCARD checking this for 10110,
I/libpersona( 5906): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5906 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 5906): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5906): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5906): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/art     (  304): Explicit concurrent mark sweep GC freed 8685(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 21.297ms
,D/TimaKeyStoreProvider( 5906): TimaSignature is unavailable
,D/ActivityThread( 5906): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 16.811ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 16.858ms
,I/dhcpcd  ( 5657): wlan0: sending IPv6 Router Solicitation
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5906): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5906): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/SurfaceFlinger(  257): id=13 Removed Uoast (8/9),
I/SurfaceFlinger(  257): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 1015): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 165491
,D/PowerManagerService( 1015): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,D/PowerManagerService( 1015): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10049}) (elapsedTime=3487)
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5906): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5906): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 5906): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5906):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5906):   adb logcat -s GAv4
,W/GAv4    ( 5906): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager( 1015): Killing 5184:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,W/GAv4    ( 5906): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5906): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/SA      ( 5156): [RC New] Execute method=[GET] start
,D/btif_config_util( 5467): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/libprocessgroup( 1015): failed to open /acct/uid_10068/pid_5184/cgroup.procs: No such file or directory
,I/SA      ( 5156): [RC New] Security=[true],
,I/System.out( 5156): Thread-875(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
,I/System.out( 5156): Thread-875(ApacheHTTPLog):isSBSettingEnabled false,
,I/System.out( 5156): Thread-875(ApacheHTTPLog):isShipBuild true
I/System.out( 5156): Thread-875(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5156): Thread-875(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10036
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 5906): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 5906): Time to load native libraries: 1 ms (timestamps 5866-5867)
,I/LibraryLoader( 5906): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5906): Binding Chromium to main looper Looper (main, tid 1) {341732c6}
,I/LibraryLoader( 5906): Expected native library version number "",actual native library version number ""
,I/chromium( 5906): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5906): Initializing chromium process, singleProcess=true
,W/art     ( 5906): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 5906): ApplicationContext is null in ApplicationStatus
,W/chromium( 5906): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5906): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5906): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5906): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5906): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5906): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5906): Local Branch: 
I/Adreno-EGL( 5906): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5906): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5906):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/NSApplication( 5906): Starting up...
,W/AudioManagerAndroid( 5906): Requires BLUETOOTH permission
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5962): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5962 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5962): v2
I/libpersona( 5962): KNOX_SDCARD checking this for 10077
I/SELinux ( 5962): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5962): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Killing 5200:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,I/SELinux ( 5962): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5962): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5962): TimaSignature is unavailable
,D/ActivityThread( 5962): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_5200/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF
,D/WaitQueueForNetworkActivate( 5337): notifyNetworkActivated
,I/SA      ( 5156): [RC New] [v2liruge] api execute + 686
,I/SA      ( 5156): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5156): AsyncTask #1 calls detatch()
,I/SA      ( 5156): [ODM] saveOpenData( GEO_IP, PL )
,W/ContextImpl( 5337): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 28167(1324KB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 23MB/35MB, paused 2.623ms total 141.748ms
,W/ActivityManager( 1015): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/SA      ( 5156): [OCP] update openData : PL
,I/SA      ( 5156): [TPMU] getNetworkMcc : 
,I/SA      ( 5156): [SCU] saveMccToPreferece Start
,I/SA      ( 5156): [SCU] RegionMCC : 260
I/SA      ( 5156): [SSP] query invoked
,I/SA      ( 5156): [TPMU] GetMccFromDB : null
,I/SA      ( 5156): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5156): [SCU] saveMccToPreferece End
,I/SA      ( 5156): [RC New] executeRequest [v2liruge] end. 915
,I/SA      ( 5156): [RC New] Execute end
I/SA      ( 5156): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5156): [OR] GetMyCountryZoneTask Success
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,V/HeadsetService( 5467): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5467): Disconnected process message: 10
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,I/splitIntent( 1015): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,I/splitIntent( 1015): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/hcjo    ( 5337): AutoUpdateManager:IDLE:execute,
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/InitializeManagerStateMachine( 5337): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5337): exit::IDLE
D/InitializeManagerStateMachine( 5337): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5337): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5337): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5337): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5337): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5337): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5337): entry::SUCCESS
D/hcjo    ( 5337): AutoUpdateManager:INITCHECK:onInitializeSuccess
,E/Zygote  ( 5985): MountEmulatedStorage(),
,E/Zygote  ( 5985): v2
I/libpersona( 5985): KNOX_SDCARD checking this for 10058
I/libpersona( 5985): KNOX_SDCARD not a persona
,I/SELinux ( 5985): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=5985 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/SELinux ( 5985): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5985): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/Zygote  ( 5995): MountEmulatedStorage()
I/libpersona( 5995): KNOX_SDCARD checking this for 10131
E/Zygote  ( 5995): v2
I/libpersona( 5995): KNOX_SDCARD not a persona
,I/SELinux ( 5995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/TimaKeyStoreProvider( 5985): TimaSignature is unavailable
I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5995 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 5995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5995): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
D/hcjo    ( 5337): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,I/FOTA_Client( 5816): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/ActivityThread( 5985): Added TimaKeyStore provider
,D/daemonapp( 1593): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1593): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1593): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/hcjo    ( 5337): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5337): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5337): exit::SUCCESS
,D/InitializeManagerStateMachine( 5337): entry::IDLE
,D/TimaKeyStoreProvider( 5995): TimaSignature is unavailable
,D/ActivityThread( 5995): Added TimaKeyStore provider
,I/FOTA_Client( 5816): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/daemonapp( 1593): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/ActivityManager( 1015): Killing 5219:com.wsomacp/u0a23 (adj 15): empty #31
,D/daemonapp( 1593): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/KLMS-2.5.123: ( 3376): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Dec 10 12:58:06 GMT+01:00 2015
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/ResourcesManager( 5995): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5995): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5995): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1593): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1593): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1593): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1593): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1593): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1593): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1593): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.5.123: ( 3376): KLMSAbstractReciever(): onReceive().END.
D/daemonapp( 1593): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/SA      ( 5156): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/daemonapp( 1593): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1593): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1593): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1593): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1593): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/KLMS-2.5.123: ( 3376): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3376): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3376): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3376): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,D/comdaemonstockapp( 1593): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET,
D/comdaemonstockapp( 1593): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
I/KLMS-2.5.123: ( 3376): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.123: ( 3376): StateImplV2(): dateTimeChanged().START : Thu Dec 10 12:58:06 GMT+01:00 2015
,I/KLMS-2.5.123: ( 3376): StateImplV2(): dateTimeChanged().END
,I/KLMS-2.5.123: ( 3376): KLMSIntentService(): onDestroy()
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1015): failed to open /acct/uid_10023/pid_5219/cgroup.procs: No such file or directory
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ExternalOEMControlProvider( 5985): onCreate
,E/Zygote  ( 6020): MountEmulatedStorage()
,E/Zygote  ( 6020): v2
I/libpersona( 6020): KNOX_SDCARD checking this for 10041
I/libpersona( 6020): KNOX_SDCARD not a persona
,I/SELinux ( 6020): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=6020 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux ( 6020): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6020): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1593): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1527): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1527): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 5985): Time Difference not stored. TIME_DIFFERENCE
,D/TimaKeyStoreProvider( 6020): TimaSignature is unavailable
,D/ActivityThread( 6020): Added TimaKeyStore provider
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6039): MountEmulatedStorage()
,E/Zygote  ( 6039): v2
I/libpersona( 6039): KNOX_SDCARD checking this for 10081
I/libpersona( 6039): KNOX_SDCARD not a persona
I/SELinux ( 6039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6039 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6039): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6050): MountEmulatedStorage()
,E/Zygote  ( 6050): v2
I/libpersona( 6050): KNOX_SDCARD checking this for 10037
I/libpersona( 6050): KNOX_SDCARD not a persona
,I/SELinux ( 6050): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6050): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6050 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6050): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6039): TimaSignature is unavailable
D/ActivityThread( 6039): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/TimaKeyStoreProvider( 6050): TimaSignature is unavailable
,D/ActivityThread( 6050): Added TimaKeyStore provider
,D/SecurityLogAgent( 5569): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5569): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5569): StateMachine : Current State = 1
,W/ResourcesManager( 6020): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6020): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6020): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6039): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6039): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6039): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6039): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,E/Zygote  ( 6070): MountEmulatedStorage(),
E/Zygote  ( 6070): v2
I/ActivityManager( 1015): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6070 uid=10153 gids={50153, 9997} abi=armeabi-v7a
I/libpersona( 6070): KNOX_SDCARD checking this for 10153,
I/libpersona( 6070): KNOX_SDCARD not a persona,
,I/SELinux ( 6070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6070): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6050): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/TimaKeyStoreProvider( 6070): TimaSignature is unavailable,
,D/ActivityThread( 6070): Added TimaKeyStore provider
,D/Mms/MmsApp( 6020): [start]    onCreate() consume time = 0.0
,W/ResourcesManager( 6070): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6086): MountEmulatedStorage()
E/Zygote  ( 6086): v2
,I/libpersona( 6086): KNOX_SDCARD checking this for 1000
I/libpersona( 6086): KNOX_SDCARD not a persona
I/SELinux ( 6086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6086): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6086): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6086 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5245:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31,
,I/ActivityManager( 1015): Killing 5265:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6086): TimaSignature is unavailable
,D/ActivityThread( 6086): Added TimaKeyStore provider
,I/CalendarProvider2( 6050): CalendarProvider2.onCreate() called
,D/TimeService( 6086): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449748686552
D/        ( 6086): TimeServiceNative: User Time to be set is 1449748686552
D/QC-time-services( 6086): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6086): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6086): Lib:time_genoff_operation: pargs->ts_val = 1449748686552
,D/QC-time-services( 6086): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  320): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  320): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449748686552
D/QC-time-services(  320): Daemon:genoff_opr: Base = 2, val = 1449748686552, operation = 0
,D/QC-time-services(  320): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/6/70 5:43:38
,D/QC-time-services(  320): Daemon:Value read from RTC seconds = 13499018000
D/QC-time-services(  320): Daemon:new time 1449748686552 
D/QC-time-services(  320): Daemon: delta 1436249668552 genoff 1436249668552 
D/QC-time-services(  320): Daemon:genoff_persistent_update: Writing genoff = 1436249668552 to memory
D/QC-time-services(  320): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  320): Daemon:time_persistent_memory_opr:Genoff write operation 
,W/art     ( 6020): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 152.033ms
,D/SettingsProvider( 1015): name = next_alarm_formatted
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10081
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5265/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10048/pid_5245/cgroup.procs: No such file or directory
,D/QC-time-services(  320): Updating the TOD offset
D/QC-time-services(  320): Daemon:genoff_persistent_update: Writing genoff = 1436249668552 to memory
D/QC-time-services(  320): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  320): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  320): Daemon:Update to modem bit set
D/QC-time-services(  320): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  320): Daemon: Base = 2, Value being sent to MODEM = 1120284868552
,E/QC-time-services( 6086): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager( 1015): Killing 5283:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #31
,E/QC-time-services(  320): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  320): Daemon: Time-services: Waiting to acceptconnection
,D/Mms/TelephonyPermission( 6020): start operation mode monitor
,D/Mms/ArtClassLoader( 6020): init before art
,W/ResourcesManager( 6020): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 6020): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 6020): isDefault true
,D/Mms/MmsApp( 6020): onCreate() com.android.mms
,D/Mms/MmsApp( 6020): [start]    initCountryIso consume time = 319.870364
,D/CountryDetector( 1015): The first listener is added
,D/Mms/MmsApp( 6020): [end]    initCountryIso consume time = 6.5875
,D/Mms/MmsConfig( 6020): [start]    MmsConfig.init() consume time = 0.43974
,D/Mms/MmsConfig( 6020): before partial update
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5283/cgroup.procs: No such file or directory
,D/Mms/MmsConfig( 6020): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 6020): serviceId : 1, features : -1
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5060): mConnectivityHandler : connected
,D/EasySignUpManager_1.0.1( 6020): isAuth is false
,D/Mms/MmsConfig( 6020): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1433): query,matched:2117, calling pid = 6020
,D/TP/MmsSmsProvider( 1433): match 2117:Elapsed time : 1.236 ms
,D/EasySignUpManager_1.0.1( 6020): isAuth is false
,D/EasySignUpManager_1.0.1( 6020): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 6020): mps_code.dat does not exist
W/PCWCLIENTTRACE_AccountUtil( 5060): [hasSamungAccount] - No Samsung Account
,E/CscParser( 6020): customer_path =/system/csc/customer.xml
E/CscParser( 6020): fileName + /system/csc/customer.xml
,W/art     ( 6039): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 179.007ms
,E/CscParser( 6020): mps_code.dat does not exist
,E/CscParser( 6020): customer_path =/system/csc/customer.xml
E/CscParser( 6020): fileName + /system/csc/customer.xml
,D/CscParser( 6020): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 6020):  enable multiwindow = false
,E/Mms/MessageUtils( 6020): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 6020): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 6020): [end]    init() consume time = 119.561093
,D/Mms/Contact( 6020): [start]    init() consume time = 0.949896
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5060): [GetString-S]
,I/ReactiveServiceManager( 5060): Supported : 1
,D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
D/Mms/Contact( 6020): [end]    init consume time = 14.684896
,D/Mms/DraftCache( 6020): [start]    rebuildCache consume time = 2.980469
,D/TP/MmsSmsProvider( 1433): query,matched:13, calling pid = 6020
,D/TP/MmsSmsProvider( 1433): query,matched:12, calling pid = 6020
,D/TP/MmsSmsProvider( 1433): match 13:Elapsed time : 0.959 ms
D/TP/MmsSmsProvider( 1433): match 12:Elapsed time : 1.237 ms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 9,
,E/Zygote  ( 6115): MountEmulatedStorage()
E/Zygote  ( 6115): v2
I/libpersona( 6115): KNOX_SDCARD checking this for 10090
I/libpersona( 6115): KNOX_SDCARD not a persona
,I/SELinux ( 6115): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6115): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6115 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 6115): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/QSEECOMAPI: ( 1015): QSEECom_dealloc_memory ,
D/QSEECOMAPI: ( 1015): QSEECom_shutdown_app, app_id = 9
I/ActivityManager( 1015): Killing 5300:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
E/terrier ( 1015): handleString: Failed to handle string(-4)
E/terrier ( 1015): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5060): getString is null,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5060): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5060): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5060): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5060): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5060): [ensureRegistration] - No Samsung account
,D/Mms/MethodReflector( 6020): getSubId is called
D/Mms/TelephonyUtils( 6020): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 6020): getTelephonyProperty is called
D/Mms/DownloadManager( 6020): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6020): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6020): auto download without roaming -> true
D/Mms/DownloadManager( 6020): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,D/Mms/MethodReflector( 6020): getSubId is called
,D/Mms/MethodReflector( 6020): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 6020): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 6020): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 6020): getTelephonyProperty is called
D/Mms/DownloadManager( 6020): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 6020): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 6020): auto download without roaming -> true
D/Mms/DownloadManager( 6020): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 6020): auto download during roaming secondary -> false
D/Mms/DownloadManager( 6020): mAutoDownload ------> true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/Mms/DraftCache( 6020): [end]    rebuildCache consume time = 75.693802
,D/TimaKeyStoreProvider( 6115): TimaSignature is unavailable
,D/ActivityThread( 6115): Added TimaKeyStore provider
,D/ComposerPerformance( 6020): 1449748686936 ms / [DONE] Composer constructor
,E/CII     ( 6020): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 6020): ReservationManager()
I/Mms/ReservationManager( 6020): resetAfterConnected()
,D/TP/MmsSmsProvider( 1433): query,matched:7, calling pid = 6020
,D/TP/MmsSmsProvider( 1433): match 7:Elapsed time : 1.911 ms
,I/Mms/ReservationManager( 6020): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/Conversation( 6020): [start]    init() consume time = 27.065729
,D/Mms/MmsApp( 6020): [end]    onCreate() consume time = 2.692812
,D/Mms/DownloadManager( 6020): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 6020): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 6020): getSubId is called
D/Mms/TelephonyUtils( 6020): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 6020): getTelephonyProperty is called
D/Mms/DownloadManager( 6020): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6020): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6020): auto download without roaming -> true
D/Mms/DownloadManager( 6020): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 6020): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 1433): deleteConversation threadId: 9223372036854775807
,D/Mms/ArtClassLoader( 6020): init [DONE] art
,I/ActivityManager( 1015): Killing 5320:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
,D/TP/MmsSmsProvider( 1433): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1433): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1433): sUpgradeVersion = 0, db.getVersion() = 81
,W/libprocessgroup( 1015): failed to open /acct/uid_10098/pid_5300/cgroup.procs: No such file or directory
,D/TP/MmsSmsProvider( 1433): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1433): need read changed broadcast:false
,D/Mms/Conversation( 6020): [end]    init consume time = 37.241094
D/Mms/MessagingNotification( 6020): [start]    init() consume time = 0.104271
,D/Mms/MessagingNotification( 6020): [end]    init consume time = 5.544896
,D/Mms/SpamFilter( 6020): [start]    SpamFilter fill() begin consume time = 2.173229
,D/elm:15121( 6115): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 6115): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6115): MDMBridge.setEnterpriseBridge()
,D/Mms/Synchronizer( 6020): [start]    doSync consume time = 4.809167
,D/TP/MmsSmsProvider( 1433): query,matched:0, calling pid = 6020
,V/TP/MmsSmsProvider( 1433): getSimpleConversations entered.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/TP/MmsSmsProvider( 1433): match 0:Elapsed time : 1.336 ms
,D/elm:15121( 6115): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
D/TP/MmsSmsProvider( 1433): update, matched:300, calling pid = 6020
V/TP/MmsSmsProvider( 1433): syncDBData start
,V/TP/MmsSmsProvider( 1433): syncDBData sms end
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,V/TP/MmsSmsProvider( 1433): syncDBData mms end
,V/TP/MmsSmsProvider( 1433): syncDBData end
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/Mms/Synchronizer( 6020): [end]    doSync consume time = 11.24026
D/TP/MmsSmsProvider( 1433): query,matched:400, calling pid = 6020
,D/elm:15121( 6115): ElmAgentService : onCreate()
,D/elm:15121( 6115): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,E/Zygote  ( 6137): MountEmulatedStorage()
I/libpersona( 6137): KNOX_SDCARD checking this for 10130
E/Zygote  ( 6137): v2
I/libpersona( 6137): KNOX_SDCARD not a persona
,I/SELinux ( 6137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,D/elm:15121( 6115): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,I/SELinux ( 6137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6137 uid=10130 gids={50130, 9997} abi=armeabi-v7a
D/elm:15121( 6115): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:15121( 6115): ModuleBase.ModifySetAlarm()
D/elm:15121( 6115): MDMBridge.getInstance()
D/elm:15121( 6115): MDMBridge.getAllLicenseInfoFromSDK()
E/SELinux ( 6137): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 6115): ElmAgentService : onDestroy().
,D/TimaKeyStoreProvider( 6137): TimaSignature is unavailable
,E/Zygote  ( 6149): MountEmulatedStorage()
E/Zygote  ( 6149): v2
I/libpersona( 6149): KNOX_SDCARD checking this for 10068
I/libpersona( 6149): KNOX_SDCARD not a persona
I/SELinux ( 6149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6149 uid=10068 gids={50068, 9997} abi=armeabi-v7a
E/SELinux ( 6149): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 4963:com.android.defcontainer/u0a3 (adj 15): empty #31
,D/ActivityThread( 6137): Added TimaKeyStore provider
,D/Mms/SpamFilter( 6020): [end]    SpamFilter fill() finished consume time = 54.015573
,I/ActivityManager( 1015): Killing 5613:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
,I/art     (  304): Explicit concurrent mark sweep GC freed 8680(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 628us total 26.377ms
,D/TimaKeyStoreProvider( 6149): TimaSignature is unavailable
,D/ActivityThread( 6149): Added TimaKeyStore provider
,E/Watchdog( 1015): !@Sync 5
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 17.299ms
,W/ResourcesManager( 6137): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6137): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 5631:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 18.291ms
,D/BadgeProvider( 6149): onCreate
,D/BadgeProvider( 6149): DatabaseHelper
,I/DBG_POLICYDM( 5092): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/Mms/MessagingNotification( 6020): checkBadgeCount unreadCount=0 badgeCount=0
I/DBG_POLICYDM( 5092): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,D/TP/SmsProvider( 1433): query,matched:26, calling pid = 6020
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,D/TP/SmsProvider( 1433): match 26:Elapsed time : 1.681 ms
I/DBG_POLICYDM( 5092): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5092): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/DBG_POLICYDM( 5092): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,I/splitIntent( 1015): Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 5511:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,D/TP/MmsSmsProvider( 1433): query,matched:6, calling pid = 6020
,D/TP/MmsSmsProvider( 1433): match 6:Elapsed time : 3.724 ms
,W/libprocessgroup( 1015): failed to open /acct/uid_10052/pid_5320/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10065/pid_5631/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10064/pid_5613/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/libprocessgroup( 1015): failed to open /acct/uid_10003/pid_4963/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/DBG_POLICYDM( 5092): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5092): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3672): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3672): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 6168): MountEmulatedStorage(),
E/Zygote  ( 6168): v2
I/libpersona( 6168): KNOX_SDCARD checking this for 10023
,I/libpersona( 6168): KNOX_SDCARD not a persona
,I/SELinux ( 6168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6168 uid=10023 gids={50023, 9997} abi=armeabi-v7a
E/SELinux ( 6168): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10055/pid_5511/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6168): TimaSignature is unavailable
,D/ActivityThread( 6168): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 6168): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,D/Mms/Omacp( 6020): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 6168): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/VacuumService( 1688): Vacuum at: now=1449748687419 tag=VacuumService
,I/GoogleURLConnFactory( 1688): Using platform SSLCertificateSocketFactory
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 14087(721KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.560ms total 138.989ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5717): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/Babel   ( 3672): UserRecoverableAuthException.
,E/Babel   ( 3672): eei: BadAuthentication
E/Babel   ( 3672): 	at eeg.a(Unknown Source)
E/Babel   ( 3672): 	at eeg.a(Unknown Source)
E/Babel   ( 3672): 	at eeg.a(Unknown Source)
E/Babel   ( 3672): 	at g.a(Unknown Source)
E/Babel   ( 3672): 	at cae.a(SourceFile:3089)
E/Babel   ( 3672): 	at cae.a(SourceFile:1131)
E/Babel   ( 3672): 	at cws.a(SourceFile:4333)
E/Babel   ( 3672): 	at cws.a(SourceFile:1419)
E/Babel   ( 3672): 	at crl.a(SourceFile:492)
E/Babel   ( 3672): 	at crl.a(SourceFile:1468)
E/Babel   ( 3672): 	at cqu.a(SourceFile:4416)
E/Babel   ( 3672): 	at cas.b(SourceFile:106)
E/Babel   ( 3672): 	at cap.d(SourceFile:335)
E/Babel   ( 3672): 	at caq.run(SourceFile:81)
,E/Babel   ( 3672): Error getting auth token
,E/Babel   ( 3672): dvm
E/Babel   ( 3672): 	at g.a(Unknown Source)
E/Babel   ( 3672): 	at cae.a(SourceFile:3089)
E/Babel   ( 3672): 	at cae.a(SourceFile:1131)
E/Babel   ( 3672): 	at cws.a(SourceFile:4333)
E/Babel   ( 3672): 	at cws.a(SourceFile:1419)
E/Babel   ( 3672): 	at crl.a(SourceFile:492)
E/Babel   ( 3672): 	at crl.a(SourceFile:1468)
E/Babel   ( 3672): 	at cqu.a(SourceFile:4416)
E/Babel   ( 3672): 	at cas.b(SourceFile:106)
E/Babel   ( 3672): 	at cap.d(SourceFile:335)
E/Babel   ( 3672): 	at caq.run(SourceFile:81)
D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Babel   ( 3672): Account registration failed 1-Redacted-21
,E/Babel   ( 3672): cyp: null -- null
E/Babel   ( 3672): 	at cae.a(SourceFile:3121)
E/Babel   ( 3672): 	at cae.a(SourceFile:1131)
E/Babel   ( 3672): 	at cws.a(SourceFile:4333)
E/Babel   ( 3672): 	at cws.a(SourceFile:1419)
E/Babel   ( 3672): 	at crl.a(SourceFile:492)
E/Babel   ( 3672): 	at crl.a(SourceFile:1468)
E/Babel   ( 3672): 	at cqu.a(SourceFile:4416)
E/Babel   ( 3672): 	at cas.b(SourceFile:106)
E/Babel   ( 3672): 	at cap.d(SourceFile:335)
E/Babel   ( 3672): 	at caq.run(SourceFile:81)
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/art     ( 3672): Note: end time exceeds epoch: 
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/System.out( 3672): (HTTPLog)-Static: isSBSettingEnabled false
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
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,I/System.out( 1688): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1688): (HTTPLog)-Static: isShipBuild true
I/System.out( 1688): (HTTPLog)-Thread-204-741934137: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10011
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1688): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/qtaguid ( 1688): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/qtaguid ( 1688): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/art     ( 1688): Explicit concurrent mark sweep GC freed 30575(1867KB) AllocSpace objects, 10(194KB) LOS objects, 39% free, 7MB/12MB, paused 1.232ms total 62.623ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 1688): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MusicLeanback( 5698): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 5698): Stop autocaching.
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Babel   ( 3672): Unexpected exception while authenticating.
,E/Babel   ( 3672): eej: User intervention required. Notification has been pushed.
E/Babel   ( 3672): 	at eeg.b(Unknown Source)
E/Babel   ( 3672): 	at eeg.b(Unknown Source)
E/Babel   ( 3672): 	at g.a(Unknown Source)
E/Babel   ( 3672): 	at cae.b(SourceFile:1146)
E/Babel   ( 3672): 	at dcg.run(SourceFile:5617)
E/Babel   ( 3672): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 3672): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 3672): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,E/Zygote  ( 6201): MountEmulatedStorage()
,E/Zygote  ( 6201): v2
I/libpersona( 6201): KNOX_SDCARD checking this for 10011
I/libpersona( 6201): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6201 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/SELinux ( 6201): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6201): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6201): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TimaKeyStoreProvider( 6201): TimaSignature is unavailable
,D/ActivityThread( 6201): Added TimaKeyStore provider
,I/CalendarProvider2( 6050): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
W/ResourcesManager( 6201): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6201): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/MultiDex( 6201): VM with version 2.1.0 has multidex support
I/MultiDex( 6201): install
I/MultiDex( 6201): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6201): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/Uploader( 1688): No account for auth token provided
W/ActivityThread( 6201): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6201): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32698725: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6201): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1688): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1688): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1883): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6201): callingUid 10011, callindPid: 6201
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1883): Restart initialization of location
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1654): [181] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1688): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,E/GmsUtils( 5698): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5698): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Uploader( 1688):  no longer exists, so no auth token.
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,W/Uploader( 1688): No account for auth token provided
,I/System.out( 1688): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1688): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1688, getuid(): 10011
,I/dhcpcd  ( 5657): wlan0: sending IPv6 Router Solicitation
,E/SQLiteLog( 1688): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD OFF
,I/Mms/MmsApp( 6020):  start initViewCache mms
D/Mms/ComposeMessageFragment( 6020): [start]    fillCache consume time = 1885.274374
D/Mms/ComposeMessageFragment( 6020): fillCache, easy = false
,D/AbsListView( 6020): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 6020): [end]    fillCache consume time = 67.880781
,D/Mms/BubbleViewCache( 6020): fillCache bubble = 1
,I/jxcore-log( 5416): Test app app.js loaded
I/jxcore-log( 5416): 
,I/chromium( 5416): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/SSRM:n  ( 1015): SIOP:: AP = 340,
,E/SMD     (  288): DCD OFF
,I/dhcpcd  ( 5657): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 5657): wlan0: no IPv6 Routers available
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,D/Finsky  ( 4731): [785] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4731): [785] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/ActivityManager( 1015): Killing 5060:com.sec.pcw.device/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 5771:com.sec.android.cloudagent/u0a1 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5060/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10001/pid_5771/cgroup.procs: No such file or directory
,I/ActivityManager( 1015): Killing 5792:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5792/cgroup.procs: No such file or directory
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5467): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5467): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5337): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5337): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5337): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5337): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5337): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5337): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5337): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5337): entry::IDLE
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 310
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4731): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4731): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4731): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 300,
,I/PowerManagerService( 1015): [PWL] Off : 140s ago,
,V/AlarmManager( 1015): waitForAlarm result :4,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 6,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4731): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4731): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4731): [1] 5.onFinished: Giving up after 6 failures.
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 5717): Starting books sync for 61035162, extras: ade
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 5717): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5717): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5717): Soft error
E/BooksSync( 5717): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5717): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5717): Sync error
E/BooksSync( 5717): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5717): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5717): Finished books sync
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 196083, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/EventLogService( 1883): Aggregate from 1449746944920 (log), 1449746944920 (data)
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/Watchdog( 1015): !@Sync 7
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/PowerManagerService( 1015): [PWL] Off : 180s ago
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 8
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 280
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 225s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK,
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 5717): Starting books sync for 61035162, extras: ade
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 40016(2MB) AllocSpace objects, 52(845KB) LOS objects, 33% free, 23MB/35MB, paused 2.465ms total 137.865ms
,I/BooksConfig( 5717): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksAccountManager( 5717): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5717): Soft error
E/BooksSync( 5717): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5717): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5717): Sync error
E/BooksSync( 5717): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5717): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5717): Finished books sync
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 286648, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5467): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5467): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SQLiteLog( 1688): (10) POSIX Error : 11 SQLite Error : 3850
,E/Watchdog( 1015): !@Sync 9
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 280
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5467): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5467): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1015): initializing...,
I/TLC_TIMA_PKM_initialize( 1015): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): aligned max_recvmsg_size = 262208 = 0x40040,
,I/TZ: qc_tlc_communication( 1015): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 10
,I/TZ: qc_tlc_communication( 1015): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1015): Trustlet response is completed
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5467): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5467): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/Watchdog( 1015): !@Sync 10,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 275s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5467): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5467): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1688): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1688): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1688): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1688): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1688): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1688): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1688): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1688): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1688): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1688): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1688): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1688): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 4731): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4731): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4731): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4731): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4731): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4731): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4731): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4731): Ignoring header User-Agent because its value was null.
,I/System.out( 4731): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 4731): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 4731): (HTTPLog)-Static: isShipBuild true
I/System.out( 4731): (HTTPLog)-Thread-803-4424597: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4731): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10026
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/System.out( 4731): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/Watchdog( 1015): !@Sync 11,
,V/HeadsetService( 5467): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5467): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5467): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5467): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 12
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged,
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 5467): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5467): Disconnected process message: 10,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 330s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5467): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5467): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 5416): Toggling radios to false
I/jxcore-log( 5416): 
,D/BluetoothAdapter( 5416): disable()
,D/SettingsProvider( 1015): name = bluetooth_on
,D/BluetoothAdapterState( 5467): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 5467): Setting state to 13
I/BluetoothAdapterState( 5467): Bluetooth adapter state changed: 12-> 13,
D/BluetoothAdapterService( 5467): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5467): updateAdapterState state is 13
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
,D/WifiService( 1015): setWifiEnabled: false pid=5416, uid=10338
D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1015): mCursor = null
I/BluetoothPbapService( 5467): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/BluetoothSocket( 5467): close() in, this: android.bluetooth.BluetoothSocket@9ba00fa, channel: 19, state: LISTENING
D/BluetoothSocket( 5467): close() this: android.bluetooth.BluetoothSocket@9ba00fa, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e301fa2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@bdac6abmSocket: android.net.LocalSocket@7f0e108 impl:android.net.LocalSocketImpl@1a5070a1 fd:FileDescriptor[74]
D/BluetoothSocket( 5467): Closing mSocket: android.net.LocalSocket@7f0e108 impl:android.net.LocalSocketImpl@1a5070a1 fd:FileDescriptor[74]
D/SettingsProvider( 1015): name = wifi_on
,D/BluetoothAdapterService( 5467): Autoconnection is available 
,D/BluetoothAdapterService( 5467): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 5467): terminating service from this receiver
,D/BluetoothPbap( 1296): Proxy object disconnected
D/PbapServerProfile( 1296): Bluetooth service disconnected
W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1015): [BT Setting State] State =13
,E/WifiStateMachine( 1015): WifiStateMachine: Leaving Connected state
,I/jxcore-log( 5416): Radios toggled
I/jxcore-log( 5416): 
,I/wpa_supplicant( 5533): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5533): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 5533): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 5533): Scan requested (ret=0) - scan timeout 30 seconds
,D/BluetoothTile( 1177):  onBluetoothStateChange:
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 13
,I/SamsungIME( 1791): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothSocket( 5467): close() in, this: android.bluetooth.BluetoothSocket@a7d2287, channel: 5, state: LISTENING
D/BluetoothSocket( 5467): close() this: android.bluetooth.BluetoothSocket@a7d2287, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d6d0433, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@133705b4mSocket: android.net.LocalSocket@f6275dd impl:android.net.LocalSocketImpl@12c3b552 fd:FileDescriptor[76]
D/BluetoothSocket( 5467): Closing mSocket: android.net.LocalSocket@f6275dd impl:android.net.LocalSocketImpl@12c3b552 fd:FileDescriptor[76]
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Bluetooth
,V/BluetoothEventManager( 1296): Received android.bluetooth.adapter.action.STATE_CHANGED
I/BtOppRfcommListener( 5467): stopping Accept Thread
D/BluetoothSocket( 5467): close() in, this: android.bluetooth.BluetoothSocket@2dff6023, channel: 12, state: LISTENING
D/BluetoothSocket( 5467): close() this: android.bluetooth.BluetoothSocket@2dff6023, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32698725, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2318c920mSocket: android.net.LocalSocket@2d9592d9 impl:android.net.LocalSocketImpl@2843d49e fd:FileDescriptor[80]
D/BluetoothSocket( 5467): Closing mSocket: android.net.LocalSocket@2d9592d9 impl:android.net.LocalSocketImpl@2843d49e fd:FileDescriptor[80]
,E/BtOppRfcommListener( 5467): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/WifiNative-wlan0( 1015): do suspend true
I/BtOppRfcommListener( 5467): BluetoothSocket listen thread finished
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/BluetoothAdapterProperties( 5467): onBluetoothDisable()
D/BluetoothAdapterProperties( 5467): mDiscovering is false
,D/SecContentProvider( 1015): uri = 3 selection = isDiscoverableEnabled
I/BluetoothAdapterState( 5467): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=false
,D/BluetoothAdapterProperties( 5467): Scan Mode:20
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothAdapterState( 5467): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 5467): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
E/bt-btif ( 5467): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
E/bt-btif ( 5467): cmd socket is not created
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
D/btif_config_util( 5467): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 5467): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 5467): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 5467): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5467): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5467): L2CAP - PSM: 0x001b not found for deregistration
,V/BluetoothOppManager( 5467): cleanUp...
,D/DockEventReceiver( 1296): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1296): onReceive
,V/BluetoothStatusReceiver( 1177): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1177): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6349): MountEmulatedStorage()
E/Zygote  ( 6349): v2
I/libpersona( 6349): KNOX_SDCARD checking this for 10055
,I/libpersona( 6349): KNOX_SDCARD not a persona
,I/SELinux ( 6349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6349 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 6349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6349): TimaSignature is unavailable
,D/ActivityThread( 6349): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 6349): PlaceProvider onCreate()
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/CommandListener(  278): Clearing all IP addresses on wlan0,
V/NativeCrypto( 1688): Read error: ssl=0xb92bffd0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1688): SSL shutdown failed: ssl=0xb92bffd0: I/O error during system call, Broken pipe
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService( 1015): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
I/qtaguid ( 1015): Tagging socket 392 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
,D/WifiP2pService( 1015): InactiveState{ what=131204 },
,D/WifiP2pService( 1015): P2pEnabledState{ what=131204 }
,I/qtaguid ( 1015): Untagging socket 392
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,D/WifiNetworkAgent( 1015): NetworkAgent: NetworkAgent channel lost
D/WifiP2pService( 1015): sending p2p connection changed broadcast: FAILED
,D/UserAnalysis.SecureDbManager( 6349): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 6349): SecurePlaceDbHelper() 
D/UserAnalysis( 6349): Create SecureDbHelper
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiScanningService( 1015): SCAN_AVAILABLE : 1
D/WifiScanningService( 1015): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1015): SCAN_AVAILABLE : 1
D/RttService( 1015): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/IntelligenceServiceApplication( 6349): onCreate()
,D/WifiP2pService( 1015): sending p2p connection changed broadcast: DISCONNECTED
,D/WifiP2pService( 1015): P2pDisablingState
D/WifiP2pService( 1015): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1015): p2p socket connection lost
D/WifiP2pService( 1015): P2pDisabledState
,E/WifiNative-wlan0( 1015): do suspend true,
D/WifiDisplayController( 1015): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1015): onP2pDisconnected
,D/WifiP2pService( 1015): P2pDisabledState{ what=143375 },
D/WifiP2pService( 1015): DefaultState{ what=143375 }
,E/WifiStateMachine( 1015): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/IntelligenceServiceApplication( 6349): no applications having user consent for prediction
I/ActivityManager( 1015): Killing 4365:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
W/bt-l2cap( 5467): btif_mce_execute_service enable:0
D/IpRemoteDisplayController( 1015): disconnectWfdBridgeServer
W/bt-l2cap( 5467): L2CAP - PSM: 0x0017 not found for deregistration
D/IpRemoteDisplayController( 1015): WfdBridgeServer is already null
W/bt-l2cap( 5467): L2CAP - PSM: 0x001b not found for deregistration
,D/WifiDisplayController( 1015): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
W/bt-l2cap( 5467): HC lib lpm enable=0 return 0
D/WifiDisplayController( 1015): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
W/bt-l2cap( 5467): L2CAP - PSM: 0x0017 not found for deregistration
D/WifiDisplayController( 1015): disconnect
W/bt-l2cap( 5467): L2CAP - PSM: 0x001b not found for deregistration
D/WifiDisplayController( 1015): updateConnection
W/bt-l2cap( 5467): L2CAP - PSM: 0x0019 not found for deregistration
,D/WifiDisplayController( 1015): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
W/bt-l2cap( 5467): L2CAP - PSM: 0x0017 not found for deregistration
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/bt-l2cap( 5467): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 5467): ag scb idx 1 not allocated
W/bt-btif ( 5467): ag scb idx 2 not allocated
E/bt-btif ( 5467): BTA AG is already disabled, ignoring ...
I/bt_userial_mct( 5467): exiting userial_read_thread
D/bt_userial_mct( 5467): Leaving userial_evt_read_thread()
,V/PlaceDetection v1.0.19 ( 6349): [PlaceDetection::stopService] Service stopped.
D/bt_userial_mct( 5467): userial_close_reader Joined userial reader thread: 0
,I/bt_vendor( 5467): hw_epilog_process
D/bt_userial_mct( 5467): userial_close
I/bt_vendor( 5467): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,V/PlaceDetection v1.0.19 ( 6349): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/ConnectivityService( 1015): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 1015): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1015): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1015): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1015): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1433): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1433): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/AllShareCastTile( 1177): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
D/AllShareCastTile( 1177): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/AuthorizationBluetoothService( 1688): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1015): nai.networkMonitor.doQuit()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/wpa_supplicant( 5533): p2p0: State: DISCONNECTED -> DISCONNECTED
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): doQuit - quitNow()
E/ConnectivityService( 1015): updateNetworkInfo()
E/ConnectivityService( 1015): updateNetworkInfo()
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1015): MasterInitialState.processMessage what=3
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): updateIfacesLocked()
V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked() took 5ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1177): EthernetConnected: false
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/SecContentProvider2( 1015): mCursor = null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(0)
D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1177): onReceive : 0, 0
D/WifiCredService( 1296): Action received :android.net.wifi.WIFI_STATE_CHANGED
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3355): Starting #8
I/Hs20UtilService( 3355): Message received 5007
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1296): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1296): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1296): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1296): MountReceiver.mPrefHandler - 7002
D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1296): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1296): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1296): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6372): MountEmulatedStorage()
,E/Zygote  ( 6372): v2
I/libpersona( 6372): KNOX_SDCARD checking this for 10064
I/libpersona( 6372): KNOX_SDCARD not a persona
,I/SELinux ( 6372): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6372): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6372): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6372 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup( 1015): failed to open /acct/uid_10039/pid_4365/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6372): TimaSignature is unavailable
,D/ActivityThread( 6372): Added TimaKeyStore provider
,I/wpa_supplicant( 5533): Blacklist: Clear (all) 
,W/ResourcesManager( 6372): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
D/FileShare-Client( 6372): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileShare-Client( 6372): ClientBroadcastReceiver.onReceive - disconnected
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
,D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
,D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
,D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
,D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
,D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3,
D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
,D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
,D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
,D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
,D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
,D/FileShare-Client( 6372): Outbound.stopDelayTimer - 
,D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PhoneApp( 1433): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/FileWriteThread_Telephony( 1433): FileWriteThread : threadType = 3
,I/wpa_supplicant( 5533): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1015): interfaceLinkStateChanged p2p0, false
D/Tethering( 1015): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged p2p0, false
,E/Zygote  ( 6402): MountEmulatedStorage()
,E/Zygote  ( 6402): v2
I/libpersona( 6402): KNOX_SDCARD checking this for 10065
I/libpersona( 6402): KNOX_SDCARD not a persona
,I/SELinux ( 6402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6402 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/SELinux ( 6402): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 5834:com.sec.android.soagent/u0a31 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6402): TimaSignature is unavailable
,D/ActivityThread( 6402): Added TimaKeyStore provider
,I/wpa_supplicant( 5533): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/bt_vendor( 5467): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 5467): bluetooth satus is on
I/bt_vendor( 5467): bt-vendor : resetting BT status
I/bt_vendor( 5467): Starting hciattach daemon
I/bt_vendor( 5467): try to set false
I/wpa_supplicant( 5533): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 5533): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 5533): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 5533): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,D/Tethering( 1015): InitialState.processMessage what=4
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
I/bt_vendor( 5467): Starting hciattach daemon
,I/bt_vendor( 5467): try to set false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/bt_vendor( 5467): cleanup
,I/GKI_LINUX( 5467): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 5467): GKI_exit_task 0 done
I/GKI_LINUX( 5467): GKI_shutdown(): task [BTU] terminated
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
E/Tethering( 1015): No numeric data
,D/BluetoothAdapterState( 5467): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5467): isSecureModeOn:false
D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1015): clearTetheredNotification()
D/BluetoothAdapterService( 5467): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 5467): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.gatt.GattService
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,V/NetworkStats( 1015): performPollLocked() took 4ms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
W/BluetoothAdapterService( 5467): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 5467): handleDebugAction() action=null
,D/BtGatt.GattService( 5467): Received stop request...Stopping profile...
D/BtGatt.GattService( 5467): stop()
D/BtGatt.AdvertiseManager( 5467): advertise clients cleared
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
W/BluetoothAdapterService( 5467): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService,
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,D/HeadsetService( 5467): Received stop request...Stopping profile...
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,D/AudioService( 1015): onServiceDisconnected: Bluetooth profile: 1
,D/HeadsetProfile( 1296): Bluetooth service disconnected
W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.hid.HidService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.hdp.HealthService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.pan.PanService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
W/BluetoothAdapterService( 5467): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService,
D/FileShare-Server( 6402): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
W/BluetoothAdapterService( 5467): Not skipping com.android.bluetooth.map.BluetoothMapService
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5467): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5467): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5467): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
I/ActivityManager( 1015): Killing 5092:com.policydm/1000 (adj 15): empty #31
W/BluetoothAdapterService( 5467): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5467): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5467): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5467): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5467): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,D/BluetoothAdapterState( 5467): Stopping profile services that were post enabled
E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/A2dpService( 5467): Received stop request...Stopping profile...
,D/A2dpStateMachine( 5467): Exit Disconnected: -1
,D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/BluetoothA2dp( 1015): Proxy object disconnected
D/AudioService( 1015): onServiceDisconnected: Bluetooth profile: 2
,D/BluetoothA2dp( 1296): Proxy object disconnected
D/A2dpProfile( 1296): Bluetooth service disconnected
I/Hs20UtilService( 3355): Starting #9
,I/Hs20UtilService( 3355): Message received 5007
,E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5467): Profile still running: com.android.bluetooth.hid.HidService
D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
W/BluetoothHeadsetServiceJni( 5467): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5467): Cleaning up Bluetooth Handsfree callback object
V/NearbySettings( 1296): DMSUtil.isNetworkConnected - flag-null, state-null
,D/HidService( 5467): Received stop request...Stopping profile...
D/HidService( 5467): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 5467): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5467): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5467): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/HealthService( 5467): Received stop request...Stopping profile...,
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,D/PanService( 5467): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,D/BluetoothPan( 1015): BluetoothPAN Proxy object disconnected,
D/BluetoothMapService( 5467): Received stop request...Stopping profile...
I/NearbySettings( 1296): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1296): MountReceiver.onReceive - Set preference state off
D/BluetoothInputDevice( 1296): Proxy object disconnected
,D/HidProfile( 1296): Bluetooth service disconnected
D/BluetoothPan( 1296): BluetoothPAN Proxy object disconnected
D/PanProfile( 1296): Bluetooth service disconnected
,V/NearbySettings( 1296): MountReceiver.mPrefHandler - 7002
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,D/SapService( 5467): Received stop request...Stopping profile...
,D/SapService( 5467): Stopping Bluetooth SapService
D/BluetoothAdapterService( 5467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f11ac48
,E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService( 5467): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 5467): Proxy object disconnected
D/BluetoothAdapterService( 5467): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 5467): gki_task task_id=2 [A2DP-MEDIA] terminating
D/BluetoothMap( 1296): Proxy object disconnected
I/GKI_LINUX( 5467): GKI_exit_task 2 done
I/GKI_LINUX( 5467): GKI_shutdown(): task [A2DP-MEDIA] terminated
,E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5467): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5467): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 5467): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5467): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5467): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 5467): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5467): Cleaning up Bluetooth PAN callback object
D/MapProfile( 1296): Bluetooth service disconnected
,E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 5467): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5467): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(1058122824)( 5467): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 5467): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 5467): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/Bluetoothsap( 1296): BluetoothSAP Proxy object disconnected
,D/SapProfile( 1296): Bluetooth service disconnected
,D/BluetoothAdapterState( 5467): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 5467): Setting state to 10
I/BluetoothAdapterState( 5467): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5467): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5467): updateAdapterState state is 10
,D/BluetoothA2dp( 1015): onBluetoothStateChange: up=false
D/BluetoothAdapterService( 5467): Autoconnection is available 
,D/BluetoothAdapterService( 5467): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 5467): Entering OffState
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/BluetoothAdapter( 1420): onBluetoothStateChange: up=false
,I/Hs20UtilService( 3355): Starting #10
,I/Hs20UtilService( 3355): Message received 5011
D/BluetoothAdapter( 1420): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 5416): onBluetoothStateChange: up=false
D/BluetoothAdapter( 5416): Bluetooth is turned off, stop adv and scan
,D/BluetoothPbap( 1296): onBluetoothStateChange: up=false
,D/SecurityLogAgent( 5569): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5569): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5569): StateMachine : Current State = 1
D/SecurityLogAgent( 5569): StateMachine : Changed Current State = 1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothAdapter( 1654): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1654): Bluetooth is turned off, stop adv and scan
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothA2dp( 5467): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 5467): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 5467): Bluetooth is turned off, stop adv and scan
D/BluetoothA2dp( 1296): onBluetoothStateChange: up=false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothAdapter( 1015): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1015): Bluetooth is turned off, stop adv and scan
D/BluetoothMap( 1296): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 1296): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1177): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1177): Bluetooth is turned off, stop adv and scan
D/Bluetoothsap( 1296): onBluetoothStateChange: up=false
D/Bluetoothsap( 1296): Unbinding service...
,D/BluetoothAdapter( 1410): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1410): Bluetooth is turned off, stop adv and scan
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothAdapter( 1433): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1433): Bluetooth is turned off, stop adv and scan
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothAdapter( 1296): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1296): Bluetooth is turned off, stop adv and scan
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceUp() to 0 receivers.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/GKI_LINUX( 5467): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 5467): GKI_exit_task 1 done
I/GKI_LINUX( 5467): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 5467): cleanupNative: return from cleanup
,D/BluetoothAdapter( 1177): 48977163: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,D/BluetoothAdapter( 1177): 48977163: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 10
D/BluetoothAdapter( 1177): 48977163: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1177): 48977163: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1177): 48977163: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,V/BluetoothEventManager( 1296): Received android.bluetooth.adapter.action.STATE_CHANGED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=false
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
I/SamsungIME( 1791): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/art     ( 5467): System.exit called, status: 0
I/AndroidRuntime( 5467): VM exiting with result code 0, cleanup skipped.
,W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1015): [BT Setting State] State =10
I/InputMethodManagerService( 1015): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/libprocessgroup( 1015): failed to open /acct/uid_10031/pid_5834/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5092/cgroup.procs: No such file or directory
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/DockEventReceiver( 1296): finishStartingService: stopping service
,I/wpa_supplicant( 5533): Blacklist: Clear (all) 
D/BluetoothNotiBroadcastReceiver( 1296): onReceive
,V/BluetoothStatusReceiver( 1177): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1177): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,I/wpa_supplicant( 5533): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager( 1015): Process com.android.bluetooth (pid 5467)(adj 0) has died(53,636)
,I/ApplicationPolicy( 1015): updateDataUsageMap
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/AuthorizationBluetoothService( 1688): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6421): MountEmulatedStorage()
E/Zygote  ( 6421): v2
I/libpersona( 6421): KNOX_SDCARD checking this for 1000
I/libpersona( 6421): KNOX_SDCARD not a persona
,I/SELinux ( 6421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6421 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6421): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6421): TimaSignature is unavailable
,D/ActivityThread( 6421): Added TimaKeyStore provider
,E/WifiStateMachine( 1015): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [21]
,W/Settings( 3672): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PCWCLIENTTRACE_LOG( 6421): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 6421): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6421): new DMDBOpenHelper instance
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(1)
D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
D/HotspotTile( 1177): onReceive : 1, 0
,W/Settings( 1654): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiCredService( 1296): Action received :android.net.wifi.WIFI_STATE_CHANGED
,I/PCWCLIENTTRACE_PushUtil( 6421): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6421): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6421): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6421): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
,I/splitIntent( 1015): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1015): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/PCWCLIENTTRACE_SYSTEMReceiver( 6421): noConnectivity : true
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 5698): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager( 1015): Killing 5861:com.samsung.android.sconnect/u0a121 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10121/pid_5861/cgroup.procs: No such file or directory
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6438): MountEmulatedStorage()
,E/Zygote  ( 6438): v2
I/libpersona( 6438): KNOX_SDCARD checking this for 10001
I/libpersona( 6438): KNOX_SDCARD not a persona
,I/SELinux ( 6438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6438 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6438): TimaSignature is unavailable
,D/ActivityThread( 6438): Added TimaKeyStore provider
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6455): MountEmulatedStorage(),
I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6455 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6455): v2
I/libpersona( 6455): KNOX_SDCARD checking this for 1000
I/libpersona( 6455): KNOX_SDCARD not a persona
,I/SELinux ( 6455): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Killing 5537:com.android.email/u0a141 (adj 15): empty #31,
,I/SELinux ( 6455): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6455): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6455): TimaSignature is unavailable,
D/ActivityThread( 6455): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6455): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1015): failed to open /acct/uid_10141/pid_5537/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6455): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6455): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6455): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6455): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6455): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6455): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,I/ActivityManager( 1015): Killing 5906:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3376): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 13:01:59 GMT+01:00 2015
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3376): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3376): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3376): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3376): KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,I/KLMS-2.5.123: ( 3376): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3376): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3376): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3376): StateImplV2(): networkChangeListener().END
,E/Zygote  ( 6471): MountEmulatedStorage(),
I/libpersona( 6471): KNOX_SDCARD checking this for 10031
,E/Zygote  ( 6471): v2,
I/libpersona( 6471): KNOX_SDCARD not a persona
I/SELinux ( 6471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6471 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6471): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3376): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6471): TimaSignature is unavailable
,D/ActivityThread( 6471): Added TimaKeyStore provider,
,I/SO_AGENT( 6471): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6486): MountEmulatedStorage()
,E/Zygote  ( 6486): v2
I/libpersona( 6486): KNOX_SDCARD checking this for 1000
,I/libpersona( 6486): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=6486 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 6486): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Killing 5962:com.android.chrome/u0a77 (adj 15): empty #31
,I/SELinux ( 6486): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6486): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SMD     (  288): DCD OFF
,D/TimaKeyStoreProvider( 6486): TimaSignature is unavailable
,D/ActivityThread( 6486): Added TimaKeyStore provider,
,W/libprocessgroup( 1015): failed to open /acct/uid_10110/pid_5906/cgroup.procs: No such file or directory
,D/Tethering( 1015): interfaceRemoved wlan0
E/Tethering( 1015): attempting to remove unknown iface (wlan0), ignoring
,I/DBG_POLICYDM( 6486): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,W/libprocessgroup( 1015): failed to open /acct/uid_10077/pid_5962/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 6486): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 6486): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 6486): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 6486): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 6486): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 6486): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 6486): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 6486): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 6486): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 6486): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 6486): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 6486): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 6486): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 6486): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 6486): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 6486): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5156): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5156): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 5156): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5156): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5156): [OR] == isSIMCardReady false ==
,I/SA      ( 5156): [SCU] == networkStateCheck == false
,I/SA      ( 5156): [OR] onReceive END
,I/DBG_POLICYDM( 6486): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 6486): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
I/ActivityManager( 1015): Killing 4792:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,E/DBG_POLICYDM( 6486): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 6486): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,V/DownloadManager( 1225): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1527): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1593): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 1527): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1527): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1527): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1527): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1527): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1527): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6506): MountEmulatedStorage()
,E/Zygote  ( 6506): v2
,I/libpersona( 6506): KNOX_SDCARD checking this for 10121
,I/libpersona( 6506): KNOX_SDCARD not a persona
I/SELinux ( 6506): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6506 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6506): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/DBG_POLICYDM( 6486): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,E/SELinux ( 6506): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 6486): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 6486): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 6486): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/art     (  304): Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 651us total 26.453ms
,D/TimaKeyStoreProvider( 6506): TimaSignature is unavailable
D/ActivityThread( 6506): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 622us total 16.431ms
,W/ResourcesManager( 6506): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6506): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6506): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.767ms
,D/Tethering( 1015): interfaceRemoved p2p0
E/Tethering( 1015): attempting to remove unknown iface (p2p0), ignoring
,D/QuickConnect( 6506): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6506): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6506): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6523): MountEmulatedStorage()
,E/Zygote  ( 6523): v2
I/libpersona( 6523): KNOX_SDCARD checking this for 10141
I/libpersona( 6523): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6523 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5985:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,I/SELinux ( 6523): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6523): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6523): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6523): TimaSignature is unavailable
,D/ActivityThread( 6523): Added TimaKeyStore provider
,W/ResourcesManager( 6523): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6523): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6523): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6523): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_10117/pid_4792/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10058/pid_5985/cgroup.procs: No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/BadgeProvider( 6149): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/BadgeProvider( 6149): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 6149): sendNotify, [notify] : null
D/BadgeProvider( 6149): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6149): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 6149): update, [UpdateCount] : 1
,D/Launcher.Model( 1460): reloadBadges entered.
,D/SecurityLogAgent( 5569): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5569): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5569): StateMachine : Current State = 1
D/SecurityLogAgent( 5569): StateMachine : Changed Current State = 1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 1883): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1883): num queued entries: 0
,I/iu.UploadsManager( 1883): num updated entries: 0
,I/iu.SyncManager( 1883): NEXT; no task
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1883): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 5885): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5885): [SystemStateMoniter] Current Time : 401028
I/Babel   ( 3672): connection state changed from CONNECTED to DISCONNECTED
,E/SPPClientService( 5885): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6548): MountEmulatedStorage()
,E/Zygote  ( 6548): v2
I/libpersona( 6548): KNOX_SDCARD checking this for 10110
I/SELinux ( 6548): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6548): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6548 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6548): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Killing 6020:com.android.mms/u0a41 (adj 15): empty #31
,E/SELinux ( 6548): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/TimaKeyStoreProvider( 6548): TimaSignature is unavailable
,D/ActivityThread( 6548): Added TimaKeyStore provider
,E/SPPClientService( 5885): [[SystemStateMonitorService]] No Active Internet
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/CountryDetector( 1015): No listener is left
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6548): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6548): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6548):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6548):   adb logcat -s GAv4
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6548): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6548): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 6548): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6548): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6548): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6548): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup( 1015): failed to open /acct/uid_10041/pid_6020/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1015): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6548): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6548): Time to load native libraries: 1 ms (timestamps 1494-1495)
I/LibraryLoader( 6548): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6548): Binding Chromium to main looper Looper (main, tid 1) {7f0e108}
,I/LibraryLoader( 6548): Expected native library version number "",actual native library version number ""
,I/chromium( 6548): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6548): Initializing chromium process, singleProcess=true
,W/art     ( 6548): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6548): ApplicationContext is null in ApplicationStatus
,W/chromium( 6548): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6548): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6548): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6548): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6548): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6548): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6548): Local Branch: 
I/Adreno-EGL( 6548): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6548): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6548):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6548): Requires BLUETOOTH permission
,I/NSApplication( 6548): Starting up...
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6604): MountEmulatedStorage()
,E/Zygote  ( 6604): v2
I/libpersona( 6604): KNOX_SDCARD checking this for 10077
I/libpersona( 6604): KNOX_SDCARD not a persona
,I/SELinux ( 6604): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6604): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6604 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6604): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 6039:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,D/TimaKeyStoreProvider( 6604): TimaSignature is unavailable
,D/ActivityThread( 6604): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10081/pid_6039/cgroup.procs: No such file or directory
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6622): MountEmulatedStorage()
,E/Zygote  ( 6622): v2
I/libpersona( 6622): KNOX_SDCARD checking this for 10117
I/libpersona( 6622): KNOX_SDCARD not a persona
,I/SELinux ( 6622): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6622 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 6070:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,I/SELinux ( 6622): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6622): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6622): TimaSignature is unavailable
,D/ActivityThread( 6622): Added TimaKeyStore provider
,W/ResourcesManager( 6622): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_10153/pid_6070/cgroup.procs: No such file or directory
,I/ActivityManager( 1015): Killing 6086:com.qualcomm.timeservice/1000 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3355): Starting #11
,I/Hs20UtilService( 3355): Message received 5011
,D/SecurityLogAgent( 5569): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5569): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5569): StateMachine : Current State = 1
D/SecurityLogAgent( 5569): StateMachine : Changed Current State = 1
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_6086/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10011
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 13
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1015): waitForAlarm result :4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 14
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 390s ago
,I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=42179)
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/ConnectivityService( 1015): Failed to find a new network - expiring NetTransition Wakelock
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 15
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/bootchecker(  315): bootchecker wake up!!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 16
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1015): [PWL] Off : 455s ago,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 17
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 18
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 525s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/Atfwd_Daemon(  318): Stop the daemon....,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 19
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1015): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 20
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 21
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1015): [PWL] Off : 600s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 22
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 23
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 680s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 24
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged,
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 25
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 26
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1015): waitForAlarm result :8
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
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 765s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 27
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 28
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 29
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 856s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,E/SMD     (  288): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1015): !@Sync 30
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 31
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 32
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 951s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 33
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 34
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 35
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 36
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 1051s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 37
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 38
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 39
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 1156s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1015): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1015): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1015): Updating Usage Statistics in DB @ 1449749734879
,I/NetworkDataUsageDb( 1015): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1015): ::isTableExists: Table exists 
,I/ApplicationUsage( 1015): Done Updating Usage Statistics in DB @ 1449749734919
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 40
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 41
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 42
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 43
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 1266s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): stay LED for fully charged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 44
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 45
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 46
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 47,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 1381s ago
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 48
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 49
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 50
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged,
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 51
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 1501s ago
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 52
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 53
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 54
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 55
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/PowerManagerService( 1015): [PWL] Off : 1626s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 56
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 57
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 58
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 59
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,I/art     ( 1015): Background partial concurrent mark sweep GC freed 40347(6MB) AllocSpace objects, 338(5MB) LOS objects, 33% free, 23MB/35MB, paused 2.411ms total 180.316ms
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 1756s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/Watchdog( 1015): !@Sync 60
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 61
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1015): !@Sync 62,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 63
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1397): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1397): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 64
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 1891s ago
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 65
,TIME-OUT KILL (timeout was 1800000ms),D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/AndroidRuntime( 7279): 
D/AndroidRuntime( 7279): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7279): CheckJNI is OFF
D/AndroidRuntime( 7279): readGMSProperty: start
D/AndroidRuntime( 7279): readGMSProperty: already setted!!
D/AndroidRuntime( 7279): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7279): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7279): readGMSProperty: end
D/AndroidRuntime( 7279): addProductProperty: start
E/AffinityControl( 7279): AffinityControl: registerfunction enter
D/AndroidRuntime( 7279): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1015): START PACKAGE DELETE: observer{1013566854}
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1015): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1015): Killing 5416:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
I/ActivityManager( 1015): Killing 6201:com.google.android.gms.wearable/u0a11 (adj 15): empty for 1800s
I/ActivityManager( 1015): Killing 5995:com.android.calendar/u0a131 (adj 15): empty for 1800s
I/ActivityManager( 1015): Killing 6137:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty for 1800s
I/ActivityManager( 1015): Killing 6168:com.wsomacp/u0a23 (adj 15): empty for 1800s
I/ActivityManager( 1015): Killing 6115:com.sec.esdk.elm/u0a90 (adj 15): empty for 1801s
I/ActivityManager( 1015): Killing 6050:com.android.providers.calendar/u0a37 (adj 15): empty for 1801s
I/ActivityManager( 1015): Killing 2702:com.samsung.android.providers.context/u0a2 (adj 15): SPC_empty #31
I/ActivityManager( 1015):   Force finishing activity ActivityRecord{2ee626f5 u0 com.test.thalitest/.MainActivity t20}
I/ProcessStatsService( 1015): Prepared write state in 21ms
D/InputDispatcher( 1015): Focus left window: 5416
I/SurfaceFlinger(  257): id=12 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=12 Removed NainActivit (-2/8)
D/InputDispatcher( 1015): Focused application released
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/GpsStatusListenerHelper( 1015): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@314f8647
W/PackageSettings( 1015): Skipping PackageSetting{1757f0a7 com.example.hello/10345} due to missing metadata
W/ActivityManager( 1015): Scheduling restart of crashed service com.samsung.android.providers.context/.ContextService in 3878480ms
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
I/art     ( 3614): Explicit concurrent mark sweep GC freed 3145(188KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 942us total 36.717ms
E/SamsungIME( 1791): mOCRHelper is null
W/GeofencerStateMachine( 1654): Ignoring removeGeofence because network location is disabled.
W/ResourcesManager( 1433): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/KLMS-2.5.123: ( 3376): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 13:28:08 GMT+01:00 2015
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3376): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1015): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1015): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1015): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7293): MountEmulatedStorage()
I/libpersona( 7293): KNOX_SDCARD checking this for 10090
E/Zygote  ( 7293): v2
I/libpersona( 7293): KNOX_SDCARD not a persona
I/SELinux ( 7293): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7293 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 7293): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7293): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3376): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3376): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/TimaKeyStoreProvider( 7293): TimaSignature is unavailable
D/ActivityThread( 7293): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3376): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/RegisteredServicesCache( 1420): empty dynamic service
I/art     ( 1015): Explicit concurrent mark sweep GC freed 21263(2MB) AllocSpace objects, 74(1284KB) LOS objects, 33% free, 23MB/35MB, paused 2.906ms total 191.424ms
I/art     ( 1015): WaitForGcToComplete blocked for 176.836ms for cause Explicit
I/KLMS-2.5.123: ( 3376): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3376): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3376): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3376): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/elm:15121( 7293): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 7293): ELMEngine.ELMEngine( context ).
D/elm:15121( 7293): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
D/elm:15121( 7293): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 7293): ElmAgentService : onCreate()
D/elm:15121( 7293): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 7293): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 7293): MDMBridge.getInstance()
D/elm:15121( 7293): MDMBridge.getAllLicenseInfoFromSDK()
D/RCPManagerService( 1015): PackageReceiver onReceive()
D/elm:15121( 7293): MDMBridge.getAllLicenseInfoFromSDK()
I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:15121( 7293): ElmAgentService : onDestroy().
I/ActivityManager( 1015): Killing 3231:com.sec.android.pagebuddynotisvc/u0a113 (adj 15): SPC_empty #31
I/KLMS-2.5.123: ( 3376): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3376): KLMSIntentService(): onDestroy()
D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10338
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
D/TaskPersister( 1015): removeObsoleteFile: deleting file=20_task.xml
V/EnterpriseBillingPolicy( 1015): uID is 10338
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
I/PCWCLIENTTRACE_PushUtil( 6421): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6421): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6421): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6421): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7311): MountEmulatedStorage()
E/Zygote  ( 7311): v2
I/libpersona( 7311): KNOX_SDCARD checking this for 10029
I/SELinux ( 7311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 7311): KNOX_SDCARD not a persona
I/SELinux ( 7311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7311 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 7311): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1015): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 1000ms
D/TimaKeyStoreProvider( 7311): TimaSignature is unavailable
D/ActivityThread( 7311): Added TimaKeyStore provider
I/art     ( 1015): Explicit concurrent mark sweep GC freed 8855(452KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.413ms total 209.579ms
I/FeatureConfig( 7311): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
I/SA      ( 5156): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5156): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1015): Killing 3475:com.sec.bcservice/1000 (adj 15): SPC_empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1015): delete codoeFile: 
D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
E/Zygote  ( 7328): MountEmulatedStorage()
I/libpersona( 7328): KNOX_SDCARD checking this for 10039
E/Zygote  ( 7328): v2
I/libpersona( 7328): KNOX_SDCARD not a persona
I/AASA_removePackage( 1015): UID=10338 Target=com.test.thalitest
D/PackageManager( 1015): result of delete: 1{1013566854}
I/SELinux ( 7328): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7328 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
W/ResourcesManager( 7311): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/SELinux ( 7328): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7328): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 7311): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/AndroidRuntime( 7279): Shutting down VM
W/ResourcesManager( 7311): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 7328): TimaSignature is unavailable
W/ResourcesManager( 7311): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ActivityThread( 7328): Added TimaKeyStore provider
W/ActivityManager( 1015): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 10829ms
W/ResourcesManager( 7311): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7328): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7328): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7328): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7328): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7328): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7328): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7328): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/GalaxyFinderApplication( 7311): system/finder_cp/cpdata.xml file not found
D/NearbySource( 7328): Nearby Source Create!
D/NearbyContext( 7328): Nearby Context Create!
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
W/art     ( 7279): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ContextImpl( 7328): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
D/SLinkSource( 7328): Samsung link source created
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
D/ContactProvider( 7328): getAllContactInfoList Start
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/PackagesMonitor( 7328): PackagesMonitor onReceive :com.test.thalitest
D/ContactProvider( 7328): getAllContactInfoList End
I/syncContacts( 7328): thread: 1143, sync time = 32
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7350): MountEmulatedStorage()
E/Zygote  ( 7350): v2
I/libpersona( 7350): KNOX_SDCARD checking this for 10041
I/libpersona( 7350): KNOX_SDCARD not a persona
I/SELinux ( 7350): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7350 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 4731:com.android.vending/u0a26 (adj 15): empty #31
I/SELinux ( 7350): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7350): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ProcessStatsService( 1015): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-11-06.bin
W/libprocessgroup( 1015): failed to open /acct/uid_10130/pid_6137/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10023/pid_6168/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10131/pid_5995/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10090/pid_6115/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10002/pid_2702/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10037/pid_6050/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10011/pid_6201/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7350): TimaSignature is unavailable
D/ActivityThread( 7350): Added TimaKeyStore provider
D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1015): no available spell checker services found
W/ResourcesManager( 7350): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7350): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7350): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7350): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7350): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Mms/MmsApp( 7350): [start]    onCreate() consume time = 0.0

```
