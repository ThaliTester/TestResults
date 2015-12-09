#### Test 506502789252e15_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system,
D/SSRM:n  ( 1018): SIOP:: AP = 260
--------- beginning of main
D/AndroidRuntime( 5371): 
D/AndroidRuntime( 5371): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5371): CheckJNI is OFF
D/AndroidRuntime( 5371): readGMSProperty: start
D/AndroidRuntime( 5371): readGMSProperty: already setted!!
D/AndroidRuntime( 5371): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5371): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5371): readGMSProperty: end
D/AndroidRuntime( 5371): addProductProperty: start
E/AffinityControl( 5371): AffinityControl: registerfunction enter
D/AndroidRuntime( 5371): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5383): MountEmulatedStorage()
E/Zygote  ( 5383): v2
I/libpersona( 5383): KNOX_SDCARD checking this for 10338
I/libpersona( 5383): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5383 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1462
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
D/AndroidRuntime( 5371): Shutting down VM
I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 5383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5383): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5383): TimaSignature is unavailable
D/ActivityThread( 5383): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1462): updateVisibility : ActivityRecord{3035f258 token=android.os.BinderProxy@1dec8ae4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1462): onTrimMemory. Level: 20
I/WebViewFactory( 5383): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
W/art     ( 5371): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/LibraryLoader( 5383): Time to load native libraries: 7 ms (timestamps 2526-2533)
I/LibraryLoader( 5383): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5383): Binding Chromium to main looper Looper (main, tid 1) {6eb335e}
I/LibraryLoader( 5383): Expected native library version number "",actual native library version number ""
I/chromium( 5383): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5383): Initializing chromium process, singleProcess=true
W/art     ( 5383): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5383): ApplicationContext is null in ApplicationStatus
W/chromium( 5383): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5383): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5383): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5383): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5383): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5383): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5383): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5383): Local Branch: 
I/Adreno-EGL( 5383): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5383): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5383):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/BluetoothAdapter( 5383): 169936120: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5383): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5383): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5383): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5383): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5383): CordovaWebView is running on device made by: samsung
W/art     ( 5383): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5383): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{1678660c u0 com.test.thalitest/.MainActivity t20}
D/OpenGLRenderer( 5383): Render dirty regions requested: true
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
W/chromium( 5383): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5383): updateVisibility : ActivityRecord{45b9c28 token=android.os.BinderProxy@109c3f1a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 5383): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5383): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1018): Focus entered window: 5383
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5383): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5383): Initialized EGL, version 1.4
D/OpenGLRenderer( 5383): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5383): Enabling debug mode 0
D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
I/ActivityManager( 1018): Displayed Component not be shown by security: +663ms (total +46s575ms)
W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{1678660c u0 com.test.thalitest/.MainActivity t20} time:153044
W/IInputConnectionWrapper( 5383): showStatusIcon on inactive InputConnection
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SamsungIME( 1749): getCurrentCandidateView
I/Timeline( 5383): Timeline: Activity_idle id: android.os.BinderProxy@109c3f1a time:153081
I/SurfaceFlinger(  257): id=11 Removed uhalitest (7/9)
I/SurfaceFlinger(  257): id=11 Removed uhalitest (-2/9)
D/SamsungIME( 1749): Dismiss ExpandCandiate
I/SamsungIME( 1749): getDebugLevel  : 0x4f4c
I/SamsungIME( 1749): getDebugLevel  : 0x4f4c
I/SamsungIME( 1749): KeybaordView init() : load resources
W/BindingManager( 5383): Cannot call determinedVisibility() - never saw a connection for the pid: 5383
I/SamsungIME( 1749): getCurrentKeyboard
I/SamsungIME( 1749): getTextKeyboard
D/SamsungIME( 1749): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 5383): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5383): JniHelper::setJavaVM(0xb8360448), pthread_self() = -1198819232
,D/JX-Cordova( 5383): jxcore cordova android initializing
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 5383): Initializing JXcore engine
W/jxcore-log( 5383): JXcore engine is ready
,W/jxcore-log( 5383): Starting JXcore engine
,E/audit   ( 1800): type=1400 msg=audit(1449683669.837:203): avc:  denied  { ioctl } for  pid=5383 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1800):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1800): type=1300 msg=audit(1449683669.837:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=be880d58 items=0 ppid=324 ppcomm=main pid=5383 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1800): type=1320 msg=audit(1449683669.837:203): 
,W/jxcore-log( 5383): Platform android
W/jxcore-log( 5383): 
W/jxcore-log( 5383): Process ARCH arm
W/jxcore-log( 5383): 
,I/jxcore-log( 5383): JXcore Cordova bridge is ready!
I/jxcore-log( 5383): 
,W/jxcore-log( 5383): JXcore engine is started
I/Choreographer( 5383): Skipped 125 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5383): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5383): Toggling radios to true
I/jxcore-log( 5383): 
,D/BluetoothAdapter( 5383): enable()
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=5383, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 1018): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5383, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
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
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5433): MountEmulatedStorage()
E/Zygote  ( 5433): v2
I/libpersona( 5433): KNOX_SDCARD checking this for 1002
I/libpersona( 5433): KNOX_SDCARD not a persona
,I/SELinux ( 5433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5433 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux ( 5433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
E/SELinux ( 5433): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiService( 1018): setWifiEnabled: true pid=5383, uid=10338
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=5383, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1018): Failed getting userId using ActivityManagerNative
W/WifiService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5383, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1018): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1018): name = wifi_on
,I/WifiService( 1018): disconnect: pid=5383, uid=10338
,E/WifiHW  ( 1018): ##################### set firmware type 0 #####################
I/jxcore-log( 5383): Radios toggled
I/jxcore-log( 5383): 
,D/TimaKeyStoreProvider( 5433): TimaSignature is unavailable
,D/ActivityThread( 5433): Added TimaKeyStore provider
,W/ResourcesManager( 5433): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 5433): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni( 5433): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 5433): Adding GattService
,D/BtSettings.ProfileConfig( 5433): Adding HeadsetService
,D/BtSettings.ProfileConfig( 5433): Adding A2dpService
D/BtSettings.ProfileConfig( 5433): Adding HidService
D/BtSettings.ProfileConfig( 5433): Adding HealthService
D/BtSettings.ProfileConfig( 5433): Adding PanService
,D/BtSettings.ProfileConfig( 5433): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 5433): Adding SapService
D/BtSettings.ProfileConfig( 5433): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 5433): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 5433): Adding SapClientService
,D/BtSettings.ProfileConfig( 5433): Adding HidDevService
I/BtSettings.ProfileConfig( 5433): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hid.HidService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text,
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 5433): make
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/bluedroid( 5433): init
,I/BluetoothAdapterState( 5433): Entering OffState
,I/bte_conf( 5433): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5433): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5433): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5433): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 5433): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 5433): get_profile_interface socket
I/bluedroid( 5433): get_profile_interface map_client
D/BluetoothAdapterService( 5433): checkAddrForIOP: Loading from conf
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/GKI_LINUX( 5433): gki_task_entry task_id=1 [BTIF] starting,
D/BluetoothAdapterProperties( 5433): Address is:08:EC:A9:50:75:41
E/BluetoothServiceJni( 5433): populateRssiValuesNative
I/bluedroid( 5433): getModelRssiValues
E/BluetoothServiceJni( 5433): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5433): modelRssiValuesCallback, low, mid, high = -70,-60,127
D/BluetoothAdapterProperties( 5433): Name is: A3-1
D/SettingsProvider( 1018): name = bluetooth_name
,I/bluedroid( 5433): config_hci_snoop_log
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothManagerService( 1018): Ble is always on enable gatt
,I/BluetoothManagerService( 1018): enableGattForLeMode, doBind called
,E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 1018): uri = 3 selection = isBluetoothEnabled
I/BtGatt.JNI( 5433): classInitNative(L900): classInitNative: Success!
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothAdapterState( 5433): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 5433): Setting state to 11
I/BluetoothAdapterState( 5433): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 5433): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5433): updateAdapterState state is 11
,D/BluetoothAdapterService( 5433): Autoconnection is available 
,D/BluetoothAdapterService( 5433): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 5433): getInstant: null
,D/BluetoothSecureManager( 5433): calling getMethod for getService
D/BluetoothSecureManager( 5433): calling getService
,W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1018): [BT Setting State] State =11
,D/BluetoothSecureManager( 5433): getService return binder: android.os.BinderProxy@8e6860d
,D/BluetoothSecureManagerService( 1018): isSecureModeEnabled
D/BluetoothSecureManagerService( 1018): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 5433): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5433): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5433): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5433): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5433): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5433): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5433): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5433): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5433): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5433): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
D/BluetoothTile( 1175):  getBluetoothState : 11
D/BluetoothTile( 1175): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,I/SamsungIME( 1749): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/BluetoothAdapterService( 5433): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5433): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5433): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine( 5433): make
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1175): onStateChanged: Bluetooth
,I/BluetoothBondStateMachine( 5433): StableState(): Entering Off State
W/BluetoothAdapterService( 5433): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.gatt.GattService
,D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=false
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5433): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 5433): handleDebugAction() action=null
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BtGatt.GattService( 5433): Received start request. Starting profile...
,D/BtGatt.GattService( 5433): start()
W/BluetoothAdapterService( 5433): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BtGatt.GattService( 5433): start()
I/bluedroid( 5433): get_profile_interface gatt
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
,D/BtGatt.AdvertiseManager( 5433): advertise manager created
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/PhoneStatusBar( 1175): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,W/BluetoothAdapterService( 5433): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.hid.HidService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5433): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.hdp.HealthService
,D/BtGatt.GattService( 5433): mStartError = false
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
,D/BluetoothNotiBroadcastReceiver( 1298): onReceive
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5433): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.pan.PanService
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5433): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.map.BluetoothMapService
D/HeadsetService( 5433): Received start request. Starting profile...
D/HeadsetService( 5433): start()
,I/BluetoothHeadsetServiceJni( 5433): classInitNative: succeeds
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/HeadsetStateMachine( 5433): make
,E/HeadsetStateMachine( 5433): # of Max HF connection is 2
,V/BluetoothStatusReceiver( 1175): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1175): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,W/BluetoothAdapterService( 5433): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5433): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,W/BluetoothAdapterService( 5433): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5433): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5433): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5433): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5433): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5433): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5433): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5433): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 5433): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5476 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,E/Zygote  ( 5476): MountEmulatedStorage()
E/Zygote  ( 5476): v2
I/libpersona( 5476): KNOX_SDCARD checking this for 10055
I/libpersona( 5476): KNOX_SDCARD not a persona
,I/SELinux ( 5476): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,I/bluedroid( 5433): get_profile_interface handsfree
,I/SELinux ( 5476): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5476): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DualScoManager( 5433): Instantiating Dual Sco Manager
,I/DualScoManager( 5433): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 5433): createCMTIContentObservers
,D/SettingsProvider( 1018): name = bluetooth_hfp_allowed_bvra
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 5433): Enter Disconnected: -2
,D/HeadsetService( 5433): mStartError = false
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
,D/BluetoothA2dp( 1018): Proxy object connected
,D/A2dpService( 5433): Received start request. Starting profile...
D/A2dpService( 5433): start()
I/BluetoothAvrcpServiceJni( 5433): classInitNative: succeeds
I/bluedroid( 5433): get_profile_interface avrcp
,D/HeadsetStateMachine( 5433): Clear mHeadsetBrsf
D/HeadsetStateMachine( 5433): map size, before remove : 0
D/HeadsetStateMachine( 5433): map size, after remove: 0
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/Tethering( 1018): interfaceAdded wlan0
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,E/Tethering( 1018): No numeric data
D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss,
D/Tethering( 1018): InitialState.processMessage what=4
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,E/Tethering( 1018): No numeric data
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/Tethering( 1018): interfaceAdded p2p0
D/Tethering( 1018): p2p0 is not a tetherable iface, ignoring
,D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceStatusChanged p2p0, false
,D/TimaKeyStoreProvider( 5476): TimaSignature is unavailable
I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/ActivityThread( 5476): Added TimaKeyStore provider
D/HotspotTile( 1175): updateTetherState():false, false
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1175): updateTetherState():false, false
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
E/RemoteController( 5433): Cannot set synchronization mode on an unregistered RemoteController
,I/WifiHW  (  279): wifi_change_fw_path(): fwpath = sta
D/SoftapController(  279): Softap fwReload - Ok
V/NetworkStats( 1018): performPollLocked() took 7ms
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,V/NetworkStats( 1018): performPollLocked() took 2ms
D/NtpTrustedTime( 1018): forceRefresh Fail.
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,D/CommandListener(  279): Setting iface cfg
D/CommandListener(  279): Trying to bring down wlan0
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,I/Avrcp   ( 5433):  Updating now playing list upon AVRCP Start
,D/BluetoothMediaBrowser( 5433):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 5433): classInitNative: succeeds
D/A2dpStateMachine( 5433): make
,D/BluetoothMediaBrowser( 5433): no now playing list
D/BluetoothMediaBrowser( 5433):  getNowPlayingId now playing id : -1
,E/WifiHW  ( 1018): supplicant_name : p2p_supplicant
,I/bluedroid( 5433): get_profile_interface a2dp
,I/GKI_LINUX( 5433): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 5433): warning : media task started media_task_refcnt 1 
D/A2dpService( 5433): mStartError = false
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
,D/A2dpStateMachine( 5433): Enter Disconnected: -2
,D/WifiMonitor( 1018): startMonitoring(wlan0) with mConnected = false
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=false enabledDesc:null
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/STATUSBAR-WifiQuickSettingButton( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1175): Wifi onReceive(2)
,D/STATUSBAR-QSTileView( 1175): onStateChanged: Wi-Fi
,D/HotspotTile( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1175): onReceive : 2, 0
,I/BluetoothHidServiceJni( 5433): classInitNative: succeeds
,D/UserAnalysis.PlaceProvider( 5476): PlaceProvider onCreate()
,D/WifiCredService( 1298): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/HidService( 5433): Received start request. Starting profile...
,D/HidService( 5433): start()
I/bluedroid( 5433): get_profile_interface hidhost
D/HidService( 5433): setHidService(): set to: null
,D/HidService( 5433): mStartError = false
,D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
,E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,I/BluetoothHealthServiceJni( 5433): classInitNative: succeeds
,D/HealthService( 5433): Received start request. Starting profile...
,D/HealthService( 5433): start()
,I/bluedroid( 5433): get_profile_interface health
,D/HealthService( 5433): mStartError = false
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
,D/UserAnalysis.SecureDbManager( 5476): Key for secure DB is newly created
I/BluetoothPanServiceJni( 5433): classInitNative(L105): succeeds
D/UserAnalysis.SecurePlaceDbHelper( 5476): SecurePlaceDbHelper() 
D/UserAnalysis( 5476): Create SecureDbHelper,
,D/BluetoothPan( 1018): BluetoothPAN Proxy object connected
,D/PanService( 5433): Received start request. Starting profile...
,D/PanService( 5433): start()
D/BluetoothPanServiceJni( 5433): initializeNative(L110): pan
,I/bluedroid( 5433): get_profile_interface pan
D/PanService( 5433): mStartError = false
,D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
,I/wpa_supplicant( 5498): [wpa_supplicant_init]: use SECRIL
,I/wpa_supplicant( 5498): Successfully initialized wpa_supplicant
,I/SecureStorage( 5498): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,D/BluetoothMapService( 5433): Received start request. Starting profile...
D/BluetoothMapService( 5433): start()
D/BluetoothMapService( 5433): mStartError = false
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
I/BluetoothSAPServiceJni( 5433): classInitNative(L204): succeeds
,D/SapService( 5433): Received start request. Starting profile...
D/SapService( 5433): start()
D/BluetoothSAPServiceJni( 5433): initializeNative(L209): sap
I/bluedroid( 5433): get_profile_interface sap
D/SapService( 5433): mStartError = false
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
,D/HeadsetStateMachine( 5433): Proxy object connected
D/HeadsetStateMachine( 5433): Try to query the phonestate on bind
,I/SecureStorage( 5498): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/Telecom ( 1414): BluetoothPhoneService: queryPhoneState
I/Telecom ( 1414): BluetoothPhoneService: handleMessage(7) / param 0
I/Telecom ( 1414): BluetoothPhoneService: updateHeadsetWithCallState
I/Telecom ( 1414): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1414): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/SecureStorage(  404): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5498
I/SecureStorage(  404): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 5498): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 5498): ssSupport state is = 1
I/wpa_supplicant( 5498): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5498): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  404): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5498
I/SecureStorage(  404): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
I/Telecom ( 1414): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1414): Proxy not attached to service
,I/Telecom ( 1414): BluetoothPhoneService: Result of Message : true
,D/HeadsetPhoneState( 5433): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 5433): sendDeviceDataStateChanged,
,D/HeadsetPhoneState( 5433): Signal level : previous=0 curr=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/HeadsetService( 5433): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/BluetoothA2dp( 5433): Proxy object connected
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/BluetoothAdapterService( 5433): Bluetooth A2dp source service connected
D/HeadsetStateMachine( 5433): Disconnected process message: 11
D/HeadsetStateMachine( 5433): Disconnected process message: 18
,D/HeadsetStateMachine( 5433): Disconnected process message: 10
D/HeadsetPhoneState( 5433): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5433): Disconnected process message: 11
E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 5502): MountEmulatedStorage()
,E/Zygote  ( 5502): v2
,I/libpersona( 5502): KNOX_SDCARD checking this for 10141
I/libpersona( 5502): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5502 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 5502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/IntelligenceServiceApplication( 5476): onCreate()
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,I/SELinux ( 5502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5502): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/ActivityManager( 1018): Killing 4838:com.wssyncmldm/1000 (adj 15): empty #31
,D/IntelligenceServiceApplication( 5476): no applications having user consent for prediction
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,V/PlaceDetection v1.0.19 ( 5476): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 5476): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
,D/TimaKeyStoreProvider( 5502): TimaSignature is unavailable
,D/ActivityThread( 5502): Added TimaKeyStore provider
,W/ResourcesManager( 5502): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 5502): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5502): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5502): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4838/cgroup.procs: No such file or directory,
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,I/SecureStorage(  404): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 5498): [INFO]: SPID(0x00000001)Processing data has been completed
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/wpa_supplicant( 5498): Ctrl_iface: loading cred from phone,
I/SecureStorage( 5498): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,I/SecureStorage( 5498): [INFO]: SPID(0x00000001)This device supports Secure Storage
,I/SecureStorage(  404): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5498
I/SecureStorage(  404): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C,
I/SecureStorage( 5498): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5498): ssSupport state is = 1
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/wpa_supplicant( 5498): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 5498): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5498): SIM READ ERROR
I/wpa_supplicant( 5498): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5498): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5498): SIM READ ERROR
I/wpa_supplicant( 5498): Blacklist: Clear (all) 
,I/wpa_supplicant( 5498): wpa_default_ap_write_once
I/wpa_supplicant( 5498): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5498): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5498): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 5498): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5498): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 5498): rfkill: Cannot open RFKILL control device
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,V/HeadsetService( 5433): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5433): Disconnected process message: 10
,D/AuthorizationBluetoothService( 1686): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 5498): wlan0: Setting scan request: 0 sec 100000 usec
,D/BluetoothAdapterState( 5433): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5433): enable
,I/ActivityManager( 1018): Killing 4859:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/bt_hci_bdroid( 5433): init
,I/GKI_LINUX( 5433): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 5433): bt-vendor : init
,I/bt_vendor( 5433): bt-vendor : get_bt_soc_type
E/bt_vendor( 5433): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 5433): init: Local BD Address : 41:75:50:a9:ec:08
D/bt_userial_mct( 5433): userial_init
,I/bt_vendor( 5433): bt-vendor : BT_VND_OP_POWER_CTRL: Off
,I/bt_vendor( 5433): Starting hciattach daemon
I/bt_vendor( 5433): try to set false
,I/bt_vendor( 5433): bt-vendor : BT_VND_OP_POWER_CTRL: On
,I/bt_vendor( 5433): Starting hciattach daemon
I/bt_vendor( 5433): try to set true
,I/qcom-bluetooth( 5530): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId,
I/Hs20UtilService( 3423): Starting #2
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/Hs20UtilService( 3423): Message received 5011
,E/Zygote  ( 5535): MountEmulatedStorage(),
E/Zygote  ( 5535): v2
I/libpersona( 5535): KNOX_SDCARD checking this for 1000,
,I/SELinux ( 5535): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5535): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5535 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5535): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5535): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/qcom-bluetooth( 5542): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5544): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 5549): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5550): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/qcom-bluetooth( 5551): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/qcom-bluetooth( 5552): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_4859/cgroup.procs: No such file or directory
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 5535): TimaSignature is unavailable
,D/ActivityThread( 5535): Added TimaKeyStore provider
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 40366(2MB) AllocSpace objects, 30(480KB) LOS objects, 33% free, 23MB/35MB, paused 2.616ms total 218.776ms
,I/wpa_supplicant( 5498): wlan0: State: DISCONNECTED -> DISCONNECTED,
I/SecureStorage( 5498): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,D/BadgeProvider( 5124): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/SecureStorage( 5498): [INFO]: SPID(0x00000001)This device supports Secure Storage
,I/SecureStorage(  404): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5498
I/SecureStorage(  404): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5498): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5498): ssSupport state is = 1
,D/BadgeProvider( 5124): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5124): sendNotify, [notify] : null
D/BadgeProvider( 5124): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5124): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5124): update, [UpdateCount] : 1
,D/Launcher.Model( 1462): reloadBadges entered.
,D/SecurityLogAgent( 5535): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5535): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5535): StateMachine : Current State = 1
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/SMD     (  303): DCD OFF,
I/wpa_supplicant( 5498): Ctrl_iface: loading cred from phone
,I/SecureStorage( 5498): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,D/SecurityLogAgent( 5535): StateMachine : Changed Current State = 1
,I/ActivityManager( 1018): Killing 3899:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/SecureStorage( 5498): [INFO]: SPID(0x00000001)This device supports Secure Storage
,I/SecureStorage(  404): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5498
I/SecureStorage(  404): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,I/SecureStorage( 5498): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5498): ssSupport state is = 1
I/wpa_supplicant( 5498): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 5498): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5498): SIM READ ERROR
I/wpa_supplicant( 5498): wpa_default_ap_write_once
I/wpa_supplicant( 5498): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5498): rfkill: Cannot open RFKILL control device
,D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1018): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1018): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1018): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
,I/wpa_supplicant( 5498): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 5498): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_3899/cgroup.procs: No such file or directory
,I/wpa_supplicant( 5498): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 5498): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5498): Skip scan - bUseNetwork false,
,E/WifiStateMachine( 1018): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 5498): HOTSPOT20_ENABLE called
I/wpa_supplicant( 5498): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5498): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5498): SIM READ ERROR
I/wpa_supplicant( 5498): Blacklist: Clear (all) 
,I/wpa_supplicant( 5498): wlan0: Setting scan request: 0 sec 0 usec,
,I/qcom-bluetooth( 5566): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:75:41 ,
,I/wpa_supplicant( 5498): Skip scan - bUseNetwork false,
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null,
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/HotspotTile( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1175): Wifi onReceive(3)
D/STATUSBAR-QSTileView( 1175): onStateChanged: Wi-Fi
,D/HotspotTile( 1175): onReceive : 3, 0
I/qcom-bluetooth( 5567): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/WifiConfigStore( 1018): Loading config and enabling all networks 
,D/WifiCredService( 1298): Action received :android.net.wifi.WIFI_STATE_CHANGED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3423): Starting #3
,D/SecurityLogAgent( 5535): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5535): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5535): StateMachine : Current State = 1
D/SecurityLogAgent( 5535): StateMachine : Changed Current State = 1
,I/Hs20UtilService( 3423): Message received 5011
,E/WifiConfigStore( 1018): Not a HS20
,E/WifiConfigStore( 1018): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [65]
,D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 5498): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5498): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 5498): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5498): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5498): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 5498): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5498): First Scan Start
I/wpa_supplicant( 5498): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-wlan0( 1018): Setting external_sim to 1
,D/WifiStateMachine( 1018): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1018): startHal
E/wifi    ( 1018): getStaticLongField sWifiHalHandle 0x9d88c88c
I/WifiNative-HAL( 1018): Could not start hal
,W/Settings( 3701): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): P2pDisabledState{ what=131203 }
,E/WifiStateMachine( 1018): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,D/WifiScanningService( 1018): SCAN_AVAILABLE : 3
,D/WifiScanningService( 1018): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  279): Setting iface cfg
D/CommandListener(  279): Trying to bring up p2p0
I/WifiNative-HAL( 1018): startHal
,D/RttService( 1018): SCAN_AVAILABLE : 3
D/RttService( 1018): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,E/wifi    ( 1018): getStaticLongField sWifiHalHandle 0x9e5b49bc
E/WifiStateMachine( 1018): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1018): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1018): invaild command id : 215
,I/WifiNative-HAL( 1018): Could not start hal
E/WifiScanningService( 1018): could not start HAL
D/WifiMonitor( 1018): startMonitoring(p2p0) with mConnected = true
,E/WifiStateMachine( 1018): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1018): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1018): invaild command id : 215
,D/WifiP2pService( 1018): P2pEnablingState
,I/wpa_supplicant( 5498): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiP2pService( 1018): P2pEnablingState{ what=147457 }
I/wpa_supplicant( 5498): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
D/WifiP2pService( 1018): P2p socket connection successful
,D/WifiP2pService( 1018): P2pEnabledState
I/bt_vendor( 5433): bluetooth satus is on
,D/bt_userial_mct( 5433): userial_open(port:0)
I/bt_vendor( 5433): bt-vendor : BT_VND_OP_USERIAL_OPEN
,E/wpa_supplicant( 5498): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine( 1018): Failed to set frequency band 0
,I/bt_vendor( 5433): Done intiailizing UART,
,I/bt_vendor( 5433): Done intiailizing UART
I/bt_userial_mct( 5433): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,I/bt_vendor( 5433): Bluetooth Firmware and transport layer are initialized
D/WifiDisplayController( 1018): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/bt_userial_mct( 5433): Entering userial_read_thread()
,D/WifiP2pService( 1018): sending p2p connection changed broadcast: IDLE
E/WifiStateMachine( 1018): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1018): disconnect
D/WifiDisplayController( 1018): updateConnection
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/SecContentProvider2( 1018): mCursor = null
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService( 1018): create mNetworkAgent
,D/AllShareCastTile( 1175): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1175): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/WifiNative-p2p0( 1018): p2pGetDeviceAddress
D/WifiNative-p2p0( 1018): p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,D/WifiDisplayController( 1018): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,I/        ( 5433): BTE_InitTraceLevels -- TRC_HCI
I/        ( 5433): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5433): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5433): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5433): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5433): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5433): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5433): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5433): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5433): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5433): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5433): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5433): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5433): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5433): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5433): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5433): BTE_InitTraceLevels -- TRC_PROTOCOL
,D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
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
,V/NearbySettings( 1298): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1298): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1298): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/WifiP2pService( 1018): sending p2p persistent groups changed broadcast
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5575 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5575): MountEmulatedStorage()
E/Zygote  ( 5575): v2
I/libpersona( 5575): KNOX_SDCARD checking this for 10064
I/libpersona( 5575): KNOX_SDCARD not a persona
,I/SELinux ( 5575): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5575): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5575): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/WifiP2pService( 1018): InactiveState
,D/WifiP2pService( 1018): InactiveState{ what=143376 }
D/WifiP2pService( 1018): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 5498): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
D/WifiP2pService( 1018): InactiveState{ what=143376 }
E/ConnectivityService( 1018): updateNetworkInfo()
D/WifiP2pService( 1018): P2pEnabledState{ what=143376 }
,D/TimaKeyStoreProvider( 5575): TimaSignature is unavailable
D/ActivityThread( 5575): Added TimaKeyStore provider
,W/ResourcesManager( 5575): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/bt-l2cap( 5433): l2c_link_processs_ble_num_bufs 16
,E/bt-btm  ( 5433): BTM_SecRegister:p_cb_info->p_le_callback == 0xa43e2ead 
,E/bt-btm  ( 5433): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa43e2ead 
,D/BluetoothAdapterProperties( 5433): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,E/bt-btif ( 5433): BTM_SEC_REG[4]: id 3
,E/bt-btif ( 5433): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties( 5433): Address is:08:EC:A9:50:75:41
,E/BluetoothServiceJni( 5433): populateRssiValuesNative
I/bluedroid( 5433): getModelRssiValues
E/BluetoothServiceJni( 5433): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5433): modelRssiValuesCallback, low, mid, high = -70,-60,127
D/FileShare-Client( 5575): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/BluetoothAdapterProperties( 5433): Name is: A3-1
,D/SettingsProvider( 1018): name = bluetooth_name
,D/FileShare-Client( 5575): ClientBroadcastReceiver.onReceive - disconnected
D/BluetoothAdapterProperties( 5433): Scan Mode:20
,D/BluetoothAdapterProperties( 5433): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5433): LE Address is:C8:D9:53:A0:EA:82
,E/bt-btif ( 5433): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,E/bt-btif ( 5433): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt_mct  ( 5433): hci lib postload completed,
E/bt-btif ( 5433): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 5433): btif_sock_init: !vhci_init
,D/IOP_DB_BT( 5433): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 5433): db_open: db_open : handle 3027914768l, read 13894 bytes onto local cache
,D/IOP_DB_BT( 5433): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT( 5433): db_query: result 1
I/        ( 5433): iop_db_open: iop_db_open status 0
,D/bte_conf( 5433): Device ID record 1 : primary
,D/bte_conf( 5433):   vendorId            = 0075
D/bte_conf( 5433):   vendorIdSource      = 0001
,D/bte_conf( 5433):   product             = 0100
D/bte_conf( 5433):   version             = 0200
D/bte_conf( 5433):   clientExecutableURL = 
D/bte_conf( 5433):   serviceDescription  = 
D/bte_conf( 5433):   documentationURL    = 
D/bte_conf( 5433): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 5433): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 5433): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 5433): ScanMode =  20
D/BluetoothAdapterProperties( 5433): State =  11
,D/SecContentProvider( 1018): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 5433): Setting state to 12
,I/BluetoothAdapterState( 5433): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties( 5433): Scan Mode:21
D/BluetoothAdapterProperties( 5433): Discoverable Timeout:120
,D/SettingsProvider( 1018): name = bluetooth_a2dp_sink_mode
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 5433): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5433): updateAdapterState state is 12
,D/FileShare-Client( 5575): Outbound.stopDelayTimer - 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,E/Zygote  ( 5593): MountEmulatedStorage(),
E/Zygote  ( 5593): v2
I/libpersona( 5593): KNOX_SDCARD checking this for 10065,
I/libpersona( 5593): KNOX_SDCARD not a persona
,I/SELinux ( 5593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5593 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/SELinux ( 5593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5593): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 4542:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,D/BluetoothAdapterService( 5433): Autoconnection is available 
,D/BluetoothAdapterService( 5433): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5433): starting service from this receiver
,D/BluetoothA2dp( 1018): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1018): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1018): onBluetoothStateChange: Bluetooth is on
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapter( 1414): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1414): onBluetoothStateChange: Bluetooth is on
,I/BluetoothAdapterState( 5433): Entering On State from state = 11
D/BluetoothA2dp( 5433): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1175): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1175): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 5383): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5383): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1424): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1424): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 5433): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5433): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1663): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1663): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1440): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1440): onBluetoothStateChange: Bluetooth is on
,W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1018): [BT Setting State] State =12
I/InputMethodManagerService( 1018): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/BluetoothPbapService( 5433): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,I/art     (  324): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 32.419ms
,D/BluetoothHeadset( 1414): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2c34c122, true
,D/BluetoothHeadset( 1414): registerMessageListener
,I/SamsungIME( 1749): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 1175):  onBluetoothStateChange:
,D/HeadsetService( 5433): registerMessageListener
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,D/HeadsetService( 5433): registerMessageListener
D/HeadsetStateMachine( 5433): Disconnected process message: 70
D/HeadsetStateMachine( 5433): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@85d2ea5
,I/Telecom ( 1414): BluetoothPhoneService: handleMessage(7) / param null
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 17.451ms
,D/TimaKeyStoreProvider( 5593): TimaSignature is unavailable
D/ActivityThread( 5593): Added TimaKeyStore provider
I/Telecom ( 1414): BluetoothPhoneService: updateHeadsetWithCallState
,I/BluetoothPbapService( 5433): Handler(): got msg=1
,D/SecContentProvider( 1018): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1175): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1175):  getBluetoothState : 12
,I/Telecom ( 1414): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1414): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1414): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/HeadsetStateMachine( 5433): Disconnected process message: 9
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 16.826ms
D/HeadsetStateMachine( 5433): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1175): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,D/audio_hw_primary(  290): adev_set_parameters: enter: A2dpSuspended=false
,V/BluetoothPbapService( 5433): PBAP Service initSocket try: 0
,V/voice   (  290): voice_set_parameters: enter: A2dpSuspended=false
,V/voice   (  290): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  290): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  290): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  290): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  290): adev_set_parameters: exit
E/HeadsetStateMachine( 5433): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,D/BluetoothMapMasInstance( 5433): set MAP SDP message type : 1
,W/BluetoothAdapter( 5433): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5433): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 5433): bindListen(), new LocalSocket 
D/BluetoothSocket( 5433): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5433): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@dc21c46
D/BluetoothSocket( 5433): channel: 19
D/BluetoothPbapService( 5433): PBAP Socket is BluetoothServerSocket
,W/BluetoothAdapter( 5433): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5433): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 5433): bindListen(), new LocalSocket 
D/BluetoothSocket( 5433): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5433): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24678e07
,D/BluetoothSocket( 5433): channel: 5
,D/FileShare-Server( 5593): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1018): Killing 4970:com.samsung.helphub/1000 (adj 15): empty #31
,W/ContextImpl( 1298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/LocalBluetoothProfileManager( 1298): Adding local A2DP profile
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1298): Adding local HEADSET profile
,E/BluetoothHeadset( 1298): BTStateChangeCB is registed
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 1298): BluetoothHeadset service is binded
,D/BluetoothMap( 1298): Create BluetoothMap proxy object
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_4542/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ContextImpl( 1298): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/Bluetoothsap( 1298): bindService called to Bluetooth SAP Service
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1298): PANU : true
W/LocalBluetoothProfileManager( 1298): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1298): LocalBluetoothProfileManager construction complete
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4970/cgroup.procs: No such file or directory
,D/DockEventReceiver( 1298): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1298): onReceive
,D/BluetoothA2dp( 1298): Proxy object connected
D/A2dpProfile( 1298): Bluetooth service connected
,V/BluetoothStatusReceiver( 1175): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1175): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/HeadsetProfile( 1298): Bluetooth service connected
,D/BluetoothMap( 1298): Proxy object connected
D/MapProfile( 1298): Bluetooth service connected
D/BluetoothMap( 1298): getConnectedDevices()
,D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
,D/BtConfig.SecureMode( 5433): isSecureModeOn:false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothPbap( 1298): Proxy object connected
D/PbapServerProfile( 1298): Bluetooth service connected
D/Bluetoothsap( 1298): BluetoothSAP Proxy object connected
D/SapProfile( 1298): Bluetooth service connected
D/Bluetoothsap( 1298): getConnectedDevices()
,D/AuthorizationBluetoothService( 1686): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothInputDevice( 1298): Proxy object connected
,D/HidProfile( 1298): Bluetooth service connected
,D/BluetoothPan( 1298): BluetoothPAN Proxy object connected
,D/PanProfile( 1298): Bluetooth service connected
,D/SecContentProvider( 1018): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/BluetoothAdapter( 5433): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5433): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
D/BluetoothSocket( 5433): bindListen(), new LocalSocket 
D/BluetoothSocket( 5433): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5433): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f20a259
,D/BluetoothSocket( 5433): channel: 12
I/BtOppRfcommListener( 5433): Accept thread started.
,I/wpa_supplicant( 5498): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 5498): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5498): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5498): Trying to associate with  'G700'
I/wpa_supplicant( 5498): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 5498): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1018): didn't find BSSID Trying to associate with SSID 'NG700'
I/WifiNative-HAL( 1018): startHal
E/wifi    ( 1018): getStaticLongField sWifiHalHandle 0x9d88c8ac
I/WifiNative-HAL( 1018): Could not start hal
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb73057c8
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1221568376)
E/wpa_supplicant( 5498): Cmd 35605 not handled
I/wpa_supplicant( 5498): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 5498): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 5498): Associated with C0.AA.48
I/wpa_supplicant( 5498): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5498): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5498): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 5498): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 5498): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5498): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 5498): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 5498): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5498): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5498): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 5498): Blacklist: Clear (temp) 
I/wpa_supplicant( 5498): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0( 1018): callSECApiVoid - ID [50]
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
E/Tethering( 1018): No numeric data
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1018): clearTetheredNotification()
D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NtpTrustedTime( 1018): forceRefresh() from cache miss
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1175): updateTetherState():false, false
E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/NtpTrustedTime( 1018): forceRefresh Fail.
V/NetworkStats( 1018): performPollLocked(flags=0x1)
I/Hs20UtilService( 3423): Starting #4
I/Hs20UtilService( 3423): Message received 5007
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
V/NetworkStats( 1018): performPollLocked() took 4ms
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1221568376) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb73057c8
D/NtpTrustedTime( 1018): forceRefresh() from cache miss
D/NtpTrustedTime( 1018): forceRefresh Fail.
D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/NearbySettings( 1298): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1298): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1298): MountReceiver.mPrefHandler - 7002
D/CommandListener(  279): Setting iface cfg
E/WifiStateMachine( 1018): Start Dhcp Watchdog 1
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
E/WifiNative-wlan0( 1018): do suspend false
D/WifiP2pService( 1018): InactiveState{ what=143375 }
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/dhcpcd  ( 5621): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5621): version 5.5.6 starting,
,E/dhcpcd  ( 5621): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5621): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 5621): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5621): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5621): bssid match
,I/dhcpcd  ( 5621): wlan0: rebinding lease of 192.168.1.132
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/dhcpcd  ( 5621): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,I/dhcpcd  ( 5621): wlan0: leased 192.168.1.132 for 86400 seconds
,E/SMD     (  303): DCD OFF
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1018): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1018): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1018): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 1018): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService( 1018): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService( 1018): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,E/ConnectivityService( 1018): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1018): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 1018): LTETest block dns file not exists
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,I/Hs20UtilService( 3423): Starting #5
,I/Hs20UtilService( 3423): Message received 5007
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1298): MountReceiver.onReceive - Keep current state
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1018): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
,E/WifiStateMachine( 1018): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 502]
,E/WifiStateMachine( 1018): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/ConnectivityService( 1018):    accepting network in place of null
,D/ConnectivityService( 1018): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1440): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1440): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 1018): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true,
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/WifiTrafficPoller( 1018): mBoosterFLAG : 0
I/WifiTrafficPoller( 1018): current booster mode : FullMode
D/WifiNative-wlan0( 1018): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1018): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1018): (HTTPLog)-Static: isShipBuild true
I/System.out( 1018): (HTTPLog)-Thread-171-594138706: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 1000
,D/ConnectivityService( 1018): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
V/NetworkStats( 1018): updateIfacesLocked()
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 1000
,V/NetworkStats( 1018): performPollLocked() took 4ms
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3423): Starting #6
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
I/Hs20UtilService( 3423): Message received 5007
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1298): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1298): MountReceiver.onReceive - Keep current state
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3423): Starting #7
D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1298): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 3423): Message received 5007
D/WifiStateMachine( 1018): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1018): mCursor = null
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,D/SRIB_DCS( 1175): log_dcs ThreadedRenderer::initialize entered! 
,D/NtpTrustedTime( 1018): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449683675834 mCachedNtpElapsedRealtime : 160836 mCachedNtpCertainty : 15
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:54:35 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449683675911], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449683675893]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290,
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/AlarmManagerService( 1018): Setting time of day to sec=1449683676
D/AlarmManagerService( 1018): Trying to open a file
,I/PCWCLIENTTRACE_PushUtil( 5003): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5003): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5003): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5003): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
D/AlarmManagerService( 1018): File Open Success
,D/AlarmManagerService( 1018): File Close Success
I/AlarmManagerService( 1018): DRM_TIME_PATH CHMOD 666 for resetState done 
W/AlarmManagerService( 1018): Unable to set rtc to 1449683676: Invalid argument
V/AlarmManager( 1018): waitForAlarm result :65536
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5662): MountEmulatedStorage()
,E/Zygote  ( 5662): v2
I/libpersona( 5662): KNOX_SDCARD checking this for 10108
I/libpersona( 5662): KNOX_SDCARD not a persona
,I/SELinux ( 5662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5662 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5662): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/AlarmManager( 1018): No more alarm at this time.nowELAPSED=161265 batch.start=164004
,D/WifiStateMachine( 1018): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,I/DowntimeConditions( 1018): android.intent.action.TIME_SET ignored because schedule turned off.
,D/TimaKeyStoreProvider( 5662): TimaSignature is unavailable
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_SET
,D/ActivityThread( 5662): Added TimaKeyStore provider
,W/Settings( 1018): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DrmEventService( 1018):  no response from SecureClock 
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SettingsProvider( 1018): name = lockscreen_zoom_panning_effect
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/KeyguardEffectViewUtil( 1175): isStrongPowerSavingMode() :false
,E/Zygote  ( 5680): MountEmulatedStorage(),
E/Zygote  ( 5680): v2
I/libpersona( 5680): KNOX_SDCARD checking this for 10071
I/libpersona( 5680): KNOX_SDCARD not a persona
,I/SELinux ( 5680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/KeyguardEffectViewController( 1175): isPreloadedWallpaper=true
I/GeometricMosaic_Keyguard( 1175): update
,E/SELinux ( 5680): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=5680 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardEffectViewUtil( 1175): getCurrentWallpaper() mWallpaperPath :null
,D/TimaKeyStoreProvider( 5680): TimaSignature is unavailable
,D/ActivityThread( 5680): Added TimaKeyStore provider
,I/KeyguardEffectViewUtil( 1175): set current wallpaper info,
D/SettingsProvider( 1018): name = keyguard_current_wallpaper_type
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/SettingsProvider( 1018): name = keyguard_current_wallpaper_file_path
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/MusicStore( 5662): Database version: 120
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/SettingsProvider( 1018): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,E/GpsLocationProvider( 1018): No APN found to select.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5662): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TEST    ( 1175): run!!!
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
I/GeometricMosaic_Renderer( 1175): setBackgroundBitmap
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text,
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,W/ContextImpl( 5662): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/KeyguardEffectViewController( 1175): isPreloadedWallpaper=true
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5662): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 5662): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5662): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1018): SIOP:: AP = 310
,V/JNIHelp ( 5662): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Auth.Api.Credentials( 1941): [CredentialSyncAdapter] Unknown sync event.
,W/DriveInitializer( 1941): Background init thread started
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/GAV2    ( 5680): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksApp( 5680): Created application version: 3.6.9 (30609)
,W/DriveInitializer( 1941): Awaiting to be initialized
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1941): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,W/ActivityThread( 5662): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5662): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@cc64cd7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5662): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5662): GMSCore installation verified
,I/ConfigStore( 5662): Config Database version: 1
,I/art     ( 1686): Explicit concurrent mark sweep GC freed 15038(841KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 988us total 44.151ms,
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
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/BooksSync( 5680): Starting books sync for 61035162, extras: ade
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/DriveInitializer( 1941): Background init thread ended
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 70
,I/MediaRouter( 5662): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5662): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5662): type=WIFI subType= reason=null isConnected=true
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 62781(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 6.890ms total 181.027ms
,I/art     ( 1018): WaitForGcToComplete blocked for 15.382ms for cause HeapTrim
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 5662): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5735): MountEmulatedStorage()
,E/Zygote  ( 5735): v2
I/libpersona( 5735): KNOX_SDCARD checking this for 10001
I/libpersona( 5735): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5735 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5735): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SELinux ( 5735): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 5662): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/TimaKeyStoreProvider( 5735): TimaSignature is unavailable
,D/ActivityThread( 5735): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 5662): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 5680): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 5680): GmsCore Version = 7.8.99 (2134222-434)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5758): MountEmulatedStorage()
I/libpersona( 5758): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5758): v2
I/libpersona( 5758): KNOX_SDCARD not a persona
I/SELinux ( 5758): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=5758 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 5758): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Killing 4985:com.google.android.apps.docs/u0a87 (adj 15): empty #31
E/SELinux ( 5758): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5758): TimaSignature is unavailable
,D/ActivityThread( 5758): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 5758): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10087/pid_4985/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1175): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1175): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/KnoxNotification( 1175): ----- inflateViews : modified publicViewLocal -----
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/KnoxNotification( 1175): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1175): PersonaID is invalid or persona doesn't exists. : 0
,E/BooksAccountManager( 5680): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,I/DIAGMON_AGENT( 5758): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
E/BooksSync( 5680): Soft error
E/BooksSync( 5680): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5680): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5680): Sync error
E/BooksSync( 5680): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5680): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 5680): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 22541, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/DIAGMON_AGENT( 5758): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/ActivityManager( 1018): Killing 4940:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/login_manager
I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/login_manager without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/DIAGMON_AGENT( 5758): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 5758): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5758): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 5758): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/Auth.Api.Credentials( 1941): [SyncManager] Error during the sync.
E/Auth.Api.Credentials( 1941): com.google.android.gms.auth.ad: BadAuthentication
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.common.server.s.b(SourceFile:59)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.common.server.s.a(SourceFile:294)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.common.server.s.a(SourceFile:201)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.auth.b.a.a(SourceFile:316)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.auth.api.credentials.be.a.b.b(SourceFile:285)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.auth.api.credentials.sync.c.a(SourceFile:384)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:114)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.auth.api.credentials.sync.a.a(SourceFile:131)
E/Auth.Api.Credentials( 1941): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
E/Auth.Api.Credentials( 1941): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_4940/cgroup.procs: No such file or directory
,D/PicasaService( 4306): start picasa sync
,D/PicasaService( 4306): end picasa sync
,I/DBG_POLICYDM( 5033): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5033): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5033): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5033): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5779): MountEmulatedStorage(),
E/Zygote  ( 5779): v2
I/libpersona( 5779): KNOX_SDCARD checking this for 10008
I/libpersona( 5779): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=5779 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5779): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5779): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5779): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 1686): (10) POSIX Error : 11 SQLite Error : 3850
,D/TimaKeyStoreProvider( 5779): TimaSignature is unavailable
,D/ActivityThread( 5779): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5052:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 4611:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #32
,I/FOTA_Client( 5779): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 5779): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/ActivityManager( 1018): Killing 5076:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3446): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 18:54:38 GMT+01:00 2015
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3446): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3446): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3446): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 5797): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5797 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 5797): v2
I/libpersona( 5797): KNOX_SDCARD checking this for 10031
I/SELinux ( 5797): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5797): KNOX_SDCARD not a persona
I/KLMS-2.5.123: ( 3446): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SELinux ( 5797): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
E/SELinux ( 5797): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3446): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3446): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3446): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3446): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3446): NetworkChangeOperations(): uploadRequestLog().START 
,D/TimaKeyStoreProvider( 5797): TimaSignature is unavailable
,D/ActivityThread( 5797): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3446): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3446): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3446): KLMSIntentService(): onDestroy()
,W/libprocessgroup( 1018): failed to open /acct/uid_10148/pid_5052/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10029/pid_4611/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_5076/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5033): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/dhcpcd  ( 5621): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 5621): wlan0: sendmsg: Cannot assign requested address
,I/DBG_POLICYDM( 5033): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5033): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,I/SA      ( 5086): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5086): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 5086): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/DBG_POLICYDM( 5033): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 5033): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init,
,I/DBG_POLICYDM( 5033): [com.policydm.XDMApplication(246/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_POLICYDM( 5033): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/SA      ( 5086): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5033): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 5086): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5086): [OR] == isSIMCardReady false ==
,I/DBG_POLICYDM( 5033): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5033): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5033): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/SA      ( 5086): [SCU] == networkStateCheck == true
,I/SA      ( 5086): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5086): isChinaCountryCode : false
I/SA      ( 5086): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 5086): [OR] == networkStateCheck true ==
,I/SA      ( 5086): [OR] GetMyCountryZoneTask
,I/SA      ( 5086): [OR] onReceive END
,I/ActivityManager( 1018): Killing 4144:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,I/SA      ( 5086): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1227): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/SMD     (  303): DCD OFF
,D/accuweather( 1573): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5086): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5086): [SSP] query invoked
,I/SA      ( 5086): [TPMU] GetMccFromDB : null
I/SA      ( 5086): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5086): [TPM] isNoProxy(default) : true
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1018): mCursor = null
,D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1573): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1573): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1573): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1573): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,D/accuweather( 1573): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1573): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/File    ( 5086): fail readDirectory() errno=2
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5824): MountEmulatedStorage()
I/libpersona( 5824): KNOX_SDCARD checking this for 10121
E/Zygote  ( 5824): v2
I/libpersona( 5824): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=5824 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 5824): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5824): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/DBG_POLICYDM( 5033): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,E/SELinux ( 5824): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5033): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 5033): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5033): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5033): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/TimaKeyStoreProvider( 5824): TimaSignature is unavailable
,D/ActivityThread( 5824): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5033): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/12/10/14:45:39
,I/DBG_POLICYDM( 5033): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/12/09/18:54:38
,I/DBG_POLICYDM( 5033): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,W/libprocessgroup( 1018): failed to open /acct/uid_10011/pid_4144/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5033): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,W/ResourcesManager( 5824): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5824): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5033): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5033): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,W/ResourcesManager( 5824): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5033): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5033): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
I/DBG_POLICYDM( 5033): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5033): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5033): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5033): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 5033): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/QuickConnect( 5824): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 5824): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,I/QuickConnect( 5824): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 5535): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5535): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5535): StateMachine : Current State = 1
,D/SecurityLogAgent( 5535): StateMachine : Changed Current State = 1
,I/ActivityManager( 1018): Killing 4950:com.android.mms/u0a41 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,I/iu.SyncManager( 1941): SYNC; picasa accounts
,D/NetworkLogImpl( 1941): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1941): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CountryDetector( 1018): No listener is left
,I/iu.UploadsManager( 1941): num queued entries: 0
,I/iu.UploadsManager( 1941): num updated entries: 0
,I/iu.SyncManager( 1941): NEXT; no task
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/btif_config_util( 5433): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_4950/cgroup.procs: No such file or directory
,E/Zygote  ( 5848): MountEmulatedStorage()
,E/Zygote  ( 5848): v2
I/libpersona( 5848): KNOX_SDCARD checking this for 10032
I/libpersona( 5848): KNOX_SDCARD not a persona
,I/SELinux ( 5848): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5848): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5848): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
I/System.out( 3701): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=5848 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/System.out( 3701): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3701): (HTTPLog)-Static: isShipBuild true
I/System.out( 3701): (HTTPLog)-Thread-586-549817196: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3701): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10102
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5848): TimaSignature is unavailable
,D/ActivityThread( 5848): Added TimaKeyStore provider
,I/System.out( 3701): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,I/Babel   ( 3701): connection state changed from DISCONNECTED to CONNECTED
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SPPClientService( 5848): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5848): [PushClientApplication] Push log off : This is Ship build version
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 1941): [AccountUtils] Account not ready
W/Kids    ( 1941): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1941): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1941): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1941): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1941): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1941): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1941): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1941): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1941): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1941): 	at java.lang.Thread.run(Thread.java:818)
,D/SPPClientService( 5848): PushLog.txt file is not deleted.
,D/SPPClientService( 5848): PushLog.txt file is not deleted.
,D/SPPClientService( 5848): ============PushLog. stop!
,E/SPPClientService( 5848): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5848): [SystemStateMoniter] Current Time : 163802
,E/SPPClientService( 5848): [SystemStateMoniter] No Connect : false
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/GCM     ( 1686): Connected
,E/Zygote  ( 5869): MountEmulatedStorage()
,I/libpersona( 5869): KNOX_SDCARD checking this for 10110
E/Zygote  ( 5869): v2
I/libpersona( 5869): KNOX_SDCARD not a persona
I/SELinux ( 5869): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5869): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5869): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5869 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5869): TimaSignature is unavailable
,D/ActivityThread( 5869): Added TimaKeyStore provider
,D/GCM     ( 1686): Message class com.google.f.a.a.p
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
,V/AlarmManager( 1018): waitForAlarm result :4
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5869): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5869): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 5869): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5869):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5869):   adb logcat -s GAv4
,I/SurfaceFlinger(  257): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 164310
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
,D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10049}) (elapsedTime=3490)
,W/GAv4    ( 5869): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 5869): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 5869): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5869): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 5869): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/SA      ( 5086): [RC New] Execute method=[GET] start
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 30250(1413KB) AllocSpace objects, 3(52KB) LOS objects, 33% free, 23MB/35MB, paused 2.628ms total 153.673ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5086): [RC New] Security=[true]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/System.out( 5086): Thread-860(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 5086): Thread-860(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5086): Thread-860(ApacheHTTPLog):isShipBuild true
I/System.out( 5086): Thread-860(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5086): Thread-860(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10036
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4681): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4681): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4681): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ActivityManager( 1018): Killing 5144:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_5144/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 5869): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 5869): Time to load native libraries: 2 ms (timestamps 4802-4804)
,I/LibraryLoader( 5869): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5869): Binding Chromium to main looper Looper (main, tid 1) {3134e2a}
,I/LibraryLoader( 5869): Expected native library version number "",actual native library version number ""
,I/chromium( 5869): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5869): Initializing chromium process, singleProcess=true
,W/art     ( 5869): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5869): ApplicationContext is null in ApplicationStatus
,W/chromium( 5869): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5869): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5869): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5869): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5869): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5869): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5869): Local Branch: 
I/Adreno-EGL( 5869): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5869): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5869):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 5869): Requires BLUETOOTH permission
,I/NSApplication( 5869): Starting up...
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5925): MountEmulatedStorage(),
I/libpersona( 5925): KNOX_SDCARD checking this for 10077
E/Zygote  ( 5925): v2
I/libpersona( 5925): KNOX_SDCARD not a persona
,I/SELinux ( 5925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5925): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5925 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5160:com.wsomacp/u0a23 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5925): TimaSignature is unavailable
,D/ActivityThread( 5925): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10023/pid_5160/cgroup.procs: No such file or directory
,I/SA      ( 5086): [RC New] [v2liruge] api execute + 708
,I/SA      ( 5086): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5086): AsyncTask #1 calls detatch()
,D/WaitQueueForNetworkActivate( 5300): notifyNetworkActivated
,I/SA      ( 5086): [ODM] saveOpenData( GEO_IP, PL )
,W/ContextImpl( 5300): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/SA      ( 5086): [OCP] update openData : PL
,I/SA      ( 5086): [TPMU] getNetworkMcc : 
,I/SA      ( 5086): [SCU] saveMccToPreferece Start
,I/SA      ( 5086): [SCU] RegionMCC : 260
I/SA      ( 5086): [SSP] query invoked
,I/SA      ( 5086): [TPMU] GetMccFromDB : null
,I/SA      ( 5086): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5086): [SCU] saveMccToPreferece End
I/SA      ( 5086): [RC New] executeRequest [v2liruge] end. 880
I/SA      ( 5086): [RC New] Execute end
,I/SA      ( 5086): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5086): [OR] GetMyCountryZoneTask Success
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,I/splitIntent( 1018): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,I/splitIntent( 1018): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/hcjo    ( 5300): AutoUpdateManager:IDLE:execute
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/InitializeManagerStateMachine( 5300): execute::IDLE:EXECUTE,
D/InitializeManagerStateMachine( 5300): exit::IDLE
D/InitializeManagerStateMachine( 5300): entry::NETWORK_CHECK
,E/Zygote  ( 5948): MountEmulatedStorage()
E/Zygote  ( 5948): v2
,I/libpersona( 5948): KNOX_SDCARD checking this for 10058
I/libpersona( 5948): KNOX_SDCARD not a persona
,I/SELinux ( 5948): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5948): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=5948 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/InitializeManagerStateMachine( 5300): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5300): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5300): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5300): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5300): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5300): entry::SUCCESS
,D/hcjo    ( 5300): AutoUpdateManager:INITCHECK:onInitializeSuccess
E/SELinux ( 5948): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     (  324): Explicit concurrent mark sweep GC freed 8680(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 628us total 28.088ms
,D/TimaKeyStoreProvider( 5948): TimaSignature is unavailable
,D/ActivityThread( 5948): Added TimaKeyStore provider
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 17.067ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.300ms
,E/Zygote  ( 5963): MountEmulatedStorage()
E/Zygote  ( 5963): v2
I/libpersona( 5963): KNOX_SDCARD checking this for 10131
I/libpersona( 5963): KNOX_SDCARD not a persona
,I/SELinux ( 5963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5963 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 5963): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/hcjo    ( 5300): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/daemonapp( 1622): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1622): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/FOTA_Client( 5779): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/hcjo    ( 5300): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5300): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/TimaKeyStoreProvider( 5963): TimaSignature is unavailable
,D/ActivityThread( 5963): Added TimaKeyStore provider
,D/daemonapp( 1622): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,I/FOTA_Client( 5779): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/comsamsunglog( 1622): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1622): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1622): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1622): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1622): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/InitializeManagerStateMachine( 5300): exit::SUCCESS
D/InitializeManagerStateMachine( 5300): entry::IDLE
,D/daemonapp( 1622): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1622): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1622): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1622): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/ActivityManager( 1018): Killing 5179:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,E/daemonapp( 1622): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/KLMS-2.5.123: ( 3446): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Wed Dec 09 18:54:40 GMT+01:00 2015
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3446): KLMSAbstractReciever(): onReceive().END.
,I/SA      ( 5086): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/comdaemonstockapp( 1622): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1622): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
W/ResourcesManager( 5963): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.5.123: ( 3446): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3446): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3446): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/KLMS-2.5.123: ( 3446): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.5.123: ( 3446): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.123: ( 3446): StateImplV2(): dateTimeChanged().START : Wed Dec 09 18:54:40 GMT+01:00 2015
,I/ExternalOEMControlProvider( 5948): onCreate
,I/KLMS-2.5.123: ( 3446): StateImplV2(): dateTimeChanged().END
,I/KLMS-2.5.123: ( 3446): KLMSIntentService(): onDestroy()
,D/accuweather( 1573): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1573): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ Time Manager ( 5948): Time Difference not stored. TIME_DIFFERENCE
,E/Zygote  ( 5983): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=5983 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/Zygote  ( 5983): v2
I/libpersona( 5983): KNOX_SDCARD checking this for 10041
I/libpersona( 5983): KNOX_SDCARD not a persona
,I/SELinux ( 5983): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5983): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5983): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1018): failed to open /acct/uid_10048/pid_5179/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5983): TimaSignature is unavailable
,D/ActivityThread( 5983): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5999): MountEmulatedStorage()
,E/Zygote  ( 5999): v2
I/libpersona( 5999): KNOX_SDCARD checking this for 10081,
I/libpersona( 5999): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=5999 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 5999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5999): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/TimaKeyStoreProvider( 5999): TimaSignature is unavailable
D/ActivityThread( 5999): Added TimaKeyStore provider
,W/ResourcesManager( 5983): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5983): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5983): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5983): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5983): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ResourcesManager( 5999): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ResourcesManager( 5999): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
W/ResourcesManager( 5999): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5999): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5999): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6018): MountEmulatedStorage(),
E/Zygote  ( 6018): v2
I/libpersona( 6018): KNOX_SDCARD checking this for 10037
I/libpersona( 6018): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6018 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6018): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 6018): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6018): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SecurityLogAgent( 5535): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5535): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5535): StateMachine : Current State = 1
,D/Mms/MmsApp( 5983): [start]    onCreate() consume time = 0.0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6034): MountEmulatedStorage(),
E/Zygote  ( 6034): v2,
I/libpersona( 6034): KNOX_SDCARD checking this for 10153
I/libpersona( 6034): KNOX_SDCARD not a persona
,I/SELinux ( 6034): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6034): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6034): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6034 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6034): TimaSignature is unavailable
,D/ActivityThread( 6034): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6018): TimaSignature is unavailable
,D/ActivityThread( 6018): Added TimaKeyStore provider
,W/ResourcesManager( 6034): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Killing 5199:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,W/ResourcesManager( 6018): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6049): MountEmulatedStorage(),
E/Zygote  ( 6049): v2
I/libpersona( 6049): KNOX_SDCARD checking this for 1000
I/libpersona( 6049): KNOX_SDCARD not a persona
I/SELinux ( 6049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 6049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5219:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #31
,E/SELinux ( 6049): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6049): TimaSignature is unavailable
,D/ActivityThread( 6049): Added TimaKeyStore provider
,D/SettingsProvider( 1018): name = next_alarm_formatted
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10081
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/CalendarProvider2( 6018): CalendarProvider2.onCreate() called
,D/TimeService( 6049): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449683681104
D/        ( 6049): TimeServiceNative: User Time to be set is 1449683681104
D/QC-time-services( 6049): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6049): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6049): Lib:time_genoff_operation: pargs->ts_val = 1449683681104
,D/QC-time-services(  342): Daemon: Connection accepted:time_genoff
,W/art     ( 5983): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 160.010ms
,D/QC-time-services( 6049): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  342): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449683681104
D/QC-time-services(  342): Daemon:genoff_opr: Base = 2, val = 1449683681104, operation = 0
D/QC-time-services(  342): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/5/70 11:40:13
D/QC-time-services(  342): Daemon:Value read from RTC seconds = 13434013000
D/QC-time-services(  342): Daemon:new time 1449683681104 
D/QC-time-services(  342): Daemon: delta 1436249668104 genoff 1436249668104 
D/QC-time-services(  342): Daemon:genoff_persistent_update: Writing genoff = 1436249668104 to memory,
D/QC-time-services(  342): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  342): Daemon:time_persistent_memory_opr:Genoff write operation 
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5199/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5219/cgroup.procs: No such file or directory
,D/QC-time-services(  342): Updating the TOD offset
D/QC-time-services(  342): Daemon:genoff_persistent_update: Writing genoff = 1436249668104 to memory
D/QC-time-services(  342): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  342): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  342): Daemon:Update to modem bit set
E/QC-time-services( 6049): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  342): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  342): Daemon: Base = 2, Value being sent to MODEM = 1120284868104
,I/ActivityManager( 1018): Killing 5237:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,E/QC-time-services(  342): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  342): Daemon: Time-services: Waiting to acceptconnection
,D/Mms/ArtClassLoader( 5983): init before art
,W/art     ( 5999): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 134.566ms
,D/Mms/TelephonyPermission( 5983): start operation mode monitor
,W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_5237/cgroup.procs: No such file or directory
,W/ResourcesManager( 5983): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5003): mConnectivityHandler : connected
,D/Mms/TelephonyPermission( 5983): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5983): isDefault true
,D/Mms/MmsApp( 5983): onCreate() com.android.mms
,W/PCWCLIENTTRACE_AccountUtil( 5003): [hasSamungAccount] - No Samsung Account
,E/SMD     (  303): DCD OFF
,D/Mms/MmsApp( 5983): [start]    initCountryIso consume time = 374.430729
,D/CountryDetector( 1018): The first listener is added
,D/Mms/MmsApp( 5983): [end]    initCountryIso consume time = 10.507031
,D/Mms/MmsConfig( 5983): [start]    MmsConfig.init() consume time = 1.302396
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6070): MountEmulatedStorage()
E/Zygote  ( 6070): v2
I/libpersona( 6070): KNOX_SDCARD checking this for 10090
I/libpersona( 6070): KNOX_SDCARD not a persona
,I/SELinux ( 6070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6070): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6070 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5284:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5003): [GetString-S]
,D/Mms/MmsConfig( 5983): before partial update
,I/ReactiveServiceManager( 5003): Supported : 1
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/TimaKeyStoreProvider( 6070): TimaSignature is unavailable
,D/ActivityThread( 6070): Added TimaKeyStore provider
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 9
,D/Mms/MmsConfig( 5983): Load Resize quality : 80,
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 9
,E/terrier ( 1018): handleString: Failed to handle string(-4)
E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5003): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5003): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5003): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5003): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5003): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5003): [ensureRegistration] - No Samsung account
D/EasySignUpManager_1.0.1( 5983): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 5983): isAuth is false
D/Mms/MmsConfig( 5983): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1440): query,matched:2117, calling pid = 5983
,D/TP/MmsSmsProvider( 1440): match 2117:Elapsed time : 1.325 ms
,D/EasySignUpManager_1.0.1( 5983): isAuth is false
D/EasySignUpManager_1.0.1( 5983): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5983): mps_code.dat does not exist
E/CscParser( 5983): customer_path =/system/csc/customer.xml
,E/CscParser( 5983): fileName + /system/csc/customer.xml
,E/CscParser( 5983): mps_code.dat does not exist
E/CscParser( 5983): customer_path =/system/csc/customer.xml
E/CscParser( 5983): fileName + /system/csc/customer.xml
,W/libprocessgroup( 1018): failed to open /acct/uid_10052/pid_5284/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/CscParser( 5983): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 5983):  enable multiwindow = false
,D/elm:15121( 6070): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 6070): ELMEngine.ELMEngine( context ).
,I/DBG_POLICYDM( 5033): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/elm:15121( 6070): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/Mms/MessageUtils( 5983): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5983): updateCountryIso : update country iso info 
,D/elm:15121( 6070): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 6070): ElmAgentService : onCreate()
,D/elm:15121( 6070): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:15121( 6070): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,E/Zygote  ( 6092): MountEmulatedStorage(),
E/Zygote  ( 6092): v2
I/libpersona( 6092): KNOX_SDCARD checking this for 10130
,I/libpersona( 6092): KNOX_SDCARD not a persona
,I/SELinux ( 6092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
D/elm:15121( 6070): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6092 uid=10130 gids={50130, 9997} abi=armeabi-v7a,
D/elm:15121( 6070): ModuleBase.ModifySetAlarm()
D/elm:15121( 6070): MDMBridge.getInstance()
D/elm:15121( 6070): MDMBridge.getAllLicenseInfoFromSDK(),
D/Mms/MmsConfig( 5983): [end]    init() consume time = 241.968385
,D/Mms/Contact( 5983): [start]    init() consume time = 0.75323
,I/SELinux ( 6092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,D/elm:15121( 6070): ElmAgentService : onDestroy().,
,I/ActivityManager( 1018): Killing 4905:com.android.defcontainer/u0a3 (adj 15): empty #31
,E/SELinux ( 6092): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 5033): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,D/Mms/Contact( 5983): [end]    init consume time = 36.590937
,D/TP/MmsSmsProvider( 1440): query,matched:13, calling pid = 5983
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,D/TP/MmsSmsProvider( 1440): match 13:Elapsed time : 2.832 ms
,D/TimaKeyStoreProvider( 6092): TimaSignature is unavailable
,D/ActivityThread( 6092): Added TimaKeyStore provider
,D/Mms/DraftCache( 5983): [start]    rebuildCache consume time = 18.020156
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/Mms/MethodReflector( 5983): getSubId is called
D/Mms/TelephonyUtils( 5983): getLongSubId from simSlot 0, return Value = -1
,D/Mms/ArtClassLoader( 5983): init [DONE] art
,D/Mms/MethodReflector( 5983): getTelephonyProperty is called
,D/Mms/DownloadManager( 5983): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5983): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5983): auto download without roaming -> true
D/Mms/DownloadManager( 5983): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 5983): getSubId is called
,D/Mms/MethodReflector( 5983): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5983): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5983): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5983): getTelephonyProperty is called
D/Mms/DownloadManager( 5983): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5983): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5983): auto download without roaming -> true
D/Mms/DownloadManager( 5983): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5983): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5983): mAutoDownload ------> true
,I/DBG_POLICYDM( 5033): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/TP/MmsSmsProvider( 1440): query,matched:12, calling pid = 5983
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/TP/MmsSmsProvider( 1440): match 12:Elapsed time : 4.757 ms
,E/DBG_POLICYDM( 5033): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/Mms/DraftCache( 5983): [end]    rebuildCache consume time = 26.104011
,D/ComposerPerformance( 5983): 1449683681607 ms / [DONE] Composer constructor
,E/CII     ( 5983): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 5983): ReservationManager()
,I/Mms/ReservationManager( 5983): resetAfterConnected()
,D/TP/MmsSmsProvider( 1440): query,matched:7, calling pid = 5983
,D/TP/MmsSmsProvider( 1440): match 7:Elapsed time : 1.970 ms
,I/Mms/ReservationManager( 5983): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MmsApp( 5983): [end]    onCreate() consume time = 18.328541
,I/DBG_POLICYDM( 5033): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/Mms/DownloadManager( 5983): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/Conversation( 5983): [start]    init() consume time = 3.52823
,D/Mms/DownloadManager( 5983): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 5983): getSubId is called
,D/Mms/TelephonyUtils( 5983): getLongSubId from simSlot 0, return Value = -1
,I/DBG_POLICYDM( 5033): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,I/ActivityManager( 1018): Killing 5124:com.sec.android.provider.badge/u0a68 (adj 15): empty #31,
W/ResourcesManager( 6092): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6092): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/Mms/MethodReflector( 5983): getTelephonyProperty is called
,D/TP/MmsSmsProvider( 1440): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1440): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1440): updateThread(), thread_id = 9223372036854775807
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/Mms/DownloadManager( 5983): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5983): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5983): auto download without roaming -> true
D/Mms/DownloadManager( 5983): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/Mms/DownloadManager( 5983): mAutoDownload ------> true
,V/TP/MmsSmsDatabaseHelper( 1440): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1440): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1440): need read changed broadcast:false
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/libprocessgroup( 1018): failed to open /acct/uid_10003/pid_4905/cgroup.procs: No such file or directory
,D/Mms/Conversation( 5983): [end]    init consume time = 42.360677
,D/Mms/MessagingNotification( 5983): [start]    init() consume time = 0.075989
,D/Mms/MessagingNotification( 5983): [end]    init consume time = 3.311406
,V/HeadsetService( 5433): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5433): Disconnected process message: 10
,I/splitIntent( 1018): Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 5575:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
,D/Mms/Synchronizer( 5983): [start]    doSync consume time = 4.829844
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/Mms/SpamFilter( 5983): [start]    SpamFilter fill() begin consume time = 5.213646
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/TP/MmsSmsProvider( 1440): update, matched:300, calling pid = 5983
V/TP/MmsSmsProvider( 1440): syncDBData start
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,V/TP/MmsSmsProvider( 1440): syncDBData sms end
,V/TP/MmsSmsProvider( 1440): syncDBData mms end
,V/TP/MmsSmsProvider( 1440): syncDBData end
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,D/TP/MmsSmsProvider( 1440): query,matched:400, calling pid = 5983
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/TP/MmsSmsProvider( 1440): query,matched:0, calling pid = 5983
V/TP/MmsSmsProvider( 1440): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1440): match 0:Elapsed time : 1.658 ms
,D/Mms/Synchronizer( 5983): [end]    doSync consume time = 18.090104
,W/ResourcesManager( 3701): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3701): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Mms/SpamFilter( 5983): [end]    SpamFilter fill() finished consume time = 13.391511
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6116): MountEmulatedStorage()
,E/Zygote  ( 6116): v2
I/libpersona( 6116): KNOX_SDCARD checking this for 10068
I/libpersona( 6116): KNOX_SDCARD not a persona
,I/SELinux ( 6116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6116 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,I/SELinux ( 6116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6116): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6116): TimaSignature is unavailable
,D/ActivityThread( 6116): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10068/pid_5124/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10064/pid_5575/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 14571(725KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.586ms total 151.052ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5680): Thread[GAThread,5,main]: No campaign data found.
,D/BadgeProvider( 6116): onCreate
D/BadgeProvider( 6116): DatabaseHelper
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MessagingNotification( 5983): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1440): query,matched:26, calling pid = 5983
,D/TP/SmsProvider( 1440): match 26:Elapsed time : 1.124 ms
,D/TP/MmsSmsProvider( 1440): query,matched:6, calling pid = 5983
,D/TP/MmsSmsProvider( 1440): match 6:Elapsed time : 2.925 ms
,I/ActivityManager( 1018): Killing 5593:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6139 uid=10023 gids={50023, 9997} abi=armeabi-v7a,
,E/Zygote  ( 6139): MountEmulatedStorage()
,E/Zygote  ( 6139): v2
I/libpersona( 6139): KNOX_SDCARD checking this for 10023
,I/libpersona( 6139): KNOX_SDCARD not a persona
,I/SELinux ( 6139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6139): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6139): TimaSignature is unavailable
,D/ActivityThread( 6139): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5476:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1686): Vacuum at: now=1449683682114 tag=VacuumService
,W/libprocessgroup( 1018): failed to open /acct/uid_10065/pid_5593/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 1686): Using platform SSLCertificateSocketFactory
,I/OMACP   ( 6139): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/libprocessgroup( 1018): failed to open /acct/uid_10055/pid_5476/cgroup.procs: No such file or directory
,W/Uploader( 1686): No account for auth token provided
,D/Mms/Omacp( 5983): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 6139): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,I/dhcpcd  ( 5621): wlan0: sending IPv6 Router Solicitation
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/System.out( 1686): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1686): (HTTPLog)-Static: isShipBuild true
I/System.out( 1686): (HTTPLog)-Thread-205-532287044: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1686): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1686): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/qtaguid ( 1686): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,I/art     ( 1686): Explicit concurrent mark sweep GC freed 27058(1601KB) AllocSpace objects, 8(153KB) LOS objects, 39% free, 7MB/13MB, paused 2.551ms total 76.174ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6163 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/Zygote  ( 6163): MountEmulatedStorage()
E/Zygote  ( 6163): v2
I/libpersona( 6163): KNOX_SDCARD checking this for 10011
I/libpersona( 6163): KNOX_SDCARD not a persona
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/SELinux ( 6163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6163): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Babel   ( 3701): UserRecoverableAuthException.
I/art     (  324): Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 611us total 24.238ms
,E/Babel   ( 3701): eei: BadAuthentication
E/Babel   ( 3701): 	at eeg.a(Unknown Source)
E/Babel   ( 3701): 	at eeg.a(Unknown Source)
E/Babel   ( 3701): 	at eeg.a(Unknown Source)
E/Babel   ( 3701): 	at g.a(Unknown Source)
E/Babel   ( 3701): 	at cae.a(SourceFile:3089)
E/Babel   ( 3701): 	at cae.a(SourceFile:1131)
E/Babel   ( 3701): 	at cws.a(SourceFile:4333)
E/Babel   ( 3701): 	at cws.a(SourceFile:1419)
E/Babel   ( 3701): 	at crl.a(SourceFile:492)
E/Babel   ( 3701): 	at crl.a(SourceFile:1468)
E/Babel   ( 3701): 	at cqu.a(SourceFile:4416)
E/Babel   ( 3701): 	at cas.b(SourceFile:106)
E/Babel   ( 3701): 	at cap.d(SourceFile:335)
E/Babel   ( 3701): 	at caq.run(SourceFile:81)
,E/Babel   ( 3701): Error getting auth token
,E/Babel   ( 3701): dvm
E/Babel   ( 3701): 	at g.a(Unknown Source)
E/Babel   ( 3701): 	at cae.a(SourceFile:3089)
E/Babel   ( 3701): 	at cae.a(SourceFile:1131)
E/Babel   ( 3701): 	at cws.a(SourceFile:4333)
E/Babel   ( 3701): 	at cws.a(SourceFile:1419)
E/Babel   ( 3701): 	at crl.a(SourceFile:492)
E/Babel   ( 3701): 	at crl.a(SourceFile:1468)
E/Babel   ( 3701): 	at cqu.a(SourceFile:4416)
E/Babel   ( 3701): 	at cas.b(SourceFile:106)
E/Babel   ( 3701): 	at cap.d(SourceFile:335)
E/Babel   ( 3701): 	at caq.run(SourceFile:81)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
,E/Babel   ( 3701): Account registration failed 1-Redacted-21
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 21.074ms
,E/Babel   ( 3701): cyp: null -- null
E/Babel   ( 3701): 	at cae.a(SourceFile:3121)
E/Babel   ( 3701): 	at cae.a(SourceFile:1131)
E/Babel   ( 3701): 	at cws.a(SourceFile:4333)
E/Babel   ( 3701): 	at cws.a(SourceFile:1419)
E/Babel   ( 3701): 	at crl.a(SourceFile:492)
E/Babel   ( 3701): 	at crl.a(SourceFile:1468)
E/Babel   ( 3701): 	at cqu.a(SourceFile:4416)
E/Babel   ( 3701): 	at cas.b(SourceFile:106)
E/Babel   ( 3701): 	at cap.d(SourceFile:335)
E/Babel   ( 3701): 	at caq.run(SourceFile:81)
,I/art     ( 3701): Note: end time exceeds epoch: 
,D/TimaKeyStoreProvider( 6163): TimaSignature is unavailable
,D/ActivityThread( 6163): Added TimaKeyStore provider
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 16.936ms
,I/System.out( 3701): (HTTPLog)-Static: isSBSettingEnabled false
,I/MusicLeanback( 5662): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5662): Stop autocaching.
,W/ResourcesManager( 6163): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6163): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Uploader( 1686): No account for auth token provided
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1686): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,I/MultiDex( 6163): VM with version 2.1.0 has multidex support
I/MultiDex( 6163): install
I/MultiDex( 6163): VM has multidex support, MultiDex support library is disabled.
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/CalendarProvider2( 6018): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,V/JNIHelp ( 6163): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/jxcore-log( 5383): Test app app.js loaded
I/jxcore-log( 5383): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/chromium( 5383): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ResourcesManager( 1686): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
W/Uploader( 1686): No account for auth token provided
,I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1686): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityThread( 6163): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/System  ( 6163): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f20a259: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6163): Installed default security provider GmsCore_OpenSSL
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
D/GCM     ( 1686): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/Babel   ( 3701): Unexpected exception while authenticating.
,E/Babel   ( 3701): eej: User intervention required. Notification has been pushed.
E/Babel   ( 3701): 	at eeg.b(Unknown Source)
E/Babel   ( 3701): 	at eeg.b(Unknown Source)
E/Babel   ( 3701): 	at g.a(Unknown Source)
E/Babel   ( 3701): 	at cae.b(SourceFile:1146)
E/Babel   ( 3701): 	at dcg.run(SourceFile:5617)
E/Babel   ( 3701): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 3701): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 3701): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1686): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1686):  no longer exists, so no auth token.
,V/GmsCoreStatsServiceLauncher( 1941): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1686): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6163): callingUid 10011, callindPid: 6163
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1686): No account for auth token provided
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1686): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1941): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1663): [180] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 5662): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5662): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
E/Uploader( 1686): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1686): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1686): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1686): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1686): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1686): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1686): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1686): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1686): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1686): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1686): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1686): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1686): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1686): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/Uploader( 1686): No account for auth token provided
,I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1686): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,E/SQLiteLog( 1686): (10) POSIX Error : 11 SQLite Error : 3850
,E/Watchdog( 1018): !@Sync 5
,I/Mms/MmsApp( 5983):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5983): [start]    fillCache consume time = 1910.449791
D/Mms/ComposeMessageFragment( 5983): fillCache, easy = false
,D/AbsListView( 5983): Get MotionRecognitionManager
,D/MotionRecognitionService( 1018):  ssp status : false
,D/Mms/ComposeMessageFragment( 5983): [end]    fillCache consume time = 80.804427
,D/Mms/BubbleViewCache( 5983): fillCache bubble = 1
,E/SMD     (  303): DCD OFF
,I/dhcpcd  ( 5621): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 5621): wlan0: no IPv6 Routers available
,D/SSRM:n  ( 1018): SIOP:: AP = 330,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,I/ActivityManager( 1018): Killing 5003:com.sec.pcw.device/1000 (adj 15): empty #31
,D/Finsky  ( 4681): [766] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4681): [766] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5003/cgroup.procs: No such file or directory
,E/SMD     (  303): DCD OFF
,I/ActivityManager( 1018): Killing 5735:com.sec.android.cloudagent/u0a1 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10001/pid_5735/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 5758:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5758/cgroup.procs: No such file or directory
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5300): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5300): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5300): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5300): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5300): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5300): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5300): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5300): entry::IDLE
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5433): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5433): Disconnected process message: 10
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 300,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4681): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4681): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4681): [1] 5.onFinished: Giving up after 6 failures.
,V/AlarmManager( 1018): waitForAlarm result :8
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 1018): [PWL] Off : 140s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5433): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5433): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5433): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5433): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4,
,I/BooksSync( 5680): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5680): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0,
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
,D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5680): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5680): Soft error
E/BooksSync( 5680): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5680): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5680): Sync error
E/BooksSync( 5680): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5680): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5680): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 194048, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 32779(1768KB) AllocSpace objects, 24(397KB) LOS objects, 33% free, 23MB/35MB, paused 2.426ms total 139.873ms
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  303): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/Watchdog( 1018): !@Sync 7
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  303): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 8
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  303): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1018): [PWL] Off : 225s ago,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :4
,I/BooksSync( 5680): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5680): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5680): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5680): Soft error
E/BooksSync( 5680): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5680): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5680): Sync error
E/BooksSync( 5680): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5680): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5680): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284421, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 9
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5433): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5433): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5433): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5433): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1018): initializing...
,I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 10
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,E/SMD     (  303): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5433): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5433): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 10
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  303): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5433): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5433): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  303): DCD OFF
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1686): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1686): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1686): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1686): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1686): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1686): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1686): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
E/PlayEventLogger( 4681): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4681): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4681): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4681): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4681): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4681): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4681): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4681): Ignoring header User-Agent because its value was null.
,I/System.out( 4681): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 4681): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4681): (HTTPLog)-Static: isShipBuild true
I/System.out( 4681): (HTTPLog)-Thread-788-102880201: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4681): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10026
,I/System.out( 4681): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5433): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5433): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 11
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5433): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5433): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1018): waitForAlarm result :8
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,I/jxcore-log( 5383): Toggling radios to false
I/jxcore-log( 5383): 
,D/BluetoothAdapter( 5383): disable()
,D/SettingsProvider( 1018): name = bluetooth_on
,D/BluetoothAdapterState( 5433): CURRENT_STATE=ON, MSG = USER_TURN_OFF
D/BluetoothAdapterProperties( 5433): Setting state to 13
I/BluetoothAdapterState( 5433): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 5433): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5433): updateAdapterState state is 13
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
D/BluetoothAdapterService( 5433): Autoconnection is available 
D/BluetoothAdapterService( 5433): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 5433): terminating service from this receiver
D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
D/SettingsProvider( 1018): name = wifi_on,
D/WifiService( 1018): setWifiEnabled: false pid=5383, uid=10338
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothPbapService( 5433): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/BluetoothAdapterProperties( 5433): onBluetoothDisable()
D/BluetoothAdapterProperties( 5433): mDiscovering is false
D/BluetoothSocket( 5433): close() in, this: android.bluetooth.BluetoothSocket@2c326e1e, channel: 19, state: LISTENING
D/BluetoothSocket( 5433): close() this: android.bluetooth.BluetoothSocket@2c326e1e, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@dc21c46, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@383a36ffmSocket: android.net.LocalSocket@35c54ccc impl:android.net.LocalSocketImpl@34300b15 fd:FileDescriptor[74]
D/BluetoothSocket( 5433): Closing mSocket: android.net.LocalSocket@35c54ccc impl:android.net.LocalSocketImpl@34300b15 fd:FileDescriptor[74]
,D/SecContentProvider( 1018): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 5433): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothPbap( 1298): Proxy object disconnected
D/PbapServerProfile( 1298): Bluetooth service disconnected
,I/jxcore-log( 5383): Radios toggled
I/jxcore-log( 5383): 
,E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 5498): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5498): wlan0: Setting scan request: 0 sec 0 usec
D/BluetoothAdapterProperties( 5433): Scan Mode:20
,I/wpa_supplicant( 5498): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 5498): Scan requested (ret=0) - scan timeout 30 seconds
,D/BluetoothAdapterState( 5433): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 5433): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 5433): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 5433): cmd socket is not created
,E/BtOppRfcommListener( 5433): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btm  ( 5433): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 5433): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/btif_config_util( 5433): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-l2cap( 5433): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5433): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5433): L2CAP - PSM: 0x001b not found for deregistration
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1018): [BT Setting State] State =13
,D/BluetoothTile( 1175):  onBluetoothStateChange:
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1175): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1175):  getBluetoothState : 13
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,I/SamsungIME( 1749): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/STATUSBAR-QSTileView( 1175): onStateChanged: Bluetooth
,D/BluetoothSocket( 5433): close() in, this: android.bluetooth.BluetoothSocket@f85441b, channel: 5, state: LISTENING
D/BluetoothSocket( 5433): close() this: android.bluetooth.BluetoothSocket@f85441b, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24678e07, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3e6069b8mSocket: android.net.LocalSocket@2b934391 impl:android.net.LocalSocketImpl@3f7022f6 fd:FileDescriptor[76]
D/BluetoothSocket( 5433): Closing mSocket: android.net.LocalSocket@2b934391 impl:android.net.LocalSocketImpl@3f7022f6 fd:FileDescriptor[76]
,D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
V/BluetoothEventManager( 1298): Received android.bluetooth.adapter.action.STATE_CHANGED
,E/WifiNative-wlan0( 1018): do suspend true
,D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=false
I/BtOppRfcommListener( 5433): stopping Accept Thread
D/BluetoothSocket( 5433): close() in, this: android.bluetooth.BluetoothSocket@2daa06f7, channel: 12, state: LISTENING
D/BluetoothSocket( 5433): close() this: android.bluetooth.BluetoothSocket@2daa06f7, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f20a259, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@198e6964mSocket: android.net.LocalSocket@2d1787cd impl:android.net.LocalSocketImpl@33f37882 fd:FileDescriptor[80]
D/BluetoothSocket( 5433): Closing mSocket: android.net.LocalSocket@2d1787cd impl:android.net.LocalSocketImpl@33f37882 fd:FileDescriptor[80]
,I/BtOppRfcommListener( 5433): BluetoothSocket listen thread finished
,D/PhoneStatusBar( 1175): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,V/BluetoothOppManager( 5433): cleanUp...
,W/ContextImpl( 1298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/DockEventReceiver( 1298): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1298): onReceive
,V/BluetoothStatusReceiver( 1175): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1175): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6304): MountEmulatedStorage(),
I/libpersona( 6304): KNOX_SDCARD checking this for 10055
E/Zygote  ( 6304): v2
I/libpersona( 6304): KNOX_SDCARD not a persona
,I/SELinux ( 6304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6304 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 6304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6304): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6304): TimaSignature is unavailable
,D/ActivityThread( 6304): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 6304): PlaceProvider onCreate()
,W/bt-l2cap( 5433): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 5433): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_userial_mct( 5433): exiting userial_read_thread
D/bt_userial_mct( 5433): Leaving userial_evt_read_thread()
D/bt_userial_mct( 5433): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 5433): hw_epilog_process
W/bt-l2cap( 5433): L2CAP - PSM: 0x001b not found for deregistration
D/UserAnalysis.SecureDbManager( 6304): Key for secure DB is newly created
W/bt-l2cap( 5433): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5433): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5433): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5433): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5433): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5433): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 5433): ag scb idx 1 not allocated
W/bt-btif ( 5433): ag scb idx 2 not allocated
E/bt-btif ( 5433): BTA AG is already disabled, ignoring ...
D/UserAnalysis.SecurePlaceDbHelper( 6304): SecurePlaceDbHelper() 
D/UserAnalysis( 6304): Create SecureDbHelper
,D/bt_userial_mct( 5433): userial_close
I/bt_vendor( 5433): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/IntelligenceServiceApplication( 6304): onCreate()
,I/ActivityManager( 1018): Killing 4306:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,D/IntelligenceServiceApplication( 6304): no applications having user consent for prediction
,D/AuthorizationBluetoothService( 1686): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/PlaceDetection v1.0.19 ( 6304): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 6304): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/libprocessgroup( 1018): failed to open /acct/uid_10039/pid_4306/cgroup.procs: No such file or directory
,I/wpa_supplicant( 5498): nl80211: Received scan results (1 BSSes)
,D/WifiP2pService( 1018): InactiveState{ what=147461 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147461 }
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/WifiP2pService( 1018): DefaultState{ what=147461 }
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 },
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,D/CommandListener(  279): Clearing all IP addresses on wlan0
V/NativeCrypto( 1686): Read error: ssl=0xb88c2800: I/O error during system call, Connection timed out
V/NativeCrypto( 1686): SSL shutdown failed: ssl=0xb88c2800: I/O error during system call, Broken pipe
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
I/WifiNative-HAL( 1018): startHal
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/wifi    ( 1018): getStaticLongField sWifiHalHandle 0x9d88c8ac
I/WifiNative-HAL( 1018): Could not start hal
E/ConnectivityService( 1018): updateNetworkInfo()
,E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/WifiP2pService( 1018): InactiveState{ what=131204 }
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=-4ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/WifiP2pService( 1018): P2pEnabledState{ what=131204 }
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
D/WifiP2pService( 1018): sending p2p connection changed broadcast: FAILED
,I/qtaguid ( 1018): Tagging socket 375 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,I/qtaguid ( 1018): Untagging socket 375
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiScanningService( 1018): SCAN_AVAILABLE : 1
D/WifiScanningService( 1018): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1018): SCAN_AVAILABLE : 1
D/RttService( 1018): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost
,D/WifiP2pService( 1018): sending p2p connection changed broadcast: DISCONNECTED
,D/WifiP2pService( 1018): P2pDisablingState
,D/WifiP2pService( 1018): P2pDisablingState{ what=147458 }
,D/WifiP2pService( 1018): p2p socket connection lost
D/WifiP2pService( 1018): P2pDisabledState
E/WifiNative-wlan0( 1018): do suspend true
,D/WifiDisplayController( 1018): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1018): onP2pDisconnected
,E/WifiStateMachine( 1018): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3423): Starting #8
I/Hs20UtilService( 3423): Message received 5007
,D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1298): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1298): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1298): MountReceiver.mPrefHandler - 7002
,D/IpRemoteDisplayController( 1018): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1018): WfdBridgeServer is already null
D/WifiDisplayController( 1018): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1018): disconnect
D/WifiDisplayController( 1018): updateConnection
D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1175): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1175): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/WifiP2pService( 1018): P2pDisabledState{ what=143375 }
,D/WifiP2pService( 1018): DefaultState{ what=143375 }
,D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NearbySettings( 1298): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - P2P: IDLE
,D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1298): MountReceiver.onReceive - Set preference state off
,D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1440): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524292
,V/NearbySettings( 1298): MountReceiver.mPrefHandler - 7002
,D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,I/wpa_supplicant( 5498): p2p0: State: DISCONNECTED -> DISCONNECTED
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TelephonyNetworkFactory( 1440): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/bt_vendor( 5433): bt-vendor : BT_VND_OP_POWER_CTRL: Off
,I/bt_vendor( 5433): bluetooth satus is on
I/bt_vendor( 5433): bt-vendor : resetting BT status
I/bt_vendor( 5433): Starting hciattach daemon
I/bt_vendor( 5433): try to set false
,I/bt_vendor( 5433): Starting hciattach daemon
I/bt_vendor( 5433): try to set false
,I/bt_vendor( 5433): cleanup
E/Zygote  ( 6327): MountEmulatedStorage()
I/libpersona( 6327): KNOX_SDCARD checking this for 10064
E/Zygote  ( 6327): v2
I/libpersona( 6327): KNOX_SDCARD not a persona
,I/GKI_LINUX( 5433): gki_task task_id=0 [BTU] terminating
I/SELinux ( 6327): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/GKI_LINUX( 5433): GKI_exit_task 0 done
I/GKI_LINUX( 5433): GKI_shutdown(): task [BTU] terminated
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6327 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6327): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6327): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
E/ConnectivityService( 1018): updateNetworkInfo()
D/BluetoothAdapterState( 5433): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5433): isSecureModeOn:false
D/BluetoothAdapterService( 5433): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 5433): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.gatt.GattService
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/SecContentProvider2( 1018): mCursor = null
,V/NetworkStats( 1018): updateIfacesLocked()
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 5ms
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/HotspotTile( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-QSTileView( 1175): onStateChanged: Wi-Fi
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/HotspotTile( 1175): onReceive : 0, 0
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1175): Wifi onReceive(0)
D/WifiCredService( 1298): Action received :android.net.wifi.WIFI_STATE_CHANGED
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BtGatt.DebugUtils( 5433): handleDebugAction() action=null
I/art     ( 1440): Background sticky concurrent mark sweep GC freed 59180(3MB) AllocSpace objects, 9(144KB) LOS objects, 38% free, 5MB/8MB, paused 5.789ms total 65.676ms
W/BluetoothAdapterService( 5433): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 5433): Received stop request...Stopping profile...
D/BtGatt.GattService( 5433): stop()
D/BtGatt.AdvertiseManager( 5433): advertise clients cleared
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.hfp.HeadsetService
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5433): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.a2dp.A2dpService
I/wpa_supplicant( 5498): Blacklist: Clear (all) 
D/TimaKeyStoreProvider( 6327): TimaSignature is unavailable
D/ActivityThread( 6327): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5433): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.hid.HidService
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5433): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.hdp.HealthService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5433): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.pan.PanService
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5433): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5433): Not skipping com.android.bluetooth.map.BluetoothMapService
W/ResourcesManager( 6327): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5433): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5433): Not skipping com.broadcom.bt.service.sap.SapService
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5433): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5433): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5433): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5433): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5433): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5433): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5433): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/FileShare-Client( 6327): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5433): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 5433): Stopping profile services that were post enabled
E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/HeadsetService( 5433): Received stop request...Stopping profile...
D/FileShare-Client( 6327): ClientBroadcastReceiver.onReceive - disconnected
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
D/AudioService( 1018): onServiceDisconnected: Bluetooth profile: 1
D/A2dpService( 5433): Received stop request...Stopping profile...
D/A2dpStateMachine( 5433): Exit Disconnected: -1
D/HeadsetProfile( 1298): Bluetooth service disconnected
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
D/HidService( 5433): Received stop request...Stopping profile...
I/wpa_supplicant( 5498): p2p0: CTRL-EVENT-TERMINATING 
D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceStatusChanged p2p0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
D/HidService( 5433): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 5433): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5433): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5433): Cleaning up Bluetooth GID callback object
D/BluetoothA2dp( 1018): Proxy object disconnected
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
D/AudioService( 1018): onServiceDisconnected: Bluetooth profile: 2
D/BluetoothA2dp( 1298): Proxy object disconnected
D/A2dpProfile( 1298): Bluetooth service disconnected
D/BluetoothInputDevice( 1298): Proxy object disconnected
D/HidProfile( 1298): Bluetooth service disconnected
D/HealthService( 5433): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
,D/PanService( 5433): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
D/BluetoothPan( 1018): BluetoothPAN Proxy object disconnected
D/BluetoothMapService( 5433): Received stop request...Stopping profile...
D/BluetoothPan( 1298): BluetoothPAN Proxy object disconnected
D/PanProfile( 1298): Bluetooth service disconnected
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
D/FileShare-Client( 6327): Outbound.stopDelayTimer - 
D/SapService( 5433): Received stop request...Stopping profile...
D/SapService( 5433): Stopping Bluetooth SapService
D/BluetoothAdapterService( 5433): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b6b40c
D/BluetoothMap( 1298): Proxy object disconnected
D/MapProfile( 1298): Bluetooth service disconnected
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6343): MountEmulatedStorage()
E/Zygote  ( 6343): v2
I/libpersona( 6343): KNOX_SDCARD checking this for 10065
I/libpersona( 6343): KNOX_SDCARD not a persona
I/SELinux ( 6343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6343 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5433): Profile still running: com.android.bluetooth.hid.HidService
W/BluetoothHeadsetServiceJni( 5433): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5433): Cleaning up Bluetooth Handsfree callback object
I/wpa_supplicant( 5498): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/SELinux ( 6343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/wpa_supplicant( 5498): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 5498): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 5498): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 5498): wlan0: State: DISCONNECTED -> DISCONNECTED
E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.hid.HidService
E/SELinux ( 6343): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BluetoothAdapterService( 5433): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 5433): Proxy object disconnected
D/BluetoothAdapterService( 5433): Bluetooth A2dp source service disconnected
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/GKI_LINUX( 5433): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 5433): GKI_exit_task 2 done
D/Tethering( 1018): InitialState.processMessage what=4
I/GKI_LINUX( 5433): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/Bluetoothsap( 1298): BluetoothSAP Proxy object disconnected
D/SapProfile( 1298): Bluetooth service disconnected
E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5433): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5433): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 5433): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5433): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
E/Tethering( 1018): No numeric data
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5433): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 5433): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5433): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5433): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5433): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(615953420)( 5433): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
W/BluetoothSAPServiceJni( 5433): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 5433): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/ActivityManager( 1018): Killing 5797:com.sec.android.soagent/u0a31 (adj 15): empty #31
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,D/BluetoothAdapterState( 5433): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 5433): Setting state to 10
I/BluetoothAdapterState( 5433): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5433): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5433): updateAdapterState state is 10
D/BluetoothA2dp( 1018): onBluetoothStateChange: up=false
,D/BluetoothAdapterService( 5433): Autoconnection is available 
D/BluetoothAdapterService( 5433): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 5433): Entering OffState
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1175): updateTetherState():false, false
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 4ms
,D/BluetoothA2dp( 1298): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1018): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1018): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1414): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1414): Bluetooth is turned off, stop adv and scan
,D/BluetoothPbap( 1298): onBluetoothStateChange: up=false
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/BluetoothInputDevice( 1298): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 5433): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1175): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1175): Bluetooth is turned off, stop adv and scan
,D/Bluetoothsap( 1298): onBluetoothStateChange: up=false
D/Bluetoothsap( 1298): Unbinding service...
,D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothAdapter( 5383): onBluetoothStateChange: up=false
D/BluetoothAdapter( 5383): Bluetooth is turned off, stop adv and scan
D/TimaKeyStoreProvider( 6343): TimaSignature is unavailable
D/BluetoothAdapter( 1424): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1424): Bluetooth is turned off, stop adv and scan
,D/ActivityThread( 6343): Added TimaKeyStore provider
,D/BluetoothAdapter( 1298): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1298): Bluetooth is turned off, stop adv and scan
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
D/BluetoothAdapter( 5433): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 5433): Bluetooth is turned off, stop adv and scan
D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapter( 1663): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1663): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1440): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1440): Bluetooth is turned off, stop adv and scan
D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothMap( 1298): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3,
D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1018): [BT Setting State] State =10
I/InputMethodManagerService( 1018): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3,
D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 1175): 414725983: getState() :  mService = null. Returning STATE_OFF
D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothTile( 1175):  getBluetoothState : 10
D/BluetoothAdapter( 1175): 414725983: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1175): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 1175): 414725983: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1175): 414725983: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1175): 414725983: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=false
D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/PhoneStatusBar( 1175): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
I/SamsungIME( 1749): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,V/BluetoothEventManager( 1298): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileShare-Server( 6343): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/GKI_LINUX( 5433): gki_task task_id=1 [BTIF] terminating
D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/GKI_LINUX( 5433): GKI_exit_task 1 done
I/GKI_LINUX( 5433): GKI_shutdown(): task [BTIF] terminated
D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
D/PhoneApp( 1440): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/BluetoothServiceJni( 5433): cleanupNative: return from cleanup
,I/art     ( 5433): System.exit called, status: 0
,I/AndroidRuntime( 5433): VM exiting with result code 0, cleanup skipped.
D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1018): Killing 5033:com.policydm/1000 (adj 15): empty #31
,D/PhoneStatusBar( 1175): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3423): Starting #9
,I/Hs20UtilService( 3423): Message received 5007
,D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1298): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1298): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1298): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/SecurityLogAgent( 5535): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5535): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5535): StateMachine : Current State = 1
,D/SecurityLogAgent( 5535): StateMachine : Changed Current State = 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/Hs20UtilService( 3423): Starting #10
W/libprocessgroup( 1018): failed to open /acct/uid_10031/pid_5797/cgroup.procs: No such file or directory
,I/Hs20UtilService( 3423): Message received 5011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/wpa_supplicant( 5498): Blacklist: Clear (all) 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1018): Process com.android.bluetooth (pid 5433)(adj 0) has died(58,621)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ContextImpl( 1298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5033/cgroup.procs: No such file or directory
,D/DockEventReceiver( 1298): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1298): onReceive
,V/BluetoothStatusReceiver( 1175): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1175): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 5498): wlan0: CTRL-EVENT-TERMINATING 
,E/Zygote  ( 6376): MountEmulatedStorage(),
,E/Zygote  ( 6376): v2
I/libpersona( 6376): KNOX_SDCARD checking this for 1002
I/libpersona( 6376): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6376 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux ( 6376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6376): TimaSignature is unavailable,
,D/ActivityThread( 6376): Added TimaKeyStore provider
,W/ResourcesManager( 6376): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6376): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni( 6376): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 6376): Adding GattService
,D/BtSettings.ProfileConfig( 6376): Adding HeadsetService
,D/BtSettings.ProfileConfig( 6376): Adding A2dpService
,D/BtSettings.ProfileConfig( 6376): Adding HidService
D/BtSettings.ProfileConfig( 6376): Adding HealthService
,D/BtSettings.ProfileConfig( 6376): Adding PanService
D/BtSettings.ProfileConfig( 6376): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 6376): Adding SapService
D/BtSettings.ProfileConfig( 6376): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 6376): Adding A2dpSinkService
,D/BtSettings.ProfileConfig( 6376): Adding SapClientService
D/BtSettings.ProfileConfig( 6376): Adding HidDevService
I/BtSettings.ProfileConfig( 6376): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
E/WifiStateMachine( 1018): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [21]
,D/SettingsProvider( 1018): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/Settings( 3701): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1175): Wifi onReceive(1)
,D/HotspotTile( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1175): onStateChanged: Wi-Fi
,W/Settings( 1663): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiCredService( 1298): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1175): onReceive : 1, 0
,I/ActivityManager( 1018): Killing 5824:com.samsung.android.sconnect/u0a121 (adj 15): empty #31
,D/AuthorizationBluetoothService( 1686): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3423): Starting #11
,I/Hs20UtilService( 3423): Message received 5011
,D/SecurityLogAgent( 5535): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5535): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5535): StateMachine : Current State = 1
D/SecurityLogAgent( 5535): StateMachine : Changed Current State = 1
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1018): updateDataUsageMap
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6392): MountEmulatedStorage(),
,E/Zygote  ( 6392): v2
I/libpersona( 6392): KNOX_SDCARD checking this for 1000
I/libpersona( 6392): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6392 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6392): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6392): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6392): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1018): failed to open /acct/uid_10121/pid_5824/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6392): TimaSignature is unavailable
,D/ActivityThread( 6392): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 6392): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 6392): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6392): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 6392): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6392): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6392): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6392): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
,I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6392): noConnectivity : true
,V/MusicLeanback( 5662): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager( 1018): Killing 5502:com.android.email/u0a141 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10141/pid_5502/cgroup.procs: No such file or directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6409): MountEmulatedStorage(),
I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6409 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6409): v2
I/libpersona( 6409): KNOX_SDCARD checking this for 10001
I/libpersona( 6409): KNOX_SDCARD not a persona
,I/SELinux ( 6409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6409): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6409): TimaSignature is unavailable
,D/ActivityThread( 6409): Added TimaKeyStore provider
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6426): MountEmulatedStorage(),
E/Zygote  ( 6426): v2
I/libpersona( 6426): KNOX_SDCARD checking this for 1000
I/libpersona( 6426): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6426 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
I/ActivityManager( 1018): Killing 5869:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
,I/SELinux ( 6426): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6426): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6426): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6426): TimaSignature is unavailable
,D/ActivityThread( 6426): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6426): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,E/Watchdog( 1018): !@Sync 12
,D/Tethering( 1018): interfaceRemoved wlan0
,E/Tethering( 1018): attempting to remove unknown iface (wlan0), ignoring
,W/libprocessgroup( 1018): failed to open /acct/uid_10110/pid_5869/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6426): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6426): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6426): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6426): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6426): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6426): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,I/ActivityManager( 1018): Killing 5925:com.android.chrome/u0a77 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3446): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 18:58:13 GMT+01:00 2015
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3446): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3446): KLMSIntentService(): onCreate()
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3446): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3446): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3446): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  ( 6443): MountEmulatedStorage(),
I/libpersona( 6443): KNOX_SDCARD checking this for 10031
E/Zygote  ( 6443): v2
I/libpersona( 6443): KNOX_SDCARD not a persona
I/KLMS-2.5.123: ( 3446): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/SELinux ( 6443): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/KLMS-2.5.123: ( 3446): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/SELinux ( 6443): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/KLMS-2.5.123: ( 3446): StateImplV2(): networkChangeListener().END
E/SELinux ( 6443): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6443 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3446): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6443): TimaSignature is unavailable
,D/ActivityThread( 6443): Added TimaKeyStore provider
,I/SO_AGENT( 6443): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6459): MountEmulatedStorage()
,E/Zygote  ( 6459): v2
,I/libpersona( 6459): KNOX_SDCARD checking this for 1000
I/libpersona( 6459): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=6459 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6459): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 5261:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,I/SELinux ( 6459): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6459): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6459): TimaSignature is unavailable
,D/ActivityThread( 6459): Added TimaKeyStore provider
,D/Tethering( 1018): interfaceRemoved p2p0
,E/Tethering( 1018): attempting to remove unknown iface (p2p0), ignoring
,I/DBG_POLICYDM( 6459): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 6459): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 6459): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 6459): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 6459): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 6459): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 6459): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 6459): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 6459): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 6459): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 6459): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 6459): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 6459): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,W/libprocessgroup( 1018): failed to open /acct/uid_10077/pid_5925/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10117/pid_5261/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 6459): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 6459): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 6459): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 6459): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5086): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5086): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5086): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 6459): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 5086): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5086): [OR] == isSIMCardReady false ==
,I/SA      ( 5086): [SCU] == networkStateCheck == false
I/SA      ( 5086): [OR] onReceive END
,I/DBG_POLICYDM( 6459): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 6459): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,I/ActivityManager( 1018): Killing 5948:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,E/DBG_POLICYDM( 6459): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,V/DownloadManager( 1227): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1573): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 1573): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1573): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1573): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1573): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1573): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1573): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6479): MountEmulatedStorage()
I/libpersona( 6479): KNOX_SDCARD checking this for 10121
E/Zygote  ( 6479): v2
I/libpersona( 6479): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6479 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6479): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 6459): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 6459): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 6459): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 6459): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,D/TimaKeyStoreProvider( 6479): TimaSignature is unavailable
,D/ActivityThread( 6479): Added TimaKeyStore provider
,W/ResourcesManager( 6479): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6479): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6479): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6479): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6479): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,W/libprocessgroup( 1018): failed to open /acct/uid_10058/pid_5948/cgroup.procs: No such file or directory
,I/QuickConnect( 6479): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6494): MountEmulatedStorage(),
E/Zygote  ( 6494): v2
I/libpersona( 6494): KNOX_SDCARD checking this for 10141
I/libpersona( 6494): KNOX_SDCARD not a persona
,I/SELinux ( 6494): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6494): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6494 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux ( 6494): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 5983:com.android.mms/u0a41 (adj 15): empty #31
,I/art     (  324): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 19.953ms
,D/TimaKeyStoreProvider( 6494): TimaSignature is unavailable,
D/ActivityThread( 6494): Added TimaKeyStore provider
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.401ms
,W/ResourcesManager( 6494): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6494): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6494): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6494): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.492ms
,D/CountryDetector( 1018): No listener is left
,W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_5983/cgroup.procs: No such file or directory
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/BadgeProvider( 6116): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/BadgeProvider( 6116): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 6116): sendNotify, [notify] : null
D/BadgeProvider( 6116): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6116): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6116): update, [UpdateCount] : 1
,D/Launcher.Model( 1462): reloadBadges entered.
,D/SecurityLogAgent( 5535): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5535): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5535): StateMachine : Current State = 1
D/SecurityLogAgent( 5535): StateMachine : Changed Current State = 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 1941): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/iu.UploadsManager( 1941): num queued entries: 0
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
I/iu.UploadsManager( 1941): num updated entries: 0
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.SyncManager( 1941): NEXT; no task
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 5848): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,I/Babel   ( 3701): connection state changed from CONNECTED to DISCONNECTED
,E/SPPClientService( 5848): [SystemStateMoniter] Current Time : 378982
,E/SPPClientService( 5848): [SystemStateMoniter] No Connect : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/SPPClientService( 5848): [[SystemStateMonitorService]] No Active Internet
,E/Zygote  ( 6521): MountEmulatedStorage()
E/Zygote  ( 6521): v2
I/libpersona( 6521): KNOX_SDCARD checking this for 10110
I/libpersona( 6521): KNOX_SDCARD not a persona
,I/SELinux ( 6521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6521): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6521): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6521 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5999:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6521): TimaSignature is unavailable
,D/ActivityThread( 6521): Added TimaKeyStore provider
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/libprocessgroup( 1018): failed to open /acct/uid_10081/pid_5999/cgroup.procs: No such file or directory
,I/GAv4    ( 6521): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6521):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6521):   adb logcat -s GAv4
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6521): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6521): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6521): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6521): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6521): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6521): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6521): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/WifiStateMachine( 1018): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,E/SMD     (  303): DCD OFF
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6521): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6521): Time to load native libraries: 1 ms (timestamps 9394-9395)
I/LibraryLoader( 6521): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6521): Binding Chromium to main looper Looper (main, tid 1) {35c54ccc}
,I/LibraryLoader( 6521): Expected native library version number "",actual native library version number ""
,I/chromium( 6521): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6521): Initializing chromium process, singleProcess=true
,W/art     ( 6521): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6521): ApplicationContext is null in ApplicationStatus
,W/chromium( 6521): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6521): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6521): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6521): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6521): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6521): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6521): Local Branch: 
I/Adreno-EGL( 6521): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6521): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6521):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6521): Requires BLUETOOTH permission
,I/NSApplication( 6521): Starting up...
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6576): MountEmulatedStorage()
,E/Zygote  ( 6576): v2
I/libpersona( 6576): KNOX_SDCARD checking this for 10077
I/libpersona( 6576): KNOX_SDCARD not a persona
,I/SELinux ( 6576): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6576 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 6034:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,I/SELinux ( 6576): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6576): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6576): TimaSignature is unavailable
,D/ActivityThread( 6576): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10153/pid_6034/cgroup.procs: No such file or directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6593): MountEmulatedStorage(),
I/libpersona( 6593): KNOX_SDCARD checking this for 10117
E/Zygote  ( 6593): v2
I/libpersona( 6593): KNOX_SDCARD not a persona,
I/SELinux ( 6593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6593 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6593): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 6049:com.qualcomm.timeservice/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6593): TimaSignature is unavailable
,D/ActivityThread( 6593): Added TimaKeyStore provider
,W/ResourcesManager( 6593): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6049/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 6018:com.android.providers.calendar/u0a37 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10037/pid_6018/cgroup.procs: No such file or directory
,I/PowerManagerService( 1018): [PWL] Off : 330s ago
,I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=4665),
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10011
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 13
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,D/ConnectivityService( 1018): Failed to find a new network - expiring NetTransition Wakelock,
,E/Watchdog( 1018): !@Sync 14
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  303): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 390s ago,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 15
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/bootchecker(  331): bootchecker wake up!!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 16
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1018): [PWL] Off : 455s ago
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 17
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 18,
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1018): [PWL] Off : 525s ago,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,I/Atfwd_Daemon(  335): Stop the daemon....,
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 19
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 20
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 21
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 600s ago,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 22
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 23
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 680s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1018): !@Sync 24
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1018): !@Sync 25
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 26
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,V/AlarmManager( 1018): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167],
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 765s ago
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 27
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 28
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 29
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 855s ago,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,E/SMD     (  303): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1018): !@Sync 30
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 31,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 32
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1018): [PWL] Off : 951s ago
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 33
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 34,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 35
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 36
,E/SMD     (  303): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1051s ago,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1018): !@Sync 37
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1018): !@Sync 38
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 39
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/PowerManagerService( 1018): [PWL] Off : 1156s ago
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1018): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1018): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1018): Updating Usage Statistics in DB @ 1449684730912
,I/NetworkDataUsageDb( 1018): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1018): ::isTableExists: Table exists 
,I/ApplicationUsage( 1018): Done Updating Usage Statistics in DB @ 1449684730954
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 40
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 41,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 42
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 43
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1266s ago
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 44
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 45
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 46
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 47
,E/SMD     (  303): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1381s ago,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 48
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1018): !@Sync 49
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1018): !@Sync 50
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 51
,E/SMD     (  303): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 1501s ago,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 52
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 53
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1018): !@Sync 54
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 55
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/PowerManagerService( 1018): [PWL] Off : 1626s ago,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 56
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 57
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1018): !@Sync 58
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 59
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 1756s ago
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3,
I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 60
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 61
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,V/AlarmManager( 1018): waitForAlarm result :4
,I/ActivityManager( 1018): Killing 6139:com.wsomacp/u0a23 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 6070:com.sec.esdk.elm/u0a90 (adj 15): empty #32
,I/ActivityManager( 1018): Killing 2558:com.sec.phone/1001 (adj 15): SPC_empty #33
I/ActivityManager( 1018): Killing 3597:com.sec.bcservice/1000 (adj 15): SPC_empty #34
I/ActivityManager( 1018): Killing 3113:com.sec.android.pagebuddynotisvc/u0a113 (adj 15): SPC_empty #35
I/ActivityManager( 1018): Killing 2689:com.samsung.android.providers.context/u0a2 (adj 15): SPC_empty #36
,D/Finsky  ( 4681): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/ProcessStatsService( 1018): Prepared write state in 14ms
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,V/NetworkStats( 1018): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,V/NetworkStats( 1018): performPollLocked() took 11ms
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/lowmemorykiller(  254): Error writing /proc/2558/oom_score_adj; errno=22
W/ActivityManager( 1018): ProcessRecord{57a01bc 2558:com.sec.phone/1001} is already killed
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 1018): Exception when unbinding service com.sec.phone/.SecPhoneService
W/ActivityManager( 1018): android.os.TransactionTooLargeException
W/ActivityManager( 1018): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 1018): 	at android.os.BinderProxy.transact(Binder.java:511)
W/ActivityManager( 1018): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:1029)
W/ActivityManager( 1018): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1997)
W/ActivityManager( 1018): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2381)
W/ActivityManager( 1018): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:18582)
W/ActivityManager( 1018): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6593)
W/ActivityManager( 1018): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:6806)
W/ActivityManager( 1018): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1606)
W/ActivityManager( 1018): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:566)
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1018): ProcessRecord{57a01bc 2558:com.sec.phone/1001} is already killed
,W/ActivityManager( 1018): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 1000ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10990ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GpsStatusListenerHelper( 1018): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@1775e0c1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): Scheduling restart of crashed service com.samsung.android.providers.context/.ContextService in 3694876ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1941): Aggregate from 1449682890228 (log), 1449682890228 (data)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 4681): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1686): Explicit concurrent mark sweep GC freed 38336(2MB) AllocSpace objects, 52(2MB) LOS objects, 39% free, 7MB/12MB, paused 988us total 49.111ms
,W/Finsky  ( 4681): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/Watchdog( 1018): !@Sync 62
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 4681): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4681): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4681): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4681): [1] DailyHygiene.reschedule: Scheduling new run in 86 minutes (failures=3)
,D/DeviceConnectionService( 1663): client connected with version: 7571000
,I/ProcessStatsService( 1018): Pruning old procstats: /data/system/procstats/state-2015-12-09-06-35-00.bin
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3597/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10090/pid_6070/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10113/pid_3113/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1001/pid_2558/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10023/pid_6139/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10002/pid_2689/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 6092:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 1686): (10) POSIX Error : 11 SQLite Error : 3850
,W/libprocessgroup( 1018): failed to open /acct/uid_10130/pid_6092/cgroup.procs: No such file or directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7237): MountEmulatedStorage(),
I/libpersona( 7237): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7237): v2
I/libpersona( 7237): KNOX_SDCARD not a persona
I/SELinux ( 7237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.bcservice for service com.sec.bcservice/.BroadcastService: pid=7237 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 7237): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7237): TimaSignature is unavailable
,D/ActivityThread( 7237): Added TimaKeyStore provider
,W/ResourcesManager( 7237): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/F_PHONE ( 7237): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 7237): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7252): MountEmulatedStorage(),
I/libpersona( 7252): KNOX_SDCARD checking this for 1001
E/Zygote  ( 7252): v2
I/libpersona( 7252): KNOX_SDCARD not a persona
,I/SELinux ( 7252): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 7252): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 7252): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.phone for service com.sec.phone/.SecPhoneService: pid=7252 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 7252): TimaSignature is unavailable
,D/ActivityThread( 7252): Added TimaKeyStore provider
,W/ResourcesManager( 7252): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/F_PHONE ( 7237): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 7237): default registerAction()
I/F_PHONE ( 7237): [[com.sec.bcservice]] sendPendingMessage()
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7273): MountEmulatedStorage()
,E/Zygote  ( 7273): v2
I/libpersona( 7273): KNOX_SDCARD checking this for 10113
I/libpersona( 7273): KNOX_SDCARD not a persona
,I/SELinux ( 7273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 7273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 7273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.pagebuddynotisvc for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc: pid=7273 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 7273): TimaSignature is unavailable
,D/ActivityThread( 7273): Added TimaKeyStore provider
,I/PageBuddyNotiSvc( 7273): onCreate mCpBitFlag=0
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4681): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4681): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4681): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 63
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4681): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4681): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4681): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  303): DCD OFF
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4681): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4681): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4681): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 64,
,E/SMD     (  303): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1891s ago
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4681): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4681): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4681): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 65
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7323): 
D/AndroidRuntime( 7323): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7323): CheckJNI is OFF
D/AndroidRuntime( 7323): readGMSProperty: start
D/AndroidRuntime( 7323): readGMSProperty: already setted!!
D/AndroidRuntime( 7323): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7323): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7323): readGMSProperty: end
D/AndroidRuntime( 7323): addProductProperty: start
E/AffinityControl( 7323): AffinityControl: registerfunction enter
D/AndroidRuntime( 7323): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{552620570}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1018): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 5383:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1018): Skipping PackageSetting{1590dd17 com.example.hello/10345} due to missing metadata
I/ActivityManager( 1018): Killing 6163:com.google.android.gms.wearable/u0a11 (adj 15): empty for 1801s
I/ActivityManager( 1018): Killing 5963:com.android.calendar/u0a131 (adj 15): empty for 1801s
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{1678660c u0 com.test.thalitest/.MainActivity t20}
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
D/InputDispatcher( 1018): Focus left window: 5383
I/SurfaceFlinger(  257): id=12 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=12 Removed NainActivit (-2/8)
D/InputDispatcher( 1018): Focused application released
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3738): Explicit concurrent mark sweep GC freed 3049(183KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 755us total 28.275ms
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1749): mOCRHelper is null
I/KLMS-2.5.123: ( 3446): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 19:24:44 GMT+01:00 2015
W/ResourcesManager( 1440): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/RegisteredServicesCache( 1424): empty dynamic service
I/art     ( 1018): Explicit concurrent mark sweep GC freed 52178(3MB) AllocSpace objects, 78(1442KB) LOS objects, 33% free, 24MB/36MB, paused 2.717ms total 185.564ms
I/art     ( 1018): WaitForGcToComplete blocked for 136.860ms for cause Explicit
D/RCPManagerService( 1018): PackageReceiver onReceive()
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
D/TaskPersister( 1018): removeObsoleteFile: deleting file=20_task.xml
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
I/art     ( 1018): Explicit concurrent mark sweep GC freed 16297(932KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 3.381ms total 155.091ms
I/art     ( 1018): WaitForGcToComplete blocked for 282.474ms for cause Explicit
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
W/GeofencerStateMachine( 1663): Ignoring removeGeofence because network location is disabled.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
I/KLMS-2.5.123: ( 3446): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
W/TextServicesManagerService( 1018): no available spell checker services found
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3446): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3446): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 7336): MountEmulatedStorage()
E/Zygote  ( 7336): v2
I/libpersona( 7336): KNOX_SDCARD checking this for 10090
I/libpersona( 7336): KNOX_SDCARD not a persona
I/SELinux ( 7336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7336 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 7336): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.123: ( 3446): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.123: ( 3446): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.123: ( 3446): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3446): KLMSIntentService(): listeningToPackageRemoved().START
D/TimaKeyStoreProvider( 7336): TimaSignature is unavailable
D/ActivityThread( 7336): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3446): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/elm:15121( 7336): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 7336): ELMEngine.ELMEngine( context ).
D/elm:15121( 7336): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 7336): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/PCWCLIENTTRACE_PushUtil( 6392): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6392): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6392): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6392): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3446): KLMSIntentService(): listeningToPackageRemoved().END
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3446): KLMSIntentService(): onDestroy()
D/elm:15121( 7336): ElmAgentService : onCreate()
D/elm:15121( 7336): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 7336): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 7336): MDMBridge.getInstance()
D/elm:15121( 7336): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 7352): MountEmulatedStorage()
E/Zygote  ( 7352): v2
I/libpersona( 7352): KNOX_SDCARD checking this for 10029
I/libpersona( 7352): KNOX_SDCARD not a persona
I/SELinux ( 7352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7352 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 7352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/elm:15121( 7336): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:15121( 7336): ElmAgentService : onDestroy().
D/TimaKeyStoreProvider( 7352): TimaSignature is unavailable
D/ActivityThread( 7352): Added TimaKeyStore provider
I/art     ( 1018): Explicit concurrent mark sweep GC freed 5702(297KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.662ms total 171.107ms
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/FeatureConfig( 7352): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
I/SA      ( 5086): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5086): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/PackageManager( 1018): delete codoeFile: 
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1018): UID=10338 Target=com.test.thalitest
D/PackageManager( 1018): result of delete: 1{552620570}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/AndroidRuntime( 7323): Shutting down VM
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/Zygote  ( 7370): MountEmulatedStorage()
E/Zygote  ( 7370): v2
I/libpersona( 7370): KNOX_SDCARD checking this for 10039
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/libpersona( 7370): KNOX_SDCARD not a persona
I/SELinux ( 7370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7370 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
D/TimaKeyStoreProvider( 7370): TimaSignature is unavailable
D/ActivityThread( 7370): Added TimaKeyStore provider
W/libprocessgroup( 1018): failed to open /acct/uid_10131/pid_5963/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10011/pid_6163/cgroup.procs: No such file or directory
E/SMD     (  303): DCD OFF
W/ResourcesManager( 7352): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7370): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7370): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7370): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7370): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7370): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7370): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7370): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/GalaxyFinderApplication( 7352): system/finder_cp/cpdata.xml file not found
D/NearbySource( 7370): Nearby Source Create!
D/NearbyContext( 7370): Nearby Context Create!
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7370): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 7370): Samsung link source created
W/art     ( 7323): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/ContactProvider( 7370): getAllContactInfoList Start
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/PackagesMonitor( 7370): PackagesMonitor onReceive :com.test.thalitest
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/ContactProvider( 7370): getAllContactInfoList End
I/syncContacts( 7370): thread: 1153, sync time = 44
W/FileUtils( 7370): Failed to chmod(/data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7393): MountEmulatedStorage()
E/Zygote  ( 7393): v2
I/libpersona( 7393): KNOX_SDCARD checking this for 10041
I/libpersona( 7393): KNOX_SDCARD not a persona
I/SELinux ( 7393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7393 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5680:com.google.android.apps.books/u0a71 (adj 15): empty #31
I/SELinux ( 7393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7393): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7393): TimaSignature is unavailable
D/ActivityThread( 7393): Added TimaKeyStore provider

```
